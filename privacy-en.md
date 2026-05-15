# Cat Ledger Privacy Policy

**Effective Date**: 2026-05-12
**Version**: v1.0
**Scope**: iOS app "Cat Ledger" (com.bai.catledger)

We respect your privacy. This policy describes what data we process, why, and where it goes.

---

## 1. Data We Process

### 1.1 Data Processed Locally (Not Uploaded)

- **Ledger data**: amounts, categories, accounts, notes, timestamps, merchant names
- **Payment screenshots**: processed by iOS Vision Framework on-device OCR; both originals and recognition results stay on your device only
- **Merchant memory**: "merchant → category" key-value pairs you confirmed
- **App settings**: cat persona, monthly budget, reminder time, subscription status, etc.

### 1.2 Data Handled via Apple Services

- **Subscription status**: managed by StoreKit / App Store. We only read the "is Pro" status, never your Apple ID, payment method, or transaction receipt
- **Local notifications**: scheduled via iOS UNUserNotificationCenter (budget alerts, daily reminders); no third-party push servers

### 1.3 Data We Do NOT Collect

- Any device identifiers (IDFA / IDFV / device name)
- Location, contacts, photo library (we only read screenshots you actively pick to import)
- Browsing history, app list, ad clicks, or any behavioral analytics
- Any third-party SDK for advertising or analytics

---

## 2. Where Data Is Stored

- All ledger data lives in iOS sandbox SwiftData local database
- If you enable iCloud sync (future feature), data syncs via Apple CloudKit within your iCloud account, never through us
- Deleting the app removes all local data via iOS

---

## 3. Data Export and Backup

- Export CSV or full JSON backup at any time via "Settings → Data". The exported file is yours to keep
- Backup files contain all your ledger data — keep them safe

---

## 4. Third-Party Services

- **Apple StoreKit**: subscription purchases and verification. Privacy policy provided by Apple
- **Apple Vision Framework**: on-device OCR. All recognition happens on your device

The app itself does **not** integrate any third-party analytics, advertising, push notification, AI, or crash reporting service.

---

## 5. Notification Permission

Budget alerts and daily reminders use iOS local notifications. iOS prompts you for permission on first enable. You can revoke at any time via "Settings → Cat Ledger → Notifications". We do not send remote push notifications.

---

## 6. Merchant Memory and "Smart Learning"

"Auto-learn merchant category" is on by default but local-only:
- Records "merchant name → category" mapping only after you **confirm save** an OCR receipt
- Used only for local pre-fill on next OCR of the same merchant
- Toggle off or delete individual entries via "Settings → Smart Learning"

---

## 7. Future Changes

If we add any of the following, we will prompt for explicit consent before enabling:
- Cloud AI analysis (bill interpretation, spending summaries, etc.)
- Cloud OCR
- Any form of data upload

We will not enable the above without your explicit consent.

---

## 8. Children's Protection

This app is intended for users 12+ years old. We do not collect any child-specific data.

---

## 9. Your Rights

You can at any time:
- Delete any transaction or merchant memory in-app
- Disable notification permission via iOS Settings
- Uninstall the app, removing all local data

---

## 10. Contact

For privacy questions, leave a comment in App Store reviews. We respond within 48 hours.

---

**Note**: This policy ships with the app and is updated as needed. Material changes will trigger an in-app prompt to re-confirm.
