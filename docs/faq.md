# FAQ & Troubleshooting

## DNS verification is still pending. What should I do?

1. Double-check that the SPF, DKIM, and Return-Path records supplied in **Email Accounts** exactly match what you added at your DNS host (no extra spaces or quotes).
2. Ensure the DNS entries are published on the root domain or the hostname specified (e.g., `pm._domainkey.mail.example.com`).
3. TTL can delay confirmation by up to an hour. Use a DNS lookup tool to confirm propagation.
4. If the record looks correct but TradeBacklinks still shows "Pending," hit **Recheck DNS**. The app re-queries Postmark immediately.

## RapidAPI quota errors appear in the dashboard.

- Open **Settings → Integrations** and confirm the RapidAPI key is still active.
- Reduce Autopilot pace temporarily so discovery jobs stay within the monthly quota.
- Consider upgrading the RapidAPI plan for the connectors you rely on most (SimilarWeb, SEO Traffic & Authority, DataForSEO).

## A partner says they never received our outreach email.

- Make sure the sending domain shows "Verified" in **Email Accounts** and that the inbox has not hit its daily send cap.
- Check the **Inbox summary** to see if a bounce was recorded. If so, update the contact’s email and requeue the opportunity.
- Confirm the unsubscribe flag is not set for that contact.

## Links we won disappeared from the partner site.

- Go to **Domain Monitoring → Lost links** to see the crawl status.
- Use the "Request reactivation" quick action, which sends a polite reminder referencing the original compensation agreement.
- If the partner declines, log a deduction in **Compensation Plan → Adjustments** so credits stay accurate.

## How do I pause Autopilot without losing my queue?

- Toggle the Autopilot switch off from the dashboard header. Queued domains remain in place and will resume when you turn it back on.
- Alternatively, pause individual domains via the Opportunity menu if you only need to stop outreach for certain niches.

Need more help? Email support@tradebacklinks.com or chat inside the app.
