<h1> Home Cybersecurity Lab Simulation

</h1>



<h2>Description</h2>

<br />
<h2> Tech Stack</h2>

Proxmox VE : https://www.virtualbox.org/wiki/Downloads](https://www.proxmox.com/en/downloads
<br />
Kali Linux :                             https://www.kali.org/get-kali/#kali-installer-images
<br />
Windows 10 :                             https://www.microsoft.com/en-ca/software-download/windows10iso
<br />
Windows 11 :                            https://www.microsoft.com/en-us/software-download/windows11
<br />
Window Server 22 :                       https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022
<br />
Ubuntu :                                https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview
<br />
Ubuntu Server :     https://ubuntu.com/download/server
<br />
Docker(install on Kali) :                 https://www.kali.org/docs/containers/installing-docker-on-kali/
<br />
Portainer.io (install on Docker) :       https://docs.portainer.io/start/install-ce/server/docker/linux
<br />
Wazuh :                                https://documentation.wazuh.com/current/deployment-options/virtual-machine/virtual-machine.html
<br />
Metasploitable :         https://koromatech.com/how-to-install-metasploitable-2-on-a-proxmox-vm-step-by-step-walkthrough/
<br />
pfSense :          https://www.pfsense.org/download/

<h2></h2>
<br />
<img src="https://imgur.com/L7acb1x.jpg"  height="80%" width="80%">
<br />
<br />
<img src="https://imgur.com/ajc26sg.jpg"  height="80%" width="80%">
<br />
<br />
<img src="https://imgur.com/BHhJuDb.jpg"  height="80%" width="80%">
<br /><br />
<img src="https://imgur.com/LFo3M6t.jpg"  height="80%" width="80%">
<br /><br />
<img src="https://imgur.com/NC5uCfL.jpg"  height="80%" width="80%">
<br />
<br />
<img src="https://imgur.com/1AANkAr.jpg"  height="80%" width="80%">
<br />

<h2>  Walk-through:</h2>

<p align="center">
VM SetUP <br/>

Open VirtualBox and click New   || Name the VM  and choose Type and ISO file → After VM Setup
Start the VM
<br />
<br />
<img src="https://imgur.com/KfKxyeG.jpg"  height="80%" width="80%">
<br />
login to Elastic and setup defend intergration  <br/>
<img src="https://imgur.com/eEtAYJk.jpg"  height="80%" width="80%">
<br />
<br />

<p align="center">
Copy agent to Clipboard and deploy into Kali  <br/>

<br />
<br />
<img src="https://imgur.com/xbPDnoi.jpg"  height="80%" width="80%">
<br />
 AFTER AGENT ENROLLMENT CONFORMED <br/>
<img src="https://imgur.com/fg34aDu.jpg"  height="80%" width="80%">
<br />
<br />
  
<br />
Elastic dashboard showing top users/hosts for Windows Event 4625 authentication failures <br/>
<img src="https://imgur.com/K7kftdh.jpg"  height="80%" width="80%">
<br />
<br />

<img src="https://imgur.com/Q1tC0Zg.jpg"  height="80%" width="80%">
<br />

<img src="https://imgur.com/jnwRWam.jpg"  height="80%" width="80%">
<br />
<br />

<img src="https://imgur.com/R0ZiSiw.jpg"  height="80%" width="80%">
<br />
<br />
<br />
Monitoring authentication anomalies: failed logons across all users and admin accounts, disabled user activity, service account RDP usage, and real time group membership changes  <br/>
<img src="https://imgur.com/ixCzoN2.jpg"  height="80%" width="80%">

<br />
<br />
<br />
Successful RDP logon related to service accounts
<img src="https://imgur.com/LXSyFxL.jpg"  height="80%" width="80%">
<br />
<br />
Users add or removed from a local group within a specific timeframe (2023-03-05) 
<img src="https://imgur.com/hSHLJWB.jpg"  height="80%" width="80%">
<br />
<br />


<img src="https://imgur.com/D5xWhfS.jpg"  height="80%" width="80%">
<br />
<br />

<img src="https://imgur.com/VmP6tx2.jpg"  height="80%" width="80%">
<br />
<br />
<br />
<br />
