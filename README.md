# Codex Quota Bar

Keep Codex quota, reset timing, and reset activity visible in the macOS menu bar.

> Ever saved a large refactor for tomorrow, only to wake up and find that the previous quota window had already reset? Codex Quota Bar helps you notice the timing earlier, so you can plan demanding work while the remaining quota is still useful.

[Download for macOS](dist/CodexQuotaBar-1.2.6-universal.dmg?raw=1) · [ZIP archive](dist/CodexQuotaBar-1.2.6-universal.zip?raw=1) · [Support the project](SUPPORT.md)

## Highlights

- **Update reminders** — checks for new versions at startup and hourly. A menu-bar arrow and panel button let you download a verified installer; installation still requires your confirmation.
- **Task inbox** — find running conversations, completed unread work, and supported requests that need your input or approval, with action requests first.
- **Timely task alerts** — new completions and action requests can open the panel automatically. Opening an action request clears its reminder, without answering or approving it for you.
- **Readable task panel** — a dark frosted panel with clear status colors, wrapping titles, and a scrollable task list.
- **Reset activity alerts** — surfaces relevant public official announcements and provides a link to the original source when available.
- **Reset-card arrival notices** — lets you know when a reset or locally visible reset-card change is detected.
- **Always-visible quota** — shows weekly quota, reset countdown, reset date, and reset-card count in the menu bar.
- **Adaptive time windows** — automatically adjusts the menu-bar layout when a five-hour quota window is present or absent.
- **Useful color alerts** — highlights lower remaining quota and marks only the reset countdown when less than one day remains.
- **Automatic refresh** — updates local quota information in the background without repeatedly opening a usage page.
- **Resilient syncing** — retries temporary query failures and refreshes after wake. Last-known values are explicitly marked as non-live when syncing fails.
- **Guided installation** — includes a visual first-run guide and supports both Apple silicon and Intel Macs.

## See It in Action

Reset announcements, source links, and reset-card arrival:

![Reset activity monitoring](assets/01-reset-alert.png)

Live quota, countdown, reset date, and color alerts:

![Live quota in the menu bar](assets/02-live-quota.png)

Automatic adaptation to the current quota-window rules:

![Adaptive five-hour quota display](assets/03-adaptive-window.png)

Guided installation and menu-bar access:

![Guided installation](assets/04-installation.png)

## Install

1. Download [CodexQuotaBar 1.2.6 for macOS](dist/CodexQuotaBar-1.2.6-universal.dmg?raw=1).
2. Open `CodexQuotaBar-1.2.6-universal.dmg`.
3. Open the DMG and double-click the installer.
4. Follow the on-screen first-run guide.

The app is locally signed but not notarized with an Apple Developer ID. If macOS blocks the first launch, Control-click the installer, choose **Open**, and confirm once.

Versions before 1.2.6 need this one manual installation to enable update checks. Updates verify archive checksums, bundle identity, version, and local code-signature integrity before opening the installer. This relies on HTTPS and the trusted repository, not Developer ID authentication. Failed installation attempts restore the previous app where possible; a recovery copy is retained after successful upgrades.

## Requirements

- macOS 13 or later
- Apple silicon or Intel Mac
- ChatGPT/Codex desktop app installed and signed in
- No API key required

## Privacy

Codex Quota Bar reads the quota state made available to the locally signed-in desktop account. It does not ask for an OpenAI API key. See [PRIVACY.md](PRIVACY.md) for the concise privacy statement.

## Important Notice

Codex Quota Bar is an independent third-party utility. It is not affiliated with, endorsed by, or supported by OpenAI or Apple. It does not add quota, bypass limits, or guarantee a reset.

Activity monitoring is informational. Announcements may change, be delayed, be cancelled, or apply only to selected accounts. Quota, reset-card delivery, reset timing, and eligibility are always determined by OpenAI's final operation and the actual state shown on your account.

The promotional images above contain Chinese interface examples. The menu-bar values shown are illustrative and may differ from your account.

Task-action detection covers supported structured input and permission requests, not every free-form request in a conversation. The promotional images predate the task inbox added in 1.2.x.

## Support Development

If this utility saves you time, please consider:

- Starring the repository
- Sharing it with another Codex user
- Supporting future maintenance through the sponsorship options in [SUPPORT.md](SUPPORT.md)

Your support helps fund compatibility work when quota rules, desktop behavior, or macOS change.

## Distribution

This repository distributes prebuilt releases and documentation. The core implementation is not published here. See [LICENSE.md](LICENSE.md).
