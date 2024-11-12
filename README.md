<h1>Basic Virtual Box Home lab</h1>



<h2>Languages and Utilities Used</h2>

- <b>VirtualBox</b> 
- <b>Kali Linux</b>
- <b>Windows 10 VM</b>
- <b>7-Zip</b>
- <b>Command Prompt (Windows)</b>
- <b>Pyhton</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Kali Linux</b>

<h2>Program walk-through:</h2>

<p align="center">
Download and install windows 10 as the OS on the virtual machine, and also download kali linux on the virtual machine as attacker machine: <br/>
<img src="https://i.imgur.com/CA0C8ej.jpeg.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />
Windows 10 powered and running on the virtual machine:  <br/>
<img src="https://i.imgur.com/LfmEfxj.png.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />
Kali linux also powered and running on the virtual machine: <br/>
<img src="https://i.imgur.com/tf5J4D3.png.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />
Assigned a static IP to the windows machine:  <br/>
<img src="https://i.imgur.com/6D7m9rw.jpeg.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />
Assigned a static IP on kali:  <br/>
<img src="https://i.imgur.com/wOfbdfR.jpeg.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />
Confirmation that there’s connectivity between the two PCs:kali and windows:  <br/>
<img src="https://i.imgur.com/or85oRf.jpeg.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />
Msfvenom to create payload for basic malware:  <br/>
<img src="https://i.imgur.com/9IO0OHz.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />
List of msf payloads:  <br/>
<img src="https://i.imgur.com/Kluopyx.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />
Meterpreter reverse tcp payload is instructed to connect to my machine based on the lhost and lport:  <br/>
<img src="https://i.imgur.com/0BIg4iH.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />
Exploit console:  <br/>
<img src="https://i.imgur.com/vXy8N5r.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />
Lhost address changed to the windows address:  <br/>
<img src="https://i.imgur.com/XBWK0kf.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />
Used Pyhton to allow test machine act as kali machine and start downloading malware:  <br/>
<img src="https://i.imgur.com/qrAraAX.png" height="80%" width="80%" alt="Home lab Steps"/>
<br />
<br />




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
