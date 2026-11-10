FTP Exploitation Using Metasploit

1. Project Overview

This project demonstrates how a vulnerable FTP service can be identified and tested using Metasploit in a controlled lab environment.

2. Objective

- Identify a vulnerable FTP service.
- Understand FTP vulnerabilities.
- Learn how Metasploit works.
- Understand the risks of vulnerable FTP services.

3. Lab Environment

- Attacker: Kali Linux
- Target: Metasploitable 2
- Virtualization: VMware
- Tool: Metasploit Framework
- Protocol: FTP (Port 21)

4. Methodology

Step 1: Starting the Lab

Started Kali Linux and Metasploitable 2 in VMware.

<img width="634" height="170" alt="Screenshot 2026-10-26 at 8 45 24 AM" src="https://github.com/user-attachments/assets/e111ddd7-ac68-4cfb-9053-256f4ee4225c" /> 1 HERE – VMware showing Kali Linux and Metasploitable 2 running.

Step 2: Identifying the Target IP

Identified the IP address of the target machine.

<img width="924" height="288" alt="Screenshot 2026-10-26 at 8 47 38 AM" src="https://github.com/user-attachments/assets/849eac77-8ff2-425d-a010-082ae514c1d8" /> 2 HERE – Terminal showing the target IP address.

Step 3: Scanning the Target

Performed a network scan to identify open ports and the FTP service.

<img width="649" height="258" alt="Screenshot 2026-10-26 at 8 48 30 AM" src="https://github.com/user-attachments/assets/7bd3220d-f392-4623-b262-bd8faa8937b1" /> 3 HERE – Nmap scan showing FTP port 21.

Step 4: Using Metasploit

Opened Metasploit Framework and selected the appropriate FTP vulnerability assessment module.

<img width="643" height="283" alt="Screenshot 2026-10-26 at 8 49 52 AM" src="https://github.com/user-attachments/assets/e6c0a51d-6cc8-4a79-9198-dffeff14eb35" /> 4 HERE – Metasploit terminal showing the selected module and configuration.

Step 5: Final Assessment

Documented the outcome of the FTP vulnerability assessment.

<img width="642" height="214" alt="Screenshot 2026-10-27 at 2 44 47 AM" src="https://github.com/user-attachments/assets/c0ea23a1-03b2-4b73-b8d8-dfa280dd36b2" /> 5 HERE – Final Metasploit assessment result.

5. Results

Status: [Successful / Unsuccessful]

The assessment demonstrated the security risks associated with vulnerable FTP services.

6. Security Recommendations

- Keep FTP services updated.
- Disable unnecessary services.
- Use secure file transfer protocols such as SFTP.
- Monitor network activity.
- Regularly scan systems for vulnerabilities.

7. Conclusion

This practical exercise improved my understanding of FTP vulnerabilities, network scanning and vulnerability assessment using Metasploit.

Disclaimer: This project was conducted strictly for educational purposes in an isolated virtual lab.
