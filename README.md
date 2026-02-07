<h1> Home Cybersecurity Lab Simulation
</h1>



<h2>Description</h2>
Create a fully segmented, enterprise style environment for hands-on learning, including attack tools, defensive tools, vulnerable machines, Active Directory, and Docker based services. The network architecture behind a pfSense firewall, creating VLANs, building and configuring pfSense, Kali Linux, and Ubuntu Server with Docker and Portainer.
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
<br/>

pfSense firewall installed and configured with VLANs, DHCP, rules, and Kali Linux installed and connected
<br />
<br />
<img src="https://imgur.com/MCJudkD.jpg"  height="80%" width="80%">
<br />
<br />
Ubuntu Server, Docker, Portainer installed, verified, and accessible
<br />
 <br/>
<img src="https://imgur.com/sVUYYP0.jpg"  height="80%" width="80%">
<br />
<br />

Metasploitable2 VM created, and MACVLAN networking configured bWAPP, DVWA, and WebGoat deployed. All vulnerable machines are reachable for future security tool integration
<br/>
<br />
<br />
<img src="https://imgur.com/sUjhHat.jpg"  height="80%" width="80%">
<br />
<br />
<img src="https://imgur.com/aG3GE3h.jpgh"  height="80%" width="80%">
<br />

<br />
<br />
<br />
 Wazuh server, Nessus Essential Integration of both tools into VLAN 10 (security tools segment). Firewall rule adjustments for scanning and agent communication. Initial vulnerability scans against Metasploitable2, DVWA, bWAPP, and WebGoat
<br />
<br />
<img src="https://imgur.com/Prw149V.jpg"  height="80%" width="80%">
<br />
<br />
<img src="https://imgur.com/Q8xTjxh.jpg"  height="80%" width="80%">
<br />
<br />
<img src="https://imgur.com/PgGwCDc.jpg"  height="80%" width="80%">
<br />
<br />
<br />
<br />
<br />
<br />
