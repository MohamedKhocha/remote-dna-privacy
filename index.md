# REMOTE DNA — Privacy Policy

[العربية](ar.html) · [Français](fr.html) · [Español](es.html) · [Português](pt.html) · [中文](zh.html)

**Effective date:** August 18, 2026 · **Last updated:** October 30, 2026

REMOTE DNA ("the App") is a universal remote-control application for TVs and
air conditioners, published by **Solar AI Systems** (Mohamed Khocha), Algeria.

This policy describes exactly what the App does and does not collect. It is
kept in sync with the shipping code.

## Summary

- Everything you need to control your devices works **offline**, on your phone.
- The App works **without an account**. An account is optional and exists only
  so a paid Pro licence can be restored on a new phone.
- We never sell your data and never use it for advertising profiles.

## 1. Data stored on your device only

The following never leaves your phone:

- Your saved devices, their code sets and any buttons you taught the App
  ("Teach my TV", "Fix a button").
- Language, theme and onboarding preferences. Until you pick a language, the
  App follows your phone's language, read on the device.
- Your Pro licence key and sign-in token (stored in the Android Keystore via
  encrypted storage).
- Wi-Fi pairing data for your TVs: the key an LG or Samsung TV issues when you
  accept the connection, and for Android TV a client certificate generated in
  the Android Keystore plus the TV's certificate fingerprint. They let the App
  reconnect without asking again and are used only on your home network.
- For a Gree air conditioner on Wi‑Fi, the encryption key the unit gives the App
  when it is paired; for the Bluetooth remote, the paired TV's Bluetooth
  address. Both are used only to reach that device.

Uninstalling the App deletes all of it.

## 2. Optional account

If — and only if — you create an account, we store on our server:

- Your **email address**.
- A **cryptographic hash** of your password (PBKDF2-HMAC-SHA256). We never
  store or see your actual password.
- The date the account was created, and the Pro licence linked to it.

Purpose: restoring your Pro licence on a new phone, and resetting your password.

**Password reset emails** are sent through Resend (resend.com). Only your email
address and a temporary 6-digit code are transmitted.

You can request deletion of your account at any time — see section 8.

## 3. Payments

Pro is a one-time purchase. How it is paid depends on where you installed the
App from, and this section discloses the payment processor used in each case.

- **If you installed the App from Google Play** — the only in-app purchase route
  is **Google Play Billing**, handled through RevenueCat, which identifies your
  purchase with an anonymous identifier. We receive no card data.
- **If you installed the App directly from our website** (the version
  distributed outside Google Play) — payment is processed by **Chargily Pay** on
  their own secure page. Your card details are entered on Chargily's site and are
  **never seen, handled or stored by the App or by us**. Chargily provides us with
  the transaction reference, amount and status, and Chargily's own privacy policy
  applies to the data you enter there. This route is not offered inside the
  Google Play version of the App.

In both cases we store only the transaction reference, amount, status and the
issued licence key, with the dates on which the key was delivered to the App and
activated (no IP address and no device identifier), so a purchase can be
checked if you ask us about it.

## 4. Advertising

The free tier shows advertisements served by **Google AdMob**:

- an **app-open ad** when the App starts (never on the very first launch, and
  on returning from the background only after a long absence);
- now and then a **full-screen ad between screens**;
- a short **rewarded video** every three uses of "Fix a button".

Two full-screen ads are always at least three minutes apart. There are no
banners. If no ad can be shown, the App carries on without it.

- Ads are requested with the **"G" (general audiences) content rating** only,
  and start **muted**.

- In the EEA, the UK and Switzerland, a **consent form (Google UMP)** is shown
  before any ad is requested, and your choice is respected.
