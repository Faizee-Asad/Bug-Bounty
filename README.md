
# Bug-Bounty

Some Tutorials and Things to Do while Hunting Particular Vulnerability. 

## Vulnerability Rating

+ **[P1](#p1)**
+ **[P2](#p2)**
+ **[P3](#p3)**
+ **[P4](#p4)**

## P1
1. [Using Default Credentials](/P1/p1-1.md)
2. [Local File Inclusion](/P1/p1-2.md)
3. [Remote Code Execution (RCE)](/P1/p1-3.md)
4. [SQL Injection](/P1/p1-4.md)
5. [XML External Entity Injection (XXE)](/P1/p1-5.md)
6. [Authentication Bypass](/P1/p1-6.md)
7. [Disclosure of Secrets - For Publicly Accessible Asset](/P1/p1-7.md)
8. [Insecure OS/Firmware - Command Injection](/P1/p1-8.md)
9. [Insecure OS/Firmware - Hardcoded Password Privileged User](/P1/p1-9.md)
10. [Broken Cryptography - Cryptographic Flaw - Incorrect Usage](/P1/p1-10.md)

## P2
1. [Misconfigured DNS - High Impact Subdomain Takeover](/P2/p2-1.md)
2. [OAuth Misconfiguration - Account Takeover](/P2/p2-2.md)
3. [Weak Password Reset Implementation - Token Leakage via Host Header Poisoning](/P2/p2-3.md)
4. [XSS - Stored - Non-Privileged User to Anyone](/P2/p2-4.md)
5. [Server-Side Request Forgery (SSRF) - Internal High Impact](/P2/p2-5.md)
6. [Cross-Site Request Forgery (CSRF) Application-Wide](/P2/p2-6.md)
7. [Application-Level Denial-of-Service (DoS) - Critical Impact and/or Easy Difficulty](/P2/p2-7.md)
8. [Insecure OS/Firmware - Hardcoded Password - Non-Privileged User](/P2/p2-8.md)

## P3
1. [Misconfigured DNS - Basic Subdomain Takeover](/P3/p3-1.md)
2. [Mail Server Misconfiguration - No Spoofing Protection on Email Domain](/P3/p3-2.md)
3. [HTTP Response Manipulation - Response Splitting (CRLF)](/P3/p3-3.md)
4. [Content Spoofing - iframe Injection](/P3/p3-4.md)
5. [2FA Bypass](/P3/p3-5.md)
6. [Session Fixation - Remote Attack Vector](/P3/p3-6.md)
7. [Disclosure of Secrets - For Internal Asset](/P3/p3-7.md)
8. [EXIF Geolocation Data Not Stripped From Uploaded Images - Automatic User Enumeration](/P3/p3-8.md)
9. [XSS - Stored - Privileged User to Privilege Elevation](/P3/p3-9.md)
10. [XSS - Stored - CSRF/URL-Based](/P3/p3-10.md)
11. [XSS - Reflected - Non-Self](/P3/p3-11.md)
12. [Server-Side Request Forgery (SSRF) - Internal Scan and/or Medium Impact](/P3/p3-12.md)
13. [Application-Level Denial-of-Service (DoS) - High Impact and/or Medium Difficulty](/P3/p3-13.md)
14. [Client-Side Injection - Binary Planting - Default Folder Privilege Escalation](/P3/p3-14.md)

## P4
1. [Misconfigured DNS - Zone Transfer](/P4/p4-1.md)
2. [Mail Server Misconfiguration - Email Spoofing to Inbox due to Missing or Misconfigured DMARC on Email Domain](/P4/p4-2.md)
3. [Database Management System (DBMS) Misconfiguration - Excessively Privileged User / DBA](/P4/p4-3.md)
4. [Lack of Password Confirmation On Delete Account](/P4/p4-4.md)
5. [No Rate Limiting on Form - Registration](/P4/p4-5.md)
6. [No Rate Limiting on Form - Login](/P4/p4-6.md)
7. [No Rate Limiting on Form - Email-Triggering](/P4/p4-7.md)
8. [No Rate Limiting on Form - SMS-Triggering](/P4/p4-8.md)
9. [Missing Secure or HTTPOnly Cookie Flag - Session Token](/P4/p4-9.md)
10. [Clickjacking - Sensitive Click-Based Action](/P4/p4-10.md)
11. [OAuth Misconfiguration - Account Squatting](/P4%20Category/p4-11.md)
12. [CAPTCHA - Implementation Vulnerability](/P4/p4-12.md)
13. [Lack of Security Headers - Cache-Control for a Sensitive Page](/P4/p4-13.md)
14. [Web Application Firewall (WAF) Bypass - Direct Server Access](/P4/p4-14.md)
15. [Content Spoofing - Impersonation via Broken Link Hijacking](/P4/p4-15.md)
16. [Content Spoofing - External Authentication Injection](/P4/p4-16.md) 
17. [Content Spoofing - Email HTML Injection](/P4/p4-17.md)
18. [Server-Side Template Injection (SSTI) - Basic](/P4/p4-18.md)
19. [Cleartext Transmission of Session Token](/P4/p4-19.md)
20. [Weak Login Function - Other Plaintext Protocol with no Secure Alternative ](/P4/p4-20.md)
21. [Weak Login Function - Over HTTP](/P4/p4-21.md)
22. [Failure to Invalidate Session On - Logout (Client and Server-Side)](/P4/p4-22.md)
23. [Failure to Invalidate Session On - Password Reset and/or Change](/P4/p4-23.md)
24. [Weak Registration Implementation Over HTTP](/P4/p4-24.md)
25. [Disclosure of Secrets Pay-Per-Use Abuse](/P4/p4-25.md)
26. [EXIF Geolocation Data Not Stripped From Uploaded Images - Manual User Enumeration](/P4/p4-26.md)
27. [Visible Detailed Error/Debug Page - Detailed Server Configuration](/P4/p4-27.md)
28. [XSS - Stored - Privileged User to No Privilege Elevation](/P4/p4-28.md)
29. [XSS - IE-Only - IE11](/P4/p4-29.md)
30. [XSS - Referer](/P4/p4-30.md)
31. [XSS - Universal (UXSS)](/P4/p4-31.md)
32. [XSS - Off-Domain - Data Uri](/P4/p4-32.md)
33. [Server-Side Request Forgery (SSRF) External](/P4/p4-33.md)
34. [Username/Email Enumeration - Non-Brute Force](/P4/p4-34.md)
35. [Open Redirect - GET-Based](/P4/p4-35.md)
36. [No Password Policy](/P4/p4-36.md)
37. [Weak Password Reset Implementation - Token is Not Invalidated After Use](/P4/p4-37.md)
38. [Weak 2FA Implementation - 2FA Secret Cannot be Rotated](/P4/p4-38.md)
39. [Weak 2FA Implementation - 2FA Secret Remains Obtainable After 2FA is Enabled](/P4/p4-39.md)
40. [Sensitive Application Data Stored Unencrypted - On External Storage](/P4/p4-40.md)
41. [Executable Download - No Secure Integrity Check](/P4/p4-41.md)
42. [Unnecessary Data Collection WiFi SSID+Password](/P4/p4-42.md)



## [Buy Me A Coffee](https://www.buymeacoffee.com/faizee)
![GitHub Logo](https://www.bmtdesigner.com/wp-content/uploads/2020/09/Buy-Me-a-Coffee-01.jpg) 

## [Twitter](https://twitter.com/faizee_asad)
 
## Contributors

<table>
	<tr>
		<td align="center"><a href="https://github.com/Faizee-Asad"><img src="https://avatars.githubusercontent.com/u/72010857?v=4?s=100" width="100px" height="100px" alt=""/><br><sub><b>Faizee Asad</b></sub></a><br><a href="#tutorial-Faizee-Asad" title="Tutorials">✅</a></td>
		<td align="center"><a href="https://github.com/Moeed9112"><img src="https://selftaught.blog/wp-content/uploads/2020/04/computer-2982270_1920.jpg" width="100px" height="100px" alt=""/><br><sub><b>Faizi Moeed</b></sub></a><br><a href="#tutorial-Moeed9112" title="Tutorials">✅</a></td>
	</tr>
</table>
