# Building-a-Resilient-Cybersecurity-Home-Lab

<h2>📚 Introduction</h2>
Welcome to my first cybersecurity project 🌐💻. I will be building a robust Cybersecurity Home Lab, this is a dedicated environment set up used to simulate real-world cyber threats, vulnerabilities, and security scenarios in a controlled and isolated space. This project will not be about wires and machines but will be done virtually as we gain hands-on learning, develop skills, and experiment with various cybersecurity tools and techniques without the risk of impacting a live network.

<h2>🛠️ Tools That I Used</h2>

- <b>[VirtualBox🔄-(Download the version for your operating system)](https://www.virtualbox.org/wiki/Downloads)</b>: This is an open-source virtualization platform that allows us to create and manage virtual machines (VMs). For our cybersecurity home lab, I would be using it to simulate diverse operating systems and network configurations within isolated environments.
- <b>[Kali Linux🏴‍☠️💻-(Download the VirtualBox 64-bit version)](https://www.kali.org/get-kali/#kali-virtual-machines)</b>: This is a Linux distribution designed for penetration testing, ethical hacking, and cybersecurity activities. In this home lab, I will use it as our primary toolkit for conducting security assessments, vulnerability analysis, and hands-on penetration testing exercises.
- <b>[Windows 11 Operating system 🖥️-(Download the VirtualBox version)](https://developer.microsoft.com/en-us/windows/downloads/virtual-machines/)</b>: We would use this OS to provide us with an environment for testing security measures and vulnerabilities. It allows you to explore and understand the security features, configurations, and potential weaknesses present in a Windows environment.
- <b>[Windows Server 2019 🌐-(Download the ISO file)](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2019)</b>: This is a server operating system that joins Windows 11 OS to a server environment. For our Home Lab, we would use it to simulate and secure network infrastructures, implement Active Directory services and explore server-side vulnerabilities.
- <b>[Metasploitable 🎯-(The link downloads automatically)](https://sourceforge.net/projects/metasploitable/files/Metasploitable2/metasploitable-linux-2.0.0.zip/download )</b>: This is a purposely vulnerable virtual machine designed for penetration testing and security training. I will use it to simulate a target environment with intentionally weak configurations and known vulnerabilities, making it an ideal resource for practicing ethical hacking techniques.

<h2>🔄💻 Required System Requirement: I use an HP ENVY x360 Laptop (Not the best but it does the job)</h2>

- <b>[🧠 CPU: 13th Gen Intel(R) Core(TM) i7-1355U 1.70 GHz (Anything higher than this will work)]</b>
- <b>[💾 RAM: 16GB (gigabytes) of RAM (I will say 8 GB of RAM or higher will suffice)]</b>
- <b>[📀 Disk: 1TB (Terabyte) (500GB - 1000GB of free disk space will be enough)]</b>
- <b>[🔄 BIOS/UEFI: VT-x, AMD-V, or the equivalent must be enabled in the BIOS/UEFI]</b>
- <b>[🔧 System Type: 64-bit operating system, x64-based processor (⚠️MANDATORY: This is a must)]</b>

<h2>[📝 Step by Step Guide To Setting Up Your Cybersecurity Home Lab (Note: For this project, we would only be setting up the Home lab and connecting each tool, then using it for future projects.]

- <b>[THIS LINK IS A WELL-DETAILED GUIDE OF THE PROJECT](https://www.youtube.com/watch?v=BwAD8w05D5A&list=PLUkY1OVVHzVktZOecfiDxdIodK4l5KkwY&index=1&pp=iAQB)</b>

- <b>STEP 1: Download and install VirtualBox from the official website. Follow the installation instructions for your operating system.</b>
- <b>STEP 2: Download and exact all the other tools (Kali Linux, Windows server 2019, Windows 11 OS, and Metasploitable). Lastly, you can also put everything in a designated folder to make it look organized.</b>
<img width="784" alt="Screenshot 2023-12-27 131015" src="https://github.com/IsaacOribamise/Building-a-Resilient-Cybersecurity-Home-Lab/assets/154943957/a3fb8b1d-6346-4719-9546-4648e7d757f2">


(The only tool that needs installing on your computer is your VirtualBox the rest will be installed in the virtual environment, and some of the files will need to be extracted. Lastly, you can also put everything in a designated folder to make it look nice).
1. Install VirtualBox:

Download and install VirtualBox from the official website: VirtualBox Downloads.
Follow the installation instructions for your operating system.
2. Download Kali Linux:

Visit the official Kali Linux website: Kali Linux Downloads.
Download the appropriate version of Kali Linux (e.g., 64-bit ISO).
3. Create a Kali Linux VM:

Open VirtualBox and click on "New" to create a new virtual machine.
Name the VM (e.g., "Kali Linux") and select "Linux" as the type, and "Debian (64-bit)" as the version.
Allocate RAM (at least 2GB) and create a new virtual hard disk (dynamic allocation recommended).
Attach the Kali Linux ISO to the VM and start the VM.
4. Install Kali Linux:

Follow the on-screen instructions to install Kali Linux.
Choose your language, location, and keyboard layout.
When prompted for disk partitioning, select "Guided - use entire disk" for simplicity.
5. Download Windows 10 and Server 2019 ISOs:

Download the Windows 10 and Server 2019 ISO files from the official Microsoft website or appropriate sources.
6. Create Windows VMs:

Repeat the process in step 3 to create two new VMs for Windows 10 and Server 2019.
Customize VM settings such as RAM, CPU, and storage based on your preferences.
7. Install Windows OS:

Start the Windows 10 VM and install the OS by attaching the Windows 10 ISO.
Repeat the process for the Server 2019 VM.
8. Download Metasploitable:

Download the Metasploitable 2 virtual machine from the Rapid7 website: Metasploitable Downloads.
9. Import Metasploitable VM:

In VirtualBox, click on "File" > "Import Appliance" and select the downloaded Metasploitable OVA file.
Adjust settings if needed and import the VM.
10. Connect VMs in a Network:

In VirtualBox, select each VM and go to "Settings" > "Network."
Choose the "Bridged Adapter" for each VM to connect them to the same network.
11. Start the Lab:

Start all VMs in the desired order: Kali Linux, Windows 10, Server 2019, Metasploitable.
12. Explore and Practice:

Use Kali Linux for ethical hacking, penetration testing, and security assessments.
Practice securing and managing Windows environments on the Windows VMs.
Explore vulnerabilities and conduct penetration tests on Metasploitable.

- <b>[📀 Disk: 1TB (Terabyte) (500GB - 1000GB of free disk space will be enough)]</b>
- <b>[🔄 BIOS/UEFI: VT-x, AMD-V, or the equivalent must be enabled in the BIOS/UEFI]</b>
- <b>[🔧 System Type: 64-bit operating system, x64-based processor (⚠️MANDATORY: This is a must)]</b>
  - [Keylogger](https://github.com/richardsaunders215/keylogger)
  - [FTP Scanner](https://github.com/richardsaunders215/FTP-Scanner)
  - [Hello World](https://github.com/richardsaunders215/hello-world)

<h2> 📜 Certifications</h2>

- [CompTia Security+](https://www.linkedin.com/in/richard-saunders/overlay/1635533065164/single-media-viewer/?profileId=ACoAAAi9JLUBzkljOcfRT5P6CjVk_CXH6ewZJ68)
- [CompTia Network+](https://www.freecodecamp.org/certification/fccc343b5d9-d835-49bd-8602-059bc7f4099c/data-analysis-with-python-v7)
- [CompTia A+](https://www.coursera.org/account/accomplishments/verify/9LQZSNAHMXYS)
- [ITIL Fundamentals](https://www.coursera.org/account/accomplishments/verify/9LQZSNAHMXYS)

<h2>🌱 My Goal</h2>


<h2>🌱 I'm currently Learning</h2>

- Cybersecurity
- Large Language Learning Models
- Power BI/Tableau

<h2> 🤳 Connect with me:</h2>

- Let's connect and share our passion for cybersecurity!
- Feel free to reach out for collaborations, discussions, or just to geek out over the latest exploits. 
- My linkedin page is below:

[<img align="left" alt="RichardSaunders | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]

[linkedin]: https://www.linkedin.com/in/isaac-oribamise/

<!--
**joshmadakor1/joshmadakor1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
