# Privacy

Codex Quota Bar is designed as a local macOS menu-bar utility.

- It does not require an OpenAI API key.
- Update checks contact the public GitHub repository at startup and hourly. Downloading an update contacts GitHub again, without uploading conversations, quota values, or account credentials.
- It reads quota information available to the locally signed-in ChatGPT/Codex desktop account.
- The task inbox reads local conversation titles, task and read states, and supported pending input or permission requests to show reminders. This information is not uploaded by the task inbox.
- Viewed action-reminder identifiers are stored locally so the same reminder does not reappear after restarting.
- It may retrieve public announcement information used for reset activity reminders.
- It does not sell personal information.
- It does not increase quota or bypass account restrictions.

Actual quota, reset timing, reset-card delivery, and activity eligibility are controlled by OpenAI and may differ between accounts.
