# Ethical Hacking Technical Report

**Client:** [Accenture ]  
**Date:** [May 11, 2024]  
**Prepared by:** [Jomarc I. Nacario] and [Edward L. Sotto]

## Executive Summary
This report presents the technical findings of the ethical hacking assessment conducted for Accenture Inc. The assessment aimed to identify vulnerabilities within the organization's network infrastructure, applications, and systems. Through various testing methodologies, including penetration testing and vulnerability scanning, critical and high-risk issues were discovered. This report provides detailed descriptions of these findings, along with actionable recommendations for remediation.

## Vulnerability Summary

### 1. Network Infrastructure
- **Critical:** Outdated Software: Unpatched software on devices like routers, firewalls, and servers exposes them to known exploits and malware.
- **High:** Unencrypted Communication: Data transmitted in plain text can be intercepted on unsecured networks.
- **High:** Physical Security Vulnerabilities: Inadequate physical security measures allow unauthorized physical access to network devices, potentially enabling attackers to tamper with hardware or steal data.

### 2. Web Applications
- **Critical:** Remote Code Execution (RCE) vulnerability in the servers, potentially enabling an attacker to install malware, steal data, or disrupt operations.
- **High:**  Insecure Defaults configurations, such as weak passwords, unnecessary services running, or permissive file permissions , allowing attackers to exploit these defaults to gain a foothold in the system.
- **High:**  Cross-Site Request Forgery (CSRF), attackers can exploit a CSRF vulnerability by forging a request that appears to originate from your authenticated browser. This can be used to perform unauthorized actions like transferring funds or changing account settings.

### 3. Operating Systems
- **Critical:** Missing or Outdated Antivirus and Anti-Malware Software, systems are vulnerable to malware infections that can steal data, disrupt operations, or even launch further attacks.
- **High:**  Local File Inclusion (LFI) application includes a local file based on user-supplied input, attackers can exploit this to execute arbitrary code on the server, potentially gaining unauthorized access or compromising the system.

### 4. Wireless Networks
- **Critical:** Default Passwords in routers,  pre-configured default passwords are widely known and easily guessable, making them a prime target for attackers.

### 5. Social Engineering
- **High:** Attackers might gather information about individuals through social media or data breaches to personalize their social engineering attempts, making them seem more legitimate.
## Recommendations

### 1. Network Infrastructure
- Regularly update operating systems, firmware, and applications with the latest security patches.
- Encrypt data at rest and in transit using strong encryption algorithms.
- Secure server rooms and network equipment with restricted access control.
- Implement security cameras and intrusion detection systems to monitor physical access points.

### 2. Web Applications
- Maintain a strict patch management process to keep all software on the web server updated with the latest security patches.
- Change all default passwords and configurations upon initial deployment.
- Implement CSRF protection mechanisms like synchronizer tokens (anti-CSRF tokens) that validate the user's intent along with the request. Enforce stricter same-site cookie attributes to further prevent CSRF attacks.

### 3. Operating Systems
- Install and maintain reputable antivirus and anti-malware software with real-time protection features. Configure them to automatically update virus definitions regularly.
-  Validate and sanitize user input to prevent them from specifying unintended files. Utilize secure coding practices to avoid LFI vulnerabilities in custom applications.

### 4. Wireless Networks
- Change the default router password to a strong and unique password that uses a combination of upper and lowercase letters, numbers, and symbols. Consider using a password manager to generate and store strong passwords for all your devices.

### 5. Social Engineering
- Organizations should have policies on responsible social media use and data protection. Employees should be mindful of the information they share online and be cautious of unsolicited communications that reference personal details.

## Conclusion
The results of the ethical hacking assessment have revealed several crucial vulnerabilities and security weaknesses in Accenture Inc.'s cybersecurity. By implementing the recommended remedial actions, Accenture Inc. can substantially improve its security stance and reduce the risk of cyber attacks and data breaches.

**Signature:** [Nacario, Sotto]
