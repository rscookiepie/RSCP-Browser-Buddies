# Security

## Current status

No V4 source or supported release has been verified in this repository.
Security, permissions, storage, external requests, cleanup, and browser
compatibility remain unassessed until the complete script is available.

## Reporting a vulnerability

If GitHub private vulnerability reporting is enabled, use the repository's
[Security page](https://github.com/rscookiepie/RSCP-Browser-Buddies/security)
to submit a private report. Availability has not been verified.

If no private reporting option is available, open a minimal issue requesting a
private contact method from RSCookiePie. Do not include exploit details,
credentials, personal information, or private webpage content in that issue.
No dedicated security email address or response timeline is published here.

A private report should describe the affected revision, impact, reproduction
steps on a safe test page, and relevant sanitised evidence.

## Browser-script review expectations

- Review complete code before executing it on a webpage.
- Avoid unnecessary external requests and unexpected data collection.
- Avoid insecure code injection or remote evaluation of unknown code.
- Document any permissions, persistent storage, retention, and deletion steps.
- Check event listener cleanup, timers, injected elements, and duplicate runs.
- Preserve browser security protections and avoid testing on sensitive pages.

These are review expectations, not claims that the missing V4 source already
meets them. See [USAGE.md](docs/USAGE.md) for current limitations.
