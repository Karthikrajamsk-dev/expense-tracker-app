<img src="icon.png" width="96" alt="Expense Tracker icon">

# Expense Tracker

A private, offline expense tracker for Android. It reads the bank and card SMS already on your phone and
turns them into an organised picture of your spending. Nothing leaves the phone.

- No account, no server, no ads, no tracking, no internet use
- Free to use

## Download and install

1. Open the [**Releases**](../../releases/latest) page on your Android phone (7.0 or newer).
2. Download `ExpenseTracker-v1.3.0.apk` (or the newest one listed).
3. Open the file and allow "Install unknown apps" when Android asks.

Updates install over the old version and keep your data.

## What it does

- **Home** — this month at a glance, safe to spend per day, coming bills, cash flow
- **Activity** — every transaction, search and filters, swipe to confirm or delete
- **Accounts** — bank accounts, cards and UPI apps found from SMS or added by hand
- **Insights** — categories, spending calendar, budgets, regular payments
- Custom categories, quick-add buttons, colour themes and your own colours
- Home-screen widget with three views
- App lock (PIN), hide amounts, backup / restore, CSV export

## Banks and currencies

Choose your currency in **Settings › Currency** (26 are built in). The app reads SMS in that currency only.

- **India (₹)** — tuned for the alert formats of most Indian banks, credit cards and UPI.
- **Other countries** — reads English-language bank and card alerts that state the amount with the
  currency and mention an account or card. This is a general reader and has been tested on far fewer
  formats, so some messages will be missed or read wrongly. You can always add or correct entries by hand.

If your bank's SMS is not read correctly, please [open an issue](../../issues/new/choose) with the
**SMS not read correctly** form. Change the numbers and names first — never post real account details.

## Privacy and terms

Only the last digits of account and card numbers are stored. The app never asks for or stores full numbers,
CVV, PIN, OTP or passwords, and the SMS text itself is not kept. See [PRIVACY.md](PRIVACY.md) and
[TERMS.md](TERMS.md).

Bank and payment-app names appear only to describe your own transactions. The app is not affiliated with
any of them and ships none of their logos.

© 2026 Karthik. All rights reserved.
