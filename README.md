# SIEM---Microsoft-Azure-Project

 ### [YouTube Reference](https://www.youtube.com/watch?v=RoZeVbbZ0o0)

<h2>Description</h2>
I setup Azure Sentinel (SIEM) and connect it to a live virtual machine acting as a honey pot. Observed live attacks (RDP Brute Force) from all around the world. Used a custom PowerShell script to look up the attackers Geolocation information and plot it on the Azure Sentinel Map!.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Remote Desktop Protocol</b>

<h2>Environments Used </h2>

- <b> Microsoft Azure VM </b> 
- <b> Microsoft Azure - Log Workspace Analytics </b> 
- <b>Microsoft Azure Sentinel </b> 

<h2>Program walk-through:</h2>


<p align="center">
Creating Honey Pot: <br/> 
  
<img src="https://imgur.com/hC0rsAH.png" height="80%" width="80%" alt="HomeLab Steps"/>
<br />
<br />
Creation of Log Analytics Workplace: <br/>
<img src="https://imgur.com/UrrY7Zf.png" height="80%" width="80%" alt="HomeLab Steps"/>
<br />
<br />
Logging into Virtual Machine: Remote Desktop Protocol: <br/>
<img src="https://imgur.com/C1pf42Z.png" height="80%" width="80%" alt="HomeLab Steps"/>
<br />
<br />
Disabling of Windows Firewall:  <br/>
<img src="https://imgur.com/XwUqxzO.png" height="80%" width="80%" alt="HomeLab Steps"/>
<br />
<br />
Successful ping after disabling firewall:  <br/>
<img src="https://imgur.com/M5WSnaB.png" height="80%" width="80%" alt="HomeLab Steps"/>
<br />
<br />
Event log on Event Viewer:  <br/>
<img src="https://imgur.com/cr0AmjR.png" height="80%" width="80%" alt="HomeLab Steps"/>
<br />
<br />
Executing PowerShell script to capture logs:  <br/>
<img src="https://imgur.com/I7syoe3.png" height="80%" width="80%" alt="HomeLab Steps"/>
</p>

Event log capture through Azure:  <br/>
<img src="https://imgur.com/XsCG4RH.png" height="80%" width="80%" alt="HomeLab Steps"/>
</p>

Event 4625 event part 1:  <br/>
<img src="https://imgur.com/rAjR7l8.png" height="80%" width="80%" alt="HomeLab Steps"/>
</p>

Event 4625 event part 2:  <br/>
<img src="https://imgur.com/2ITCsWp.png" height="80%" width="80%" alt="HomeLab Steps"/>
</p>

SIEM Data Visualization:  <br/>
<img src="https://imgur.com/IqA9old.png" height="80%" width="80%" alt="HomeLab Steps"/>
</p>

SIEM Geolocation Map:  <br/>
<img src="https://imgur.com/eYzwUpn.png" height="80%" width="80%" alt="HomeLab Steps"/>
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
