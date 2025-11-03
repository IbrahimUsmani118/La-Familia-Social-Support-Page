# La-Familia-Social-Support-Page

_Last updated: **October 2025**_

Welcome to the **La Familia Social** Support page. This page answers the most common questions about accounts, messages, image uploads (including our duplicate-image blocking), app permissions, privacy, and how to get help.

> **TL;DR**
> - We don’t sell your data.
> - DMs are encrypted in transit and at rest; one-to-one chats may use end-to-end encryption where supported.
> - We compute a **non-reversible image fingerprint** on upload to reduce spam; a third identical upload is blocked automatically.
> - You can delete your account and request your data.

---

## What We Collect (at a glance)

- **Account & Profile:** email, username, display name, photo, bio.
- **User Content:** posts, comments, reactions, messages, media.
- **Social Graph:** follows/followers, blocks/mutes.
- **Duplicate-Image Fingerprints:** non-reversible perceptual hashes + minimal counters.
- **Device & Usage:** app version, OS, crash logs, coarse analytics (no cross-app ads).
- **Optional Signals:** approximate location (if you add it), contacts discovery (opt-in), push tokens.
- **Web (only):** cookies/local storage for auth/session/basic analytics.

See also: [Privacy & Data Requests](#privacy--data-requests)

---

## Account Management

### Create an Account
1. Open the app → **Sign up**.
2. Verify your email if prompted.
3. Set your display name and (optional) profile photo.

### Delete Your Account
- **In-app:** Settings → Account → Delete Account (if available).
- Or email support (see [Contact Support](#contact-support)) from your account email with subject: **Delete Account**.

> Deletion removes your profile and content from the service. Some operational logs may persist briefly for security, then purge.

### Change Email / Username / Photo
- **Settings → Profile** to edit your details.
- Save to apply changes across sessions.

---

## Messaging & Encryption

- **Encryption in transit and at rest:** All messages use TLS over the network and encrypted storage on our servers.
- **End-to-End Encryption (E2EE):** Where supported for **one-to-one** messages, only sender and recipient hold the keys.
- **Backups & multi-device:** If you export/backup keys (where available), store them securely; losing keys may prevent message recovery.

> If you suspect device compromise, immediately log out of other sessions and update your password.

---

## Duplicate-Image Detection & Blocking

To fight spam and harmful mass-reposts:

- On every image upload, we compute a **non-reversible perceptual hash** (an image “fingerprint”).
- **Policy:** The **same image** may be uploaded **twice**. A **third** attempt is **blocked automatically**.
- We store **only** the fingerprint and minimal counters needed to enforce this rule.
- We **do not share** fingerprints with third parties.

### Common Questions
**Q:** _My third upload was blocked but I edited the image slightly._  
**A:** Minor edits often yield a similar fingerprint. Try materially changing the content (crop/overlay alone may not be enough). The system aims to catch near-identical resubmits.

**Q:** _Can Support “whitelist” my image?_  
**A:** We don’t disable global safeguards, but you can appeal if you believe the block is erroneous (see [Contact Support](#contact-support)). Include the image, timestamps, and the upload flow you used.

---

## Permissions (iOS)

We request permissions **only when needed**, and you can change them anytime in **Settings → La Familia Social**:

- **Camera:** capture photos/videos to post or DM.
- **Photo Library / Add:** select and (optionally) save media.
- **Microphone:** record audio/video messages (if you use these features).
- **Notifications (optional):** message & activity alerts.
- **Contacts (optional):** friend discovery (opt-in only).

> If a feature isn’t working, confirm the permission is enabled for La Familia Social.

---

## Privacy & Data Requests

You control your data:
- **Delete Content:** remove your posts, comments, and media in-app.
- **Delete Account:** see [Account Management](#account-management).
- **Access / Correction / Deletion (GDPR/CCPA and similar):**
  - Email us (see [Contact Support](#contact-support)) with your request.
  - Use subject lines like **Data Access Request**, **Data Deletion Request**, or **Rectification Request**.
  - We’ll verify ownership via your account email and respond within an applicable legal window.

**International Transfers:** Data may be processed in the **United States** and other regions where our cloud providers operate, with appropriate safeguards where required.

**Security:** We use encryption, access controls, and industry-standard safeguards. No method is 100% secure; we continuously improve protections.

**Retention:**
- **User Content:** kept to provide the service until you delete it or delete your account.
- **Duplicate-Image Fingerprints:** kept only as long as necessary to enforce limits and protect the service; deleted when no longer needed or upon account deletion.
- **Diagnostics:** retained temporarily to improve stability.

**Children’s Privacy:** Not directed to children under 13. If we learn we collected data from a child under 13, we will delete it.

---

## Troubleshooting

### Can’t See Notifications
- iOS **Settings → Notifications → La Familia Social** → allow Alerts & Badges.
- In-app **Settings → Notifications** → ensure categories you care about are enabled.

### Media Upload Fails
- Check network connectivity and available device storage.
- Confirm **Camera/Photos** permissions are enabled.
- If the error cites **duplicate-image** policy, see [Duplicate-Image Detection & Blocking](#duplicate-image-detection--blocking).

### App Crashes or Freezes
- Update to the latest app version (App Store).
- Reboot your device.
- If it persists, send **crash time**, **steps to reproduce**, and **screenshots** (see [Contact Support](#contact-support)).

### Message Not Delivering
- Verify recipient follows you (if required by your privacy settings).
- Check if you or the recipient have blocked/muted each other.
- Poor network? Try on Wi-Fi and cellular.

---

## Frequently Asked Questions (FAQ)

**Do you sell my data?** No. We do **not** sell, rent, or trade your data.

**Who do you share data with?** Only **service providers** under contract (e.g., cloud hosting, crash analytics), or as required by **lawful requests**, or to **prevent fraud/abuse**.

**Do you track me for ads?** No cross-app ad tracking. We use coarse, privacy-preserving analytics to improve features and reliability.

**How long to process a data request?** We acknowledge promptly and complete within the applicable legal timeframe (jurisdiction-specific).

---

## Contact Support

**General & Account Help** - Ibrahim Usmani — 📩 [onlyibrahim13@gmail.com](mailto:onlyibrahim13@gmail.com)  
- Joel Minaya — 📩 [jminaya20@gmail.com](mailto:jminaya20@gmail.com)

_When writing in, include:_
- Your **account email/username**
- **Device & OS** (e.g., iPhone 14, iOS 18.x)
- **App version** (Settings → About)
- **Issue summary**, **steps to reproduce**, **timestamps**, and **screenshots** if possible

---

## Service Notices & Changes

We may update features and this Support page periodically. For **material changes** to policies, we’ll provide in-app or email notice and update the “Last updated” date.

Stay safe and create boldly — we’re here to help.
