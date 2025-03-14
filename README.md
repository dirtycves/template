# CVE Research Submission Template

## Overview
Provide a brief description of the vulnerability, including the affected package(s) and a summary of the issue.

## Affected Packages
List all affected packages and their dependencies.

```
- Package: <package-name>
- Dependencies:
  - <dependency-1>
  - <dependency-2>
```

## Package Versions
Specify the versions affected by this vulnerability.

```
- Affected Versions:
  - <version-1>
  - <version-2>
  - <version-3>
```

## Summary
Provide a concise summary of the vulnerability, its nature, and how it affects the system.

## Probability
Describe the likelihood of exploitation (e.g., High, Medium, Low) and any known instances of exploitation.

## Severity
Indicate the severity level (e.g., Critical, High, Medium, Low) based on its impact.

## Impact
Explain the consequences of this vulnerability, including potential data breaches, system compromise, or privilege escalation.

## Technical Details
Provide in-depth technical details, including how the vulnerability works, affected code snippets, and proof-of-concept (if available).

```python
# Example vulnerable code snippet
import os

def insecure_function(user_input):
    os.system("echo " + user_input)  # Command Injection
```

## Suggested Fix
If available, provide a patch, workaround, or recommended fix.

```python
# Secure version
import subprocess

def secure_function(user_input):
    subprocess.run(["echo", user_input], check=True)
```

## References
List external references, advisories, or related CVE IDs.

```
- [CVE-ID](https://cve.mitre.org/)
- [Exploit-DB Reference](https://www.exploit-db.com/)
```

## Research Details
Provide additional details about how this research was conducted, testing methods, and any tools used.

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

