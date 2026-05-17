# About
Collection of codes to verify servers, applications and infrastructure immunity against specific CVEs.

# How
Use instruction in each CVE directory to check whether your servers or apps are vulnerable.

These codes are helpful when you have many servers and do not want to check on each one manually.

## 🛡️ Covered CVEs

Below is the current list of vulnerabilities supported by this verification suite:

| CVE ID | Impacted Component | Description & Check Summary |
| :--- | :--- | :--- |
| **CVE-2025-26465** | OpenSSH | It could enable adversaries to launch machine-in-the-middle/man-in-the-middle (MitM) or denial-of-service (DoS) attacks. |
| **CVE-2025-26466** | OpenSSH | It could enable adversaries to launch machine-in-the-middle/man-in-the-middle (MitM) or denial-of-service (DoS) attacks. |
| **CVE-2026-42945** | NGINX | A vulnerability in the ngx_http_rewrite_module module. |

# Contribution
Contributions are highly welcomed! Whether you are fixing a bug, improving documentation, or adding automated checks for a new CVE, your help makes infrastructure safer for everyone.

How to Contribute
1. Fork the repository.

2. Create a branch for your feature or CVE check (git checkout -b cve-202X-XXXX-verification).

3. Implement your script following the project standard (return exit code 0 if safe, non-zero if vulnerable).

4. Update the table in this README.md with your CVE details and a brief summary.

5. Open a Pull Request explaining your testing methodology.