- AdMob may process device identifiers for ad delivery and frequency capping in
  accordance with [Google's privacy policy](https://policies.google.com/privacy).
- **Pro users see no advertisements at all**, and no ad SDK request is made for
  them.

## 5. Optional code contribution (the "genetic network")

This is **off by default** and requires your explicit consent.

If you enable it and choose to share a device's codes, we receive:

- The infrared protocol, address and button codes of that device.
- The brand/model label you typed, and the app version.
- A **random identifier generated on your device at install time** — used only
  to count distinct contributors so codes can be verified by majority agreement.

This contains **no name, email, phone number, location or advertising ID**, and
it cannot be linked back to you. You can turn contribution off at any time in
Settings.

## 6. Crash reports

Anonymous crash reports are sent to **Sentry** (EU data region) **only when the
App crashes or hits an error**. A report contains the technical error, app version and device
model/OS version. Personally identifiable information is explicitly disabled,
and reports are never used for advertising.

**Server status check.** When the App opens, it sends one empty request to our server's status page, so the server is awake before you need it. The request carries no identifier and no data about you or your devices.

**Server logs.** Like any web server, ours (hosted on Render) records each request's IP address, time, address requested and app type in technical logs. They serve security and troubleshooting only and are deleted after the short period set by the host.

**Where data is stored.** Our server and its database (Render, MongoDB Atlas) and the email service (Resend) are located outside Algeria; Sentry stores crash reports in the European Union; Google (AdMob, Play) and RevenueCat process data under their own policies. Website payments are handled by Chargily in Algeria.

**How long we keep it.** Account data: until you delete the account. Reset and confirmation codes: 30 minutes. Unpaid checkout records: 48 hours. Licence and payment records: as long as accounting and tax law requires. Shared codes: they stay in the anonymous catalogue.

**Legal bases.** Account and Pro: to perform our contract with you. Code contribution and personalised ads: your consent, which you can withdraw. Crash reports, server logs and abuse protection: our legitimate interest in a secure, working App.

## 7. Permissions

- `TRANSMIT_IR` — to emit infrared signals through your phone's IR blaster. IR
  signals are one-way light pulses and carry no personal information.
- `CAMERA` — used **only** when you choose "Import via QR" to scan a
  device-sharing code, or "Find by model" to read the model number on a
  device's label. Everything is processed on your device: a label photo is
  **deleted as soon as it has been read**, and **no photo or video is stored or
  uploaded**. You may deny it and everything else keeps working.
- **Choosing a photo** — in "Find by model" you can also pick a label photo
  you already took. Android's photo picker gives the App that one photo and
  nothing else, with no storage permission; it is read on your device, the copy
  made for reading is deleted, and nothing is uploaded.
- `INTERNET` — needed only for the optional features above (account, payment,
  ads, crash reports, catalogue updates). All remote-control functions work with
  the network switched off.
- **Local network discovery** — when you use Wi-Fi control, the App looks for
  smart TVs on your own network (SSDP/DIAL and mDNS), and when you type a TV's
  IP address it checks which control ports answer on that one address to tell
  the TV's system. It only talks to the device you choose, and this traffic
  stays inside your home network.
- `BLUETOOTH_CONNECT`, `BLUETOOTH_SCAN`, `BLUETOOTH_ADVERTISE` ("Nearby
  devices") — used **only** when you choose the Bluetooth remote or the cursor:
  to find your TV, pair with it, make the phone visible to it while pairing, and
  send it key presses and pointer moves. The search is declared "never for
  location", and the names and addresses it sees are not kept, except the
  address of the TV you choose.
- `ACCESS_FINE_LOCATION` — requested **only on Android 11 and older**, and only
  when you tap "Search for nearby devices": those Android versions allow a
  Bluetooth search only with this permission. The App never reads, stores or
  sends your location. Android 12 and later never ask for it.
- **Gree air conditioners** — to control a Gree unit over Wi‑Fi, the App finds it
  with a broadcast on your own network and talks to it directly (encrypted, UDP
  port 7000). Nothing passes through any server.
- `AD_ID` (advertising ID) — declared by Google AdMob for the ads described in
  section 4. Pro users make no ad requests.

The App does **not** request microphone, contacts, phone, SMS or file-storage
permissions, and asks for location only as described above (Android 11 and
older, for the Bluetooth search).

## 8. Your rights and data deletion

Under Algerian Law No. 18-07 on the protection of personal data, and the GDPR where it applies, you can access, correct, oppose or delete your data, and complain to the national authority (ANPDP in Algeria, or your local data-protection authority).

- **Delete local data:** uninstall the App, or clear its data in Android Settings.
- **Delete your account and everything linked to it** (email, password hash,
  licence binding): in the App, open **Me → Account → Delete account
  permanently**. The record is erased immediately — no request, no waiting. A Pro
  licence you paid for is **unlinked, never revoked**: the key keeps working and
  can be activated again later. If you cannot reach the App, email us at the
  address below from the account's email and we will erase it within 30 days.
- **Withdraw code-contribution consent:** turn it off in Settings. Previously
  contributed codes are anonymous and cannot be traced back to you.

## 9. Children

The App is a general-audience utility. It is not directed at children and we do
not knowingly collect data from them.

## 10. Changes

If a future version changes these practices, this policy is updated **before**
that version ships, and the in-app link points to the revised text.

## 11. Contact

Questions, data-deletion requests or anything else:

**solar.ai.systems@gmail.com**

Solar AI Systems — Algeria

---

See also: [Terms of Use and Sale](terms.html)
