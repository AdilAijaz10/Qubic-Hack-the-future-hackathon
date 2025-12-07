# Qubic Auto-Tracker

A super simple, fully automatic Qubic wallet & asset monitor that works the moment money moves — no typing addresses, no manual refresh, no code.

Every time a transaction happens on a wallet you follow, **Qubic Auto-Tracker** instantly updates two Google Sheets with fresh data and friendly AI summaries (powered by OpenAI).


### What you get (2 sheets)

**Sheet 1 – Wallet Activity**  
- Wallet address  
- Latest balance  
- Newest transaction  
- Timestamp  
- AI summary in plain English  
  Example: “This wallet just received 500 QUBIC and now holds 2,840 total!”

**Sheet 2 – Owned Assets**  
- Every QXMR share, NFT, token the wallet owns  
- One clean row per asset  
- AI note for each asset  
  Example: “Owns 1,610 full QXMR shares” or “Has 7 rare collectibles”

### How it works (100% automatic)

1. You set up alerts in EasyConnect for the wallets you want to watch  
2. Transaction happens → EasyConnect sends a webhook  
3. Make.com catches it → pulls fresh data from Qubic API  
4. AI writes short, human-friendly summaries  
5. Both Google Sheets update themselves in seconds  

That’s it. No coding, no servers, runs 24/7 forever.

### Tech stack

- EasyConnect (real-time alerts)  
- Make.com (automation & webhooks)  
- Qubic Public API  
- Google Sheets (dashboard)  
- OpenAI / Grok (AI summaries)  

### Want to use it yourself?

1. Duplicate this Google Sheet template → [click here when ready]  
2. Create the same scenario in your Make.com (blueprint available on request)  
3. Connect your EasyConnect alerts to the webhook URL  
4. Done – start adding wallets in EasyConnect and watch the sheets fill up!

Built for the Qubic × EasyConnect hackathon.  
Simple, useful, and completely hands-free.
