# Email Accounts

![Email Accounts screenshot](static/images/dashboard/06-email-accounts.png)

Connect branded domains so Autopilot can send outreach on your behalf.

## Summary cards
- **Sent emails**, **# of replies**, and **Spam complaints** cover the last 30 days.

## Servers section
- Shows each sending domain plus its status (e.g., Pending DNS, Verified).
- Use "Add an email below to configure further" to assign inboxes to that domain.
- Remove a server if you want to rotate it out of Autopilot.

## Emails section
- Lists individual inboxes tied to each server. Columns include from name, related server, and whether it’s the primary sender.
- Click **Add Email** to add a new mailbox. Make sure the inbox exists with your email provider first.

## DNS Verification checklist
1. Add SPF, DKIM, and Return-Path records as instructed.
2. Wait for propagation, then click **Recheck DNS**.
3. Once verified, the status changes to “Ready” and Autopilot can use it.

Keep deliverability healthy by spreading outreach volume across multiple inboxes and monitoring spam complaints weekly.
