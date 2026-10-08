# Contributing

Thank you for helping improve RSCP Browser Buddies, created by RSCookiePie.

## Current scope

V4 source is awaiting upload and verification. Documentation improvements are
welcome. Do not reconstruct the missing script, add placeholder JavaScript,
or mark planned features as implemented.

## Reporting bugs

Use [GitHub Issues](https://github.com/rscookiepie/RSCP-Browser-Buddies/issues)
for ordinary bugs and feature suggestions. Search existing issues first.
Include:

- A short description and steps to reproduce.
- Expected and actual behaviour.
- Script version or commit, browser version, and operating system.
- Sanitised console errors and, if useful, a screenshot without private data.
- Whether the problem occurs after a fresh page load or repeated execution.

Do not post secrets, API keys, or private webpage content. Consult
[SECURITY.md](SECURITY.md) for sensitive vulnerabilities.

## Pull requests

1. Work on a focused branch using the existing checkout.
2. Preserve existing source, functionality, history, and copyright notices.
3. Explain the change and update related documentation.
4. Validate local Markdown links and file references.
5. When JavaScript is present, run `node --check src/browser-buddies-v4.js`
   and test its behaviour on a trusted test page. Syntax checks alone do not
   verify browser behaviour.
6. Report tested browsers, cleanup and duplicate-execution results, and any
   untested behaviour in the pull request.

No package manifest, automated test suite, or build workflow is currently
provided. Do not claim checks that could not be run.

## Source attribution

Keep existing copyright information. Include this notice in new project source
files when complete source is available:

```javascript
/*
 * RSCP Browser Buddies
 * Copyright (c) 2026 RSCookiePie
 * Licensed under the MIT License.
 * See LICENSE for details.
 */
```

The [MIT licence](LICENSE) requires preservation of copyright and licence
notices in copies or substantial portions of the software. It does not require
an on-screen watermark. Do not change the existing LICENSE file in this upgrade.
