# REMOTE DNA — Privacy Policy

**Effective date:** August 18, 2026

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

- Your saved devices, their code sets and any buttons captured with the Hunter.
- Language, theme and onboarding preferences.
- Your Pro licence key and sign-in token (stored in the Android Keystore via
  encrypted storage).

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
issued licence key.

## 4. Advertising

The free tier shows **one optional rewarded video advertisement** before the
Command Hunter, served by **Google AdMob**. There are no banners, no interstitials
and no ads anywhere else in the App.

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
App crashes**. A report contains the technical error, app version and device
model/OS version. Personally identifiable information is explicitly disabled,
and reports are never used for advertising.

## 7. Permissions

- `TRANSMIT_IR` — to emit infrared signals through your phone's IR blaster. IR
  signals are one-way light pulses and carry no personal information.
- `CAMERA` — used **only** when you choose "Import via QR" to scan a
  device-sharing code. Frames are processed live on your device; **no photo or
  video is captured, stored or uploaded**. You may deny it and everything else
  keeps working.
- `INTERNET` — needed only for the optional features above (account, payment,
  ads, crash reports, catalogue updates). All remote-control functions work with
  the network switched off.
- **Local network discovery** — when you use Wi-Fi control, the App looks for
  smart TVs on your own network. This traffic stays inside your home network.

## 8. Your rights and data deletion

- **Delete local data:** uninstall the App, or clear its data in Android Settings.
- **Delete your account and everything linked to it** (email, password hash,
  licence binding): email us at the address below from the account's email and we
  will erase it within 30 days.
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
