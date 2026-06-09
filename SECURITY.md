# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| 1.0.x   | ✅ Yes     |

## Integrity Verification (Hashes)

To ensure that the Key2Pad installer has not been tampered with, we publish the **SHA-256 Hash** of each `.exe` file in the release notes.

You can verify the legitimacy of the file by opening a terminal (PowerShell) in the folder where you downloaded the installer and running:

```powershell
Get-FileHash .\Key2Pad-Setup.exe
```

Compare the result with the hash provided on the [Releases](https://github.com/alaancuevas/key2pad-releases/releases) page. If it does not match, **DO NOT run the file** and report it immediately to our contact email.

## Reporting a Vulnerability

If you find a security issue in Key2Pad, please **DO NOT** open a public issue.

Contact directly at: **key2pad.contact@gmail.com**

Include:
- Description of the vulnerability.
- Steps to reproduce it.
- Potential impact on the system architecture.

You will receive a response within 72 hours.

## Notes on ViGEmBus

Key2Pad uses the Open-Source virtual driver **ViGEmBus** by Nefarius Software Solutions.  

Currently, ViGEmBus is in an *End-of-Life* (EOL) state, meaning its creator no longer provides active updates. However, it remains the most stable and functional driver on Windows 10/11.
Security issues at the kernel or driver level related to ViGEmBus are beyond our direct control, but we actively monitor any community patches, mitigations, or secure forks available at:  
https://github.com/nefarius/ViGEmBus
