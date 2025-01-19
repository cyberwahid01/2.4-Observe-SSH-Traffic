<p align="center">
<img src="https://imgur.com/wYucC7L.png" alt="osTicket logo"/>
</p>

<h1>Microsoft Azure Compute and Networking 🪟 - Observe SSH Traffic</h1>
Next in this section of using Wireshark, I use the SSH (Secure Shell) Protocol to connect to the Linux VM from within the Windows VM using Powershell. <br /> (Link Back to Main Project Contents Page is at the Bottom of this Repo)

<h2>Environments and Technologies Used</h2>

- Lenovo Ideapad 5 Pro 16gb AMD Ryzen 7
- Microsoft Azure Resource Group (from [Part 1 - Setting Up Virtual Machines](https://github.com/cyberwahid01/2.1-Virtual-Machine-Setup))
- Microsoft Azure Windows 10 Pro version 22H2 - x64 Gen2 Virtual Machine (from [Part 1 - Setting Up Virtual Machines](https://github.com/cyberwahid01/2.1-Virtual-Machine-Setup))
- Microsoft Azure Ubuntu Pro 24.04 LTS - x64 Gen2 Virtual Machine (from [Part 1 - Setting Up Virtual Machines](https://github.com/cyberwahid01/2.1-Virtual-Machine-Setup))
- Wireshark Network Protocol Analyzer Software
- Windows Powershell

<h2>Operating Systems Used </h2>

- Local Windows 11 Home Version 21H2</b>
- Windows 10 Pro version 22H2 Virtual Machine
- Ubuntu Pro 24.04 LTS - x64 Gen2 Virtual Machine

<h2>List of Prerequisites</h2>

- Microsoft Azure Subscription
- Microsoft Azure Subsription Credit
- Wireshark Installed on Windows 10 Virtual Machine

<h2>Installation, Setup, Resource Setup, Executing Functions</h2>

1. For using the SSH Protocol, I initiated packet capture with Wireshark, filtered it for SSH traffic only, and from Windows Powershell, I used the command ssh CyberWahidNetworking@10.0.0.6 to connect into the Linux VM Server. From the green text at the bottom of Powershell we can see the successful connection to the Linux VM.
<p>
<img src="https://imgur.com/9PxwVxa.png" alt="Disk Sanitization Steps"/>
</p>
<p>
2. I then exited out of the Linux VM using the command $ exit and as we can see the original connection to the Windows VM was reestablished.
</p>
<br />

<p>
<img src="https://imgur.com/jNvY1ra.png" alt="Disk Sanitization Steps"/>
</p>
<p>
LINK BACK TO THE MAIN PROJECT CONTENTS PAGE - https://github.com/cyberwahid01/Azure-Compute-and-Networking
