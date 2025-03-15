# CVE Research Submission Template

## Overview
Provide a brief description of the vulnerability, including the affected package(s) and a summary of the issue.

## Required Details for Submission
Analysts must provide the following details when submitting CVE research data:

### Title
- **Vulnerability Title:** Provide a concise and descriptive title of the issue.

### Tags
- **Type:** Security, Bug, etc.
- **Priority:** Critical, High, Medium, Low
- **Score:** CVSS score (if available)
- **Status:** Patched, Unpatched, In Progress

### Affected Packages
List all affected packages and their dependencies.

```
- Package: <package-name>
- Affected Versions: <version-range>
- Patched Version: <version>
- Dependencies:
  - <dependency-1>
  - <dependency-2>
```

### Summary
Provide a concise summary of the vulnerability, its nature, and how it affects the system.

### Probability
```
"Prob": {
  "Likelihood": "<High/Medium/Low>",
  "Exploitation Ease": "<Easy/Moderate/Difficult>",
  "Attack Vector": "<Network/Local/Physical>",
  "User Interaction": "<Required/Not Required>"
}
```

### Severity
Indicate the severity level (e.g., Critical, High, Medium, Low) based on its impact.

### Impact
Explain the consequences of this vulnerability, including potential data breaches, system compromise, or privilege escalation.

### Technical Details
Provide in-depth technical details, including how the vulnerability works, affected code snippets, and proof-of-concept (if available).

```python
# Example vulnerable code snippet
import os

def insecure_function(user_input):
    os.system("echo " + user_input)  # Command Injection
```

### Suggested Fix
If available, provide a patch, workaround, or recommended fix.

```python
# Secure version
import subprocess

def secure_function(user_input):
    subprocess.run(["echo", user_input], check=True)
```

### References
List external references, advisories, or related CVE IDs.

```
- [CVE-ID](https://cve.mitre.org/)
- [Exploit-DB Reference](https://www.exploit-db.com/)
- [GitHub Advisory](https://github.com/advisories/)
```

### CVSS Metrics
#### Exploitability Metrics
```
- Attack Vector: <Network/Local>
- Attack Complexity: <Low/Medium/High>
- Privileges Required: <None/User/Admin>
- User Interaction: <Required/Not Required>
```
#### Vulnerable System Impact Metrics
```
- Confidentiality Impact: <High/Medium/Low>
- Integrity Impact: <High/Medium/Low>
- Availability Impact: <High/Medium/Low>
```
#### CVSS Vector
```
CVSS: <CVSS-Vector-String>
```

### EPSS Score
- **EPSS Score:** (If available, include estimated probability of exploitation)

### Weakness
```
- CWE ID: <CWE-XXX>
- Description: <Weakness Description>
```

### CVE Details
```
- CVE ID: <CVE-ID>
- Status: <Assigned/Unassigned>
```

### Analysis
```
- Analyst Name: <Your Name>
- Research Team: <Team Name>
```

### Source Code
```
- Repository: <Repository Name>
- URL: <Repository URL>
```

---

### Submission Guidelines
- Ensure all information is accurate and well-documented.
- Attach necessary proof-of-concept scripts or logs if applicable.
- Submit through the appropriate disclosure channels.

---

**Author:** [Your Name]  
**Date:** [YYYY-MM-DD]  
**Contact:** [Your Email or Social Handle]

---

## Email us at 
dirtycves@gmail.com
## For example check 
https://www.dirtycves.com/search/GHSA-h42x-xx2q-6v6g


