<h1>Ransomware Investigation</h1>

<h2>Description</h2>
We'll employ LetsDefend, a premier Blue Team Cybersecurity training platform, to investigate a ransomware alert from our SIEM. This strategic analysis aims to enhance our incident response capabilities and fortify cyber defenses effectively.
<br />


<h2>Programs used</h2>

- <b>LetsDefend</b> 
- <b>MD5 AND SHA Checksum Utility</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
First, we will document our information on a notepad to have it easily accessible. Then we will need to download the zip file: <br/>
<img src="https://i.imgur.com/MInI8Gf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Unzip and extract "ab.bin" from the downloaded file. Add it to VirusTotal for malware detection and analysis:  <br/>
<img src="https://i.imgur.com/eFfxzpl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter your "ab.bin" file to MD5 AND SHA Checksum Utility. Copy MD5 and document it into your notepad: <br/>
<img src="https://i.imgur.com/iSW3bgT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Input Mark's IP address in the endpoint security interface and initiate containment to isolate his machine for investigation. This ensures effective mitigation of security risks and creates a secure environment for analysis:  <br/>
<img src="https://i.imgur.com/tzUIfGD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In log management, search Mark's IP address. Note the two websites and their IP addresses found. Copy and document this in your notepad for analysis:  <br/>
<img src="https://i.imgur.com/g1y8HTp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now we will document our findings in incident details, providing a value, type, and comment:  <br/>
<img src="https://i.imgur.com/NsT9cAu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
