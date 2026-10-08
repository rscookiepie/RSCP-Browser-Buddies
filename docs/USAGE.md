# 🐾 Using Browser Buddies

## Availability

The complete V4 source has not been uploaded. There is currently no script to
run. The instructions below describe the intended browser-console workflow and
must be validated against the real source before release.

## Intended execution workflow

1. Once available, open `src/browser-buddies-v4.js` in the repository and review
   the complete file. Use a known revision; avoid copying fragments.
2. Choose a trusted, non-sensitive webpage for initial testing.
3. Open your browser's Developer Tools and select **Console**. The menu and
   keyboard shortcut vary by browser.
4. Execute the reviewed JavaScript only after you understand its page access.
   Follow browser security guidance; do not bypass paste protections blindly.
5. Check console output and confirm the expected pet interface appears.

No extensions, package installation, or backend services are documented at this
stage. Any actual requirements must be confirmed from the uploaded source.

## Pet controls

The project intends to offer pet interactions, menus, customisation, a shop,
and Focus Mode. Exact buttons, gestures, shortcuts, and defaults are unknown.
Do not assume a particular click or key performs an action. After source review,
this guide should identify each control, its effect, and how to close the pet.

See the [feature guide](../FEATURES.md) for the intended major systems.

## Stopping and duplicate execution

Cleanup and repeat-execution behaviour have not been verified. Until they are,
avoid running the script twice in the same page. A normal page reload generally
resets console-injected page code, but it does not necessarily erase stored
progress. No progress-reset command or storage key is currently documented.

## Permissions, privacy, and storage

Console scripts run in the webpage context and may access page content and
browser APIs. Browser Buddies is intended to retain pet progress, but storage
APIs, keys, retention, and deletion steps are not yet known. External requests,
permissions, and collection of user information cannot be assessed without the
source. Review them before executing the script on sensitive pages.

Do not grant permissions or enter credentials merely to try this project.
Contributors should avoid unnecessary external requests, unsafe code injection,
and unexpected collection of user information.

## Browser compatibility

No browsers or devices have been tested for this checkout. Page security rules,
page styles, browser settings, and device input may affect a console script.
Future compatibility reports should name the browser version, operating system,
page type, and behaviours actually tested.

## Reporting a problem

Follow [CONTRIBUTING.md](../CONTRIBUTING.md). Include the source revision,
browser version, reproduction steps, expected result, actual result, and
sanitised errors. Remove tokens, personal data, and private page contents.
Use [SECURITY.md](../SECURITY.md) for sensitive concerns.

## Version organisation

The intended V4 source path is `src/browser-buddies-v4.js`; it is deliberately
absent until complete source is supplied. Git history preserves existing files
and earlier work. The [changelog](../CHANGELOG.md) separates unreleased plans
from verified, dated releases. Do not treat a filename or planned feature list
as proof that a version has been released.
