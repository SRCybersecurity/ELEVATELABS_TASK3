# ELEVATELABS_TASK3
Vulnerability scan report with identified issues. 
<br></br>
Task 3: Perform a Basic Vulnerability Scan .
<br></br>

Objective: Identify common vulnerabilities on your computer. <br></br>
Tools: OpenVAS Community Edition or Nessus, Targeted host (BeeBox).<br></br>
Key Concepts: Vulnerability scanning, risk assessment, CVSS, remediation, security tools.<br></br>

Deliverables: Vulnerability scan report with identified issues.<br></br>


1.Installation and setting up of Nessus.          <br></br>
                      
2.Set up scan target as your local machine IP or localhost.<br></br>
      
3.Full vulnerability scan results are uploaded along with PDF file. <br></br>

4.Wait for scan to complete (may take 30-60 mins).
 </br>- It takes about 40-60 mins or more. <br></br>


5. Vulnerabilities and severity Report.
</br>- Targeted Host BEEBOX (10.10.10.133) Scan results. <br></br>

6.Simple fixes or mitigations for found vulnerabilities.<br></br>
***CRITICAL Severity***
</br>Summary of the Vulnerability:
</br>•	Vulnerability: SQL Injection in phpMyAdmin prior to version 4.8.6
</br>•	CVE ID: CVE-2019-12922
</br>•	Patch Info: Fixed in phpMyAdmin 4.8.6
</br>•	Public Exploits: Yes, proof-of-concept (PoC) and exploit scripts are publicly available.
</br> Mitigation:
</br>Upgrade phpMyAdmin
</br>This is the most direct and strongly recommended fix.
</br>•	Current Version: Prior to 4.8.6
</br>•	Secure Version: 4.8.6 or later
</br>***HIGH Severity***
</br>Drupal Database Abstraction API SQLi
</br>Risk: SQL injection through unsafe queries.
</br>CVE: CVE-2014-3704
</br>Affected: Drupal 7.x before 7.32
</br>Mitigation:
</br>•	Update Drupal immediately to latest 7.x or 9.x/10.x if still on 7.
<br></br>
***MEDIUM Severity***
</br>2. Apache ETag Header Information Disclosure
</br>Risk: ETag reveals inode info, which may assist in host fingerprinting.
</br>Mitigation (Apache):
</br>In httpd.conf or .htaccess:
<br></br>
***LOW severity***
</br>HTTP TRACE / TRACK Methods Allowed
</br>Risk: Cross-site tracing (XST) vulnerability.
</br>Mitigation:
</br>Disable TRACE method (Apache):
</br>TraceEnable Off
<br></br><br></br>

***END***

