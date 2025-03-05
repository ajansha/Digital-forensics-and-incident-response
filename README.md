This project explores both offensive and defensive aspects of cybersecurity by simulating a real-world cyber attack and conducting a digital forensic investigation. A vulnerable Windows machine was targeted, exploited, and later analyzed to reconstruct the attack timeline and identify key evidence.

Using Kali Linux, Metasploit, and Nmap, vulnerabilities were discovered and exploited, leading to unauthorized system access. Post-exploitation activities included privilege escalation, credential dumping, and malware execution, demonstrating the tactics used by attackers to maintain persistence.

Following the attack, forensic techniques were applied to uncover traces left behind. Network traffic analysis with Security Onion revealed scanning activities, suspicious SMB traffic, and remote command execution. Memory forensics with Volatility helped identify injected malicious processes, unauthorized user accounts, and PowerShell-based attacks. Disk analysis with Autopsy recovered deleted files, logs, and malware artifacts, piecing together the attacker’s actions.

This project provided hands-on experience in penetration testing, incident response, and forensic analysis, highlighting how attacks unfold and how investigators can trace and mitigate them.
