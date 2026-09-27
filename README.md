### Incident Handler's Journal

#### Overview

#### Case 1 – Ransomware Incident

**Date:** May 6, 2024
**Activity:** Incident Handler's Journal
**Tools:** None

**Scenario**

A small U.S. healthcare clinic experienced a ransomware incident after targeted phishing emails were sent to several employees. A malicious attachment installed malware, allowing the attackers to gain access to the company's network and deploy ransomware. Critical files, including patient data, were encrypted, causing major disruption to business operations. The attackers demanded a large ransom in exchange for the decryption key.

**Incident Analysis**

I documented the incident using the 5 W's framework:

* **Who:** An organized group of attackers
* **What:** A ransomware security incident
* **When:** Tuesday at approximately 9:00 a.m.
* **Where:** A healthcare organization
* **Why:** The attackers gained access through targeted phishing emails containing a malicious attachment. The incident also suggests that the affected employees may have lacked sufficient security awareness to identify and respond appropriately to the phishing attempt.

**Security Considerations**

The exercise also considered two questions:

* **How could the healthcare company reduce the risk of a similar incident occurring again?**
  Security awareness training could help employees recognize targeted phishing emails and avoid opening malicious attachments. Critical data should also be backed up and available for recovery in the event of a ransomware attack.

* **Should the company pay the ransom to regain access to the encrypted files?**
  The exercise considered the circumstances surrounding the ransom demand and whether paying the ransom would be appropriate.

The exercise highlighted the relationship between phishing, initial access, malware deployment, ransomware and business disruption, while also considering preventive security measures, backup and recovery, and incident-response decisions.


**What I learned**

This exercise introduced a structured approach to documenting a cybersecurity incident and analyzing an attack from initial access through operational impact. It also reinforced the importance of considering both technical controls and organizational security practices when responding to security incidents.


#### Case 2 – Malicious Attachment and File Analysis

### Entry 2 – Malicious File Investigation

**Date:** May 9, 2024
**Activity:** Incident Handler's Journal
**Tools:** VirusTotal

**Scenario**

A financial services company detected suspicious activity on an employee's workstation. The employee had received an email containing a password-protected spreadsheet attachment. The password was provided in the email, and after the employee opened the spreadsheet, a malicious payload was executed on the computer.

The incident was detected after multiple unauthorized executable files were created on the workstation.

**Incident Analysis**

I documented the incident using the 5 W's framework:

* **Who:** An employee at a financial services company
* **What:** A malicious file was delivered through an email attachment and executed on the employee's workstation.
* **When:** The employee downloaded and opened the file at approximately 1:13 p.m.; multiple unauthorized executable files were created around 1:15 p.m.
* **Where:** The employee's workstation
* **Why:** The incident was initiated through a malicious email attachment. The successful execution of the payload also indicated a need for stronger awareness and procedures for handling suspicious files and attachments.

**File and IoC Investigation**

I retrieved the malicious file and generated a SHA-256 hash to use as a unique identifier for the file. I then used VirusTotal to investigate the hash and gather additional threat intelligence.

The investigation included reviewing the file's detection results and related information to determine whether the file was malicious and identify associated indicators of compromise (IoCs). The activity used the Pyramid of Pain framework to categorize IoCs such as hashes, IP addresses, domains, network or host artifacts, tools, and attacker tactics, techniques, and procedures (TTPs).

**Security Considerations**

The incident highlighted several areas that could reduce the risk of similar attacks:

* Employees should receive security awareness training covering suspicious emails, password-protected attachments, and malicious files.
* Procedures should be in place for reporting and handling suspicious attachments.
* Suspicious files should be isolated and investigated before being allowed to execute.
* File hashes and other IoCs can be used to support detection and investigation of related malicious activity.
* Threat-intelligence sources such as VirusTotal can provide additional context when investigating suspicious files.

**What I Learned**

This exercise provided hands-on experience with a basic malware investigation workflow: identifying a suspicious file, generating a SHA-256 hash, investigating the hash in VirusTotal, and identifying related indicators of compromise.

It also demonstrated how individual artifacts can be connected to broader threat intelligence and how IoCs can support the investigation and detection of security incidents.


#### Case 3 – Web Application Vulnerability and Data Exposure

**Scenario**
...

**Investigation**
...

**Findings**
- Forced browsing
- Unauthorized access to customer data
- Approximately 50,000 records affected

**Security considerations**
...

#### Case 4 – Phishing and Malicious Domain Investigation

**Scenario**
...

**Investigation**
- Google Chronicle
- Domain investigation
- Affected assets

**Findings**
...

**Security considerations**
...

#### What I learned

...
