# Cybersecurity Vulnerability Assessment Project

# Internship Task 3 – Elevate Labs Cybersecurity Internship
# 📋 Project Overview

This repository contains the implementation and documentation of a comprehensive vulnerability assessment project using Tenable Nessus Essentials. The project demonstrates practical cybersecurity skills, including vulnerability scanning, security analysis, and remediation planning on multiple target systems.

The assessment covered three hosts (10.0.2.2, 10.0.2.3, and 10.0.2.17), identifying vulnerabilities across network services, SSL/TLS configurations, outdated software, and misconfigurations.

# 🎯 Objectives

    Perform vulnerability scans on multiple target systems.

    Identify and categorize security vulnerabilities.

    Analyze risk based on severity and impact.

    Provide actionable remediation strategies.

    Document findings professionally.

# 🛠️ Tools Used

    Tenable Nessus Essentials – Primary vulnerability scanner.

    Kali Linux – Target system for testing and scanning.

    VirtualBox – Lab environment setup for isolated testing.

# 🔍 Methodology
Phase 1 – Environment Setup

    Installed and configured Nessus Essentials.

    Selected target IPs: 10.0.2.2, 10.0.2.3, 10.0.2.17.

    Verified connectivity to targets.

Phase 2 – Vulnerability Scanning

    Performed comprehensive scans on each host.

    Used default and custom scan policies for deeper inspection.

    Collected scan reports for analysis.

Phase 3 – Analysis & Documentation

    Reviewed vulnerabilities by severity: Critical, High, Medium, Low, and Informational.

    Linked vulnerabilities to CVE references and Nessus plugin documentation.

    Developed remediation recommendations.


 # 📊 Key Findings
Host 10.0.2.2

    Medium: SMB Signing Not Required (Potential MITM risk).

    Low: DHCP Server Detection.

    Info: Multiple SMB and OS information disclosures.

Host 10.0.2.3

    Medium: DNS Server Cache Snooping (Information Disclosure).

    Info: DNS version disclosure, OS fingerprinting.

Host 10.0.2.17

    Critical: Multiple Node.js vulnerabilities (versions < latest security releases).

    High: Outdated Node.js with multiple CVEs.

    Medium: SSL Certificate Cannot Be Trusted, SQLite vulnerabilities.

    Info: Apache HTTP server detection, SSL/TLS configuration details, software inventory.

# 🛡️ Remediation Recommendations
Immediate Actions

    Enable SMB Signing on Windows systems.

    Restrict DNS cache snooping access.

    Update Node.js to the latest patched version.

    Replace or reconfigure SSL certificates to use a trusted CA chain.

Security Hardening

    Minimize exposed services and ports.

    Enforce strong firewall rules.

    Apply latest OS and application patches.

Long-Term Improvements

    Schedule regular vulnerability scans.

    Implement security monitoring and incident response plans.

    Train staff in security awareness.

# 📈 Scan Statistics

| Target IP | Total Vulnerabilities | Critical | High | Medium | Low | Info |
|-----------|----------------------|----------|------|--------|-----|------|
| 10.0.2.2  | 23                   | 0        | 0    | 1      | 1   | 21   |
| 10.0.2.3  | 11                   | 0        | 0    | 1      | 0   | 10   |
| 10.0.2.17 | 78                   | 2        | 3    | 4      | 0   | 69   |


# 📚 Learning Outcomes

    Practical experience with Nessus Essentials.

    Risk analysis and prioritization of vulnerabilities.

    Hands-on remediation strategy planning.

    Understanding of network and application-level vulnerabilities.

# 🚀 Future Enhancements

    Integration with automated patch management tools.

    Advanced penetration testing on high-risk services.

    Continuous vulnerability monitoring.
