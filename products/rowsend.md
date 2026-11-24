# Rowsend

Marketing emails from your database

- **Site:** [rowsend.com](https://rowsend.com/)
- **Topic:** [Marketing and sales](../topics/marketing-and-sales.md)
- **Ownership verified:** 2026-10-24

Rowsend is a desktop app for marketing email. It reads your users from your own database (Postgres, MySQL, MongoDB or Firebase) with a read-only login and sends through your own SES, Postmark, Mailgun or SMTP account. Credentials stay on your computer. Run the sending service on your own server with one Docker image: unsubscribe pages, hosted images, bounces and scheduled sends while your laptop is closed. You pay once, not per contact.

## Quick answers

Each answer comes with the sentence it is based on, quoted from the product's own pages.

### What is included in the Rowsend Cloud plan?

Rowsend Cloud includes up to 100,000 sends and 1 GB of hosted images each month.

> Each Cloud plan includes up to 100,000 sends and 1 GB of hosted images a month.

### Which email service providers are supported?

Rowsend supports Amazon SES, Postmark, Mailgun, or standard SMTP. No markup is added to your sending costs.

> Use SES, Postmark, Mailgun or SMTP. Rowsend adds no markup to your sends.

### Can I send emails from my own server using Docker?

Yes, you can run sends from your own computer, a custom server running Docker, or Rowsend Cloud.

> From your computer, your own server with Docker, or Rowsend Cloud.

### Is it worth it if my list is small?

Maybe not yet. Rowsend's own pricing page says that with fewer than 1,000 contacts, the free plans from Loops and Resend cost less.

> With fewer than 1,000 contacts, Loops and Resend have free plans that cost less.

### Do the unsubscribe links meet Gmail and Yahoo's rules?

Yes. Every email carries an unsubscribe link and the one-click header those two providers ask for. With topics, a person can leave one kind of email and keep getting the rest.

> Every email has an unsubscribe link and the one-click header Gmail and Yahoo ask for.

### Where are my email provider keys stored?

On your computer, encrypted. AI agents you connect never see them, and Rowsend Cloud only stores them if you turn on offline sending.

> Your computer encrypts your provider keys. Agents never see them. Cloud stores them only when you enable offline sending.

### Can Rowsend change data in my database?

No. It reads through a login that can't write. When you connect, it first checks the role and refuses a superuser, a role that owns tables or one with write grants.

> Rowsend first checks that the role can't write: it refuses a superuser, a role with pg\_write\_all\_data, a role that owns tables, or one with write grants.

### Does Rowsend track opens and clicks?

No. It adds no tracking pixels and doesn't rewrite your links. Each campaign reports deliveries, bounces, unsubscribes and complaints instead.

> Deliveries, bounces, unsubscribes and complaints for each campaign. No tracking pixels or rewritten links in your emails.

### Can I use one license on two Macs?

Not at the same time. A license is active on one computer, and you deactivate it in Settings when you want to move it to another.

> A license works on one computer at a time; deactivate it in Settings to move it to another.

### Can I try it before I buy?

Yes. Every feature is free for 7 days from the first time Rowsend runs on your computer. After that you need a license to send campaigns, but editing and test sends keep working.

> Every feature is free for 7 days from the first time Rowsend runs on a computer.

### How much does a Rowsend license cost?

It is a single payment. The first 300 licenses are $20, the next 500 are $29, and after that the price is $49 and goes no higher.

> The first 300 licenses are $20. After that the price steps up, and it never goes past $49.

### Does Rowsend run on Windows?

Not yet. It is a Mac app, and Windows is listed as coming soon.

> Windows coming soon

### Can an AI agent help me set up campaigns?

Yes. Agents such as Claude Code, Codex or Gemini can build segments and draft campaigns, and you review and press send yourself.

> Works with your agent. Claude Code, Codex, Gemini & more.

### Does the agent see my email provider keys?

No. Credentials never pass through the agent, and you can revoke its access at any time.

> Credentials never pass through the agent.

### What happens to addresses that bounce?

They are left out of every later send, and a campaign pauses itself if bounces or complaints climb.

> Addresses that bounce or mark you as spam are left out of every later send.

### Can I warm up a new sending domain?

Yes. Rowsend can start a new domain at 50 emails a day and grow toward the daily limit you set.

> warm up a new domain from 50 emails a day to build trust as it grows to that limit

### Does it work with MongoDB or Firebase?

Yes. Both are in the list of supported databases, along with Supabase, Neon, Postgres, MySQL, MariaDB and PlanetScale.

> Supabase, Postgres, MySQL, MongoDB or Firebase.

### Is there a version for Intel Macs?

Yes. The download page offers an Intel Mac build next to the main Mac download.

> Intel Mac

### What happens when the 7-day trial ends?

Sending campaigns then needs a license. Test sends, editing and everything else keep working.

> After that, sending campaigns needs a license. Test sends, editing and everything else keep working.

### Can I paste in my own HTML email?

Yes. You can build emails in the block editor, save templates, or paste your own HTML.

> Save templates, or paste your own HTML.

### Can people unsubscribe from one kind of email only?

Yes. Topics let someone leave one type of email, like a newsletter, and keep the rest.

> Topics let people leave one kind of email and keep the rest.

### Do I need a card to start the trial?

No. The 7-day trial starts without a card.

> No card needed

### Are future versions included in the license?

Yes. One payment covers every future version of the desktop app.

> One payment, every future version of the desktop app.

### What happens if I go over the Cloud fair use limit?

If you go over two months in a row, Cloud pauses new sends until the next month. You can write to the team if you need more.

> If you go over two months running, Cloud pauses new sends until the next month.

### Can I see how a campaign went?

Yes. Each campaign shows deliveries, bounces, unsubscribes and complaints.

> Deliveries, bounces, unsubscribes and complaints for each campaign.

### Can I stop a campaign that is already sending?

Yes. You can pause or cancel a send that is under way, and sends can go out in batches.

> pause or cancel a send that's under way

### Can I move from my Mac to Cloud or my own server later?

Yes. You can switch where sending runs at any time without losing an unsubscribe.

> Switch any time without losing an unsubscribe.

### Does Rowsend keep the database password I use for setup?

No. For Postgres and MySQL it uses that login once to list your tables and does not save the password.

> Rowsend uses this login once, to list your tables. It doesn’t save the password.

### How do I subscribe to Rowsend Cloud?

From Settings in the app. Every license includes 30 days of Cloud first.

> Subscribe from Settings in the app.

## What it does not do

- It doesn't run on Windows yet. The desktop app is for Mac.

  > Windows coming soon

- It doesn't report open or click rates. Campaign results cover deliveries, bounces, unsubscribes and complaints.

  > No tracking pixels or rewritten links in your emails.

- It doesn't send scheduled campaigns while your Mac is off unless you turn on offline sending in Rowsend Cloud.

  > Scheduled sends go out while your computer is off. Turn on offline sending in Rowsend Cloud.

- It doesn't include more than 100,000 sends a month on a Cloud plan. If you go over two months in a row, new Cloud sends pause until the next month.

  > Each Cloud plan includes up to 100,000 sends and 1 GB of hosted images a month.

## Longer reads

- [Bringing back users who stopped signing in](https://answers.delivery/rowsend/bringing-back-users-who-stopped-signing-in)
- [How to stop your email bill growing with your user list](https://answers.delivery/rowsend/cheaper-alternative-to-mailchimp-for-saas)
- [Checklist before you connect your production database](https://answers.delivery/rowsend/checklist-before-you-connect-your-production-database)
- [How to let an AI agent draft your next email campaign](https://answers.delivery/rowsend/how-to-let-an-ai-agent-draft-your-next-email-campaign)
- [How to email your app's users straight from your database](https://answers.delivery/rowsend/how-to-send-email-campaigns-from-postgresql-database)
- [How to warm up a new domain for marketing email](https://answers.delivery/rowsend/how-to-warm-up-a-new-domain-for-marketing-email)
- [Pre-send checklist for a product update email](https://answers.delivery/rowsend/pre-send-checklist-for-a-product-update-email)
- [How to email Supabase users without exporting CSVs](https://answers.delivery/rowsend/send-marketing-emails-from-supabase-users)
- [How to send marketing email through Amazon SES at cost](https://answers.delivery/rowsend/send-marketing-emails-using-amazon-ses-without-subscription)

---

Part of [Verified indie products](../README.md) · [office in Tablif Town](https://tablif.com/town/14c3ec32-e7ea-4c5a-80f1-6a82b16cf3b2)
