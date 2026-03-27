# Security Policy

## Supported Versions

Only the latest published version of the Chrome extension receives security updates. Prior versions are not supported.

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |
| < Latest | :x:               |

## Scope

This policy covers the full stack required to run the Feedback Plugin Chrome extension:

- **Chrome extension** (content scripts, service worker, sidebar, popup, options page)
- **Firebase backend** (Firestore, Authentication, Security Rules)
- **Cloud Functions** (notification delivery, integrations)

### Out of Scope

- Third-party dependencies (see below)
- Websites that the extension is used on
- Browser vulnerabilities
- Attacks requiring physical access to a user's device

### Third-Party Dependencies

Third-party dependencies are not directly maintained by this project. However, when a critical or high-severity vulnerability is disclosed in a dependency we use, we commit to updating to a patched version within **30 days**.

## Reporting a Vulnerability

**Please do not open public GitHub issues for security vulnerabilities.**

Instead, email **security@feedback-machine.com** with your report. This keeps the details confidential while we work on a fix.

### What to Include

- Description of the vulnerability
- Steps to reproduce
- Affected component (extension, backend, Cloud Functions)
- Potential impact
- Suggested fix (if you have one)

### What to Expect

- **Acknowledgement** within **72 hours** of your report
- **Status updates** at least every 7 days while the issue is being investigated
- **Resolution target** of **14 days** for critical vulnerabilities, longer for lower severity issues
- Credit in the fix commit and release notes (unless you prefer to remain anonymous)

### If Your Report Is Accepted

We will work on a fix, coordinate disclosure timing with you, and release a patched version. You will be notified when the fix is live.

### If Your Report Is Declined

We will explain why we don't consider it a vulnerability and close the report. You are welcome to follow up with additional context if you disagree.
