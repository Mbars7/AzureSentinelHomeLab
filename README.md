<h1>Azure Sentinel Home Lab</h1>


<h2>Description</h2>
- Used custom PowerShell script to extract metadata from Windows Event Viewer to be forwarded to third-party API to derive geolocation data. <br>
- Configured Log Analytics Workspace in Azure to ingest custom logs containing geographic information (latitude, longitude, state/province, and country)<br>
- Configured custom fields in Log Analytics Workspace with the intent of mapping geo data in Azure Sentinel<br>
- Configured Azure Sentinel (Microsoft's cloud SIEM) workbook to display global attack data (RDP brute force) on world map according to physical location and magnitude of attacks.<br>

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Sentinel</b>

<h2>Environments Used </h2>
- <b>Azure</b><br>
- <b>Windows 10</b> (22H2)

<h2>Project Snapshots:</h2>

<p align="center">
Azure VM Deployment: <br/>
<img src="https://i.imgur.com/3Rl2sXq.jpg"/>
<br />
<br />
Configuring firewall wide open:  <br/>
<img src="https://i.imgur.com/AiEnuDg.jpg"/>
<br />
<br />
Remotely connecting to VM: <br/>
<img src="https://i.imgur.com/xD8g4ex.jpg"/>
<br />
<br />
Making VM vulnerable:  <br/>
<img src="https://i.imgur.com/iEIwJam.jpg"/>
<br />
<br />
Running custom PowerShell script:  <br/>
<img src="https://i.imgur.com/zzRBcvW.jpg"/>
<br />
<br />
Active Directory Computers:  <br/>
<img src="https://i.imgur.com/zEnop5P.jpg"/>
<br />
<br />
Client Login:  <br/>
<img src="https://i.imgur.com/jQGki5m.jpg"/>
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
