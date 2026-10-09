# Changelog

## 1.2.5

- Added a task inbox for running conversations, completed unread work, and supported input or permission requests.
- Prioritized action-required alerts and added automatic panel opening for relevant new events.
- Opening an action request clears that reminder, including across restarts.
- Fixed stale async question reminders after a task ends.
- Added a dark frosted task panel and fixed clipped headers and excess blank space during resizing.
- Improved quota-service startup compatibility, bounded retries, wake refresh, and explicit sync failure states.
- Kept quota details and existing operations accessible from the settings button.

## 1.1.14

- Fixed login startup by launching the menu-bar executable directly instead of relying on a background LaunchServices open request.

## 1.1.13

- Added reset activity announcements with source access.
- Added reset-card arrival notifications.
- Improved local quota refresh accuracy.
- Added automatic adaptation when the five-hour quota window is present or absent.
- Refined weekly quota, reset countdown, date, and reset-card menu-bar pages.
- Added quota and reset countdown color alerts.
- Improved guided installation for macOS 13+, Apple silicon, and Intel Macs.
