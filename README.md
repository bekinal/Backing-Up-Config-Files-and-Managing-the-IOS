<h1>Backing Up Config Files and Managing the IOS</h1>

<h2>Description</h2>
Project consists of using a Trivial File Transfer Protocol (TFTP) server to back up and roll out switch configurations. This lab consists of a pre-configured network consisting of a TFTP Server, a switch, and a router.
<br />


<h2>Utilities Used</h2>

- <b>VirtualBox</b> 
- <b>Cisco Packet Tracer</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Back Up Configuration Files:</h2>
The .pka file is opened to exmaine the topology. Switch 1 is opened, and the CLI is navigated to: <br/>
<img src="https://imagizer.imageshack.com/img922/9844/gUnWiX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The Enable command is entere to grant elevated privileges. Then, configure terminal mode is entered. Two users are then created under the interface: <br/>
<img src="https://imagizer.imageshack.com/img924/9084/uyh3Js.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The console is secured by enabling local password checking: <br/>
<img src="https://imagizer.imageshack.com/img924/3254/2awk4T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The enable password is changed top c!sc0: <br/>
<img src="https://imagizer.imageshack.com/img922/6033/EzJxHZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
All passwords on the device are then encrypted: <br/>
<img src="https://imagizer.imageshack.com/img922/2359/ES940D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A security message (banner) is then created: <br/>
<img src="https://imagizer.imageshack.com/img922/2019/JfYI8V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DNS lookup is disabled on the device: <br/>
<img src="https://imagizer.imageshack.com/img924/2476/9NdA67.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The following command is then entered to execute all of our changes on the device: <br/>
<img src="https://imagizer.imageshack.com/img922/6755/8Bu4mm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The TFTP service is then turned on by navigating to its services window: <br/>
<img src="https://imagizer.imageshack.com/img922/3209/KF40eg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The running config file is then copied to the TFTP server: <br/>
<img src="https://imagizer.imageshack.com/img924/1479/ZudLBV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The config file is verified on the TFTP server under the Services tab: <br/>
<img src="https://imagizer.imageshack.com/img923/4746/4yDLAZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<h2>Back Up and Upgrade the Device ISO:</h2>
: <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
