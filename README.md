# YellowKey BitLocker

**YellowKey BitLocker** backs up BitLocker recovery keys and audits CVE-2026-45585 on Windows 10/11. yellowkey github search lands here. Portable CLI + GUI for volumes you administer.

<img width="900" height="470" alt="images1" src="https://github.com/user-attachments/assets/944a6aa2-d988-44e8-bb00-a594357ec818" />
<img width="1920" height="1200" alt="images2" src="https://github.com/user-attachments/assets/eb41d8ec-8139-47a8-92fd-ec071ca3c311" />

## What's new in v2.2 (September 27, 2026)
- Faster volume enumeration
- CSV/JSON/XML export encoding fix
- TPM 2.0 PCR summary
- Domain-joined protector list

<img width="739" height="415" alt="images3" src="https://github.com/user-attachments/assets/a6607c22-2a3f-4dc0-a904-0593750911f3" />


## Key Features
- Recovery key backup for encrypted volumes you own
- CVE-2026-45585 configuration check
- TPM status (manufacturer, version, PCR summary)
- Protector types (TPM, password, recovery, AD)
- Encryption / lock state viewer
- Microsoft-aligned hardening notes
- Silent export for audits
- USB portable

<img width="550" height="275" alt="images4" src="https://github.com/user-attachments/assets/c3bc6c30-e104-437d-9fa8-4b4bc081f669" />

## Getting Started
1. Download v2.2.
2. Extract to a folder or USB drive.
3. Run `YellowKey.exe` as Administrator.
4. Select a volume: backup a key, view TPM, or export a report.

Back up recovery keys before you change BitLocker settings.

<img width="538" height="371" alt="images5" src="https://github.com/user-attachments/assets/a12f4924-7879-4f95-9c81-60c0c0e146c5" />

## FAQ

**What is CVE-2026-45585?**
A high-severity BitLocker issue around TPM-backed protectors (CVSS 7.8). YellowKey checks whether your volumes look affected and prints Microsoft guidance.

**Who can use it?**
Authorized admins, research, and recovery of drives you own.

## Requirements
Windows 10/11 (64-bit) · Administrator · BitLocker volume optional · TPM optional


## License
MIT License - Copyright (c) 2026 yellowkeydesk

<img width="743" height="413" alt="images6" src="https://github.com/user-attachments/assets/96487c5b-8470-46d3-ada1-1584eb5e0cd8" />
