# Log Analysis and Threat Hunting with Windows Event logs and Splunk
## Inserting Logs on Splunk.
This repository explains how to insert windows event logs on Splunk
<br />


## Utilities Used

- <b>Windows 11</b>

<h2>Environments Used </h2>

- <b>Virtual Box</b>

## Project Walk-Through

### Project installation tools

| Tool Name | Why It Was Used | Download Link |
|-----------|---------------------------|---------------|
| VirtualBox | Used to create and manage virtual machines for the lab environment. | [Download](https://www.virtualbox.org/) |
| Windows 11 Enterprise | Will be used as our client machine | [Download](https://www.microsoft.com/en-us/evalcenter/download-windows-11-enterprise) |
| Splunk | a SIEM tool used for incident response and event management | [Download](https://www.splunk.com/en_us/download/splunk-enterprise.html) |
| Windows Event Log | .csv log file that was recorded from our target's windows system | [Download](https://github.com/M122/Splunk_Exercise/archive/refs/tags/v1.0.0.zip) |

<!--- INSERTING WINDOWS EVENT LOGS IN SPLUNK --->

### Inserting Logs in Splunk

<br/>

<p align="center">
  <strong>Step 1:</strong> Go to settings and choose "Add Data"<br/>
<img alt="image" src="https://github.com/user-attachments/assets/033638b3-ec4d-4f90-857b-b8804eefb6dd" height="80%" width="80%"/>
  
<br />
<br />


<p align="center">
  <strong>Step 2:</strong> Choose Upload<br/>
<img alt="image" src="https://github.com/user-attachments/assets/5744f168-51da-4e3d-9386-8b2ff4481574" height="80%" width="80%"/>
  
<br />
<br />

<p align="center">
  <strong>Step 3:</strong> Choose Select<br/>
<img alt="image" src="https://github.com/user-attachments/assets/1943921b-58a7-4461-b144-543b9227193c" height="80%" width="80%"/>
  
<br />
<br />

<p align="center">
  <strong>Step 4:</strong> Choose .csv file<br/>
<img alt="image" src="https://github.com/user-attachments/assets/7fda4ea4-87b9-4c1f-bcd5-baf505757b58" height="80%" width="80%"/>
  
<br />
<br />

<p align="center">
  <strong>Step 5:</strong> <br/>
<img alt="image" src="https://github.com/user-attachments/assets/e64a6474-7884-4fee-861a-40bc9048ca32" height="80%" width="80%"/>
  
<br />
<br />

<p align="center">
  <strong>Step 6:</strong> <br/>
<img alt="image" src="https://github.com/user-attachments/assets/6dd06d7f-8106-4e33-a51c-4f03d3734a13" height="80%" width="80%"/>
  
<br />
<br />

<p align="center">
  <strong>Step 7:</strong> Create new index<br/>
<img alt="image" src="https://github.com/user-attachments/assets/5a527e2d-e1e2-4a43-9b4b-c048b53ca3ac" height="80%" width="80%"/>
  
<br />
<br />

<p align="center">
  <strong>Step 8:</strong> Give a name to your index<br/>
<img alt="image" src="https://github.com/user-attachments/assets/67933068-9bcd-47bc-bd65-95878e868a01" height="80%" width="80%"/>
  <br/>
  NB: The name given above wasn't accepted during the final step, so it's better to avoid using "_". <br/>
  Once this is done, Click on Review > Submit > Start Searching.
<br />
<br />

<p align="center">
  <strong>Step 9:</strong> Start Searching<br/>
<img alt="image" src="https://github.com/user-attachments/assets/81c20f4d-2faa-4617-8b82-06bfd58616ac" height="80%" width="80%"/>
  
<br />
<br />

<p align="center">
  <strong>Step 10:</strong> logs Successfully inserted on Splunk<br/>
<img alt="image" src="https://github.com/user-attachments/assets/7de95e40-757f-4594-a4e0-fe5dd85036b9" height="80%" width="80%"/>
  
<br />
<br />





