---
layout: default
title: Privacy policy
permalink: /privacy/
---

# Privacy policy

<p class="meta">Effective {{ site.effective_date }}</p>

{{ site.title }} is a timing game: tap to start a stopwatch, tap again to stop it on exactly 3.00. This policy explains what the app collects, why, where it goes, and how to delete it. The app is published by {{ site.publisher }} ("we").

## The short version

- No ads, no analytics, no tracking, and no third-party SDKs that collect data.
- We never sell your data or share it for advertising.
- Your game history stays on your phone. Once the app has an internet connection, it also syncs to an account so you can get it back after a reinstall, and so that leaderboards can be added later.
- You don't need an email address or a password. Signing in with Apple or Google is optional.
- You can delete your account and all of its data from inside the app at any time.

## What we collect

### Game attempts

For every attempt, including cancelled ones:

- a random attempt ID;
- a random device ID the app generates when it is installed;
- a sequence number;
- the time of the attempt in UTC and your phone's timezone offset at that moment;
- the mode (visible or blind);
- the measured time between your two taps;
- whether the attempt was cancelled, and why;
- whether it was made through a screen reader.

We use these to keep your history and stats, to restore them on a new install, and, once leaderboards exist, to rank results. Attempts made through a screen reader are kept with your history but excluded from rankings.

### Account

- A random user ID, created the first time the app syncs.
- Your handle, which the app generates (for example `quiet-heron-482`) and you can change. Your handle is public: it may be shown to other players next to your results.
- If you sign in with Apple or Google: the account identifier that service gives us and, if the service shares one, your email address. Apple lets you hide your real address behind a relay address. We use the email only to identify your account and to reply if you contact us. We never send marketing.
- If you sign in with Apple: a token Apple issues to us, kept only so that we can revoke your Apple sign-in when you delete your account, as Apple requires.

### Technical data

Our hosting provider records the IP address and basic details of each request (time, endpoint, response) in server logs. These are used for security and abuse prevention and kept for a short period set by the provider. We do not use your IP address to identify you, and we do not record your location.

### What stays on your phone

Settings (sound, music, mode), badges and milestones are stored only on your phone. Your login session is stored in your phone's secure storage: the iOS Keychain, or Google's Block Store on Android. That is how the app gets your account back after a reinstall. On Android, Block Store can include it in your Google backup, end-to-end encrypted, so the account also moves to a new phone that you restore from that backup.

### What we do not collect

Contacts, photos, location, microphone, advertising identifiers, hardware identifiers, and browsing or purchase history. The app shows no ads. Sharing a result uses your phone's share sheet: we never see what you share or who you share it with.

## Who processes your data

- **Supabase** hosts our database, accounts and server functions, in the United States.
- **Apple** and **Google** handle sign-in if you choose to use it. Google also stores your session in Block Store on Android.

These providers act on our instructions. Nobody else receives your data, unless the law requires us to disclose it.

## Legal basis

If you are in the European Economic Area or the United Kingdom, we process your data to provide the game and your account at your request (performance of a contract), and to keep the service secure and fair (our legitimate interests). Your data is transferred to the United States under the safeguards in our providers' data processing terms.

## How long we keep it

Your account and attempts stay until you delete them. Deleting the app on its own does not delete your account, because the account exists so you can get your history back. To erase everything, delete your account first; see [Delete your account]({{ '/delete-account/' | relative_url }}).

If you lose access to an account without having signed in with Apple or Google (for example, after a factory reset), that account stays on our servers and its results stop appearing as soon as it goes inactive. Email us with its handle and we will delete it.

## Your rights

You can see your data in the app, change your handle, and delete your account and all of its data from the app. You can also email us to ask for a copy of your data, to correct it, to delete it, or to object to how we use it. We answer within 30 days. If you are in the EEA or UK, you can also complain to your data protection authority.

California residents: we do not sell or share personal information as the CCPA defines those terms, and we do not use sensitive personal information.

## Children

The app is not directed at children under 13, and we do not knowingly collect data from them. If you believe a child under 13 has created an account, email us and we will delete it.

## Security

Data travels to and from our servers over encrypted connections (TLS). The app cannot write to our database directly: every change goes through server functions that check it. Your session on the phone is held in the platform's secure storage.

## Changes

We will update this page, and the date at the top, before changing what the app collects. That includes adding leaderboards that show results by country. Significant changes will also be announced in the app.

## Contact

{{ site.publisher }}, <a href="mailto:{{ site.contact_email }}">{{ site.contact_email }}</a>
