<h1>Azure Sentinel Home Lab</h1>
<p align="center">
 <img src="https://i.imgur.com/CGAdkfg.jpg"/>
</p>

<h2>Description</h2>
- Used custom PowerShell script to extract metadata from Windows Event Viewer to be forwarded to third-party API to derive geolocation data. <br>
- Configured Log Analytics Workspace in Azure to ingest custom logs containing geographic information (latitude, longitude, state/province, and country)<br>
- Configured custom fields in Log Analytics Workspace with the intent of mapping geo data in Azure Sentinel<br>
- Configured Azure Sentinel (Microsoft's cloud SIEM) workbook to display global attack data (RDP brute force) on world map according to physical location and magnitude of attacks.<br>

<h2>Languages and Utilities Used</h2>
- <b>PowerShell</b><br>
- <b>Sentinel</b>

<h2>Environments Used </h2>
- <b>Azure</b><br>
- <b>Windows 10</b> (22H2)

<h2>Project Snapshots:</h2>

<p align="center">
Azure VM Deployment: <br/>
<img src="https://i.imgur.com/JVpbB3D.jpg"/>
<br />
<br />
Configuring firewall wide open:  <br/>
<img src="https://i.imgur.com/USYAcCN.jpg"/>
<br />
<br />
Remotely connecting to VM: <br/>
<img src="https://i.imgur.com/dsqmSjf.jpg"/>
<br />
<br />
Making VM vulnerable:  <br/>
<img src="https://i.imgur.com/DP8B4TJ.jpg"/>
<br />
<br />
Running custom PowerShell script:  <br/>
<img src="https://i.imgur.com/A3S3nTx.jpg"/>
<br />
<br />
Create Sentinel Workbook and run query:  <br/>
<img src="https://i.imgur.com/oBO4XYk.jpg"/>
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
