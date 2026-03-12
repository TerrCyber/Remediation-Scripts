# Remediation-Scripts

## Purpose

The goal of this repository is to:

- Automate remediation of Windows STIG findings
- Demonstrate vulnerability remediation workflows
- Provide reusable scripts for compliance enforcement
- Document remediation validation using vulnerability scanning tools

---

## Tools Used

- PowerShell
- Tenable / Nessus
- Windows Registry
- DISA STIG Guidelines

---

## Example Workflow

1. Vulnerability scan identifies STIG finding
2. Remediation script created
3. Configuration applied via PowerShell
4. System rescanned
5. Compliance verified

---

## Implemented STIGs

| STIG ID | Description |
|-------|-------------|
| WN11-AU-000500 | Application event log size must be configured to 32768 KB or greater |
| WN11-EP-000310 | This PowerShell script enables Kernel DMA Protection by setting the Device Enumeration Policy to Block All (0) in the Windows registry|
| WN11-SO-000167 | This PowerShell script restricts remote calls to SAM to Administrators only by configuring the RestrictRemoteSAM registry value.|
| WN11-UR-000010 | This PowerShell script ensures that only Administrators and Remote Desktop Users are granted the "Access this computer from the network" user right.|
| WN11-SO-000025 | This PowerShell script renames the built-in Guest account to a non-default nameto satisfy the requirement that the Guest account must not be named "Guest".|

More STIG remediations will be added as they are completed.

---

## Author

Terrance Fortson  

