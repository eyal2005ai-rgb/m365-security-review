# M365 Security Review

Free, read-only monthly Microsoft 365 security review that produces a CISO-style PDF report for each tenant you manage. By ECIT IT Services.

## Download

| Platform | Download | Requirements |
|---|---|---|
| macOS | [M365-Security-Review-Mac.zip](https://github.com/eyal2005ai-rgb/m365-security-review/releases/latest/download/M365-Security-Review-Mac.zip) | macOS 11 or later, Python 3.9+ |
| Windows | [M365-Security-Review-Windows.zip](https://github.com/eyal2005ai-rgb/m365-security-review/releases/latest/download/M365-Security-Review-Windows.zip) | Windows 10/11 64-bit, nothing else needed |

All versions and release notes: see Releases. SHA-256 checksums are attached to each release (SHA256SUMS.txt).

## What it does

Reads tenant security settings through Microsoft Graph with read-only permissions only, and never changes anything in a tenant. Checks identity and MFA, Conditional Access, Secure Score and alerts, email authentication (SPF, DKIM, DMARC), SharePoint and OneDrive sharing, and device compliance. Everything runs on your own computer; no data is sent to us.

## First launch

The installers are not code-signed. On macOS open System Settings, Privacy and Security, and click Open Anyway. On Windows click More info, then Run anyway.

## License

Free to use under the End User License Agreement shown during installation. Not affiliated with Microsoft. Questions: info@ecit.co.il
