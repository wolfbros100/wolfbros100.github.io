---
permalink: /swipe2cloud/privacy/
---

# Privacy Policy — Swipe2Cloud

**Effective date:** 2026-04-23
**Version:** 1.0
**Developer:** Wolf Bros — wolfbros.100@gmail.com

---

## 1. Introduction

Swipe2Cloud ("the app", "we", "our") is an Android application that allows you to back up photos from your device to your own Google Drive account by swiping. This Privacy Policy explains what data the app accesses, how it is used, and your rights regarding that data.

By using Swipe2Cloud, you agree to the practices described in this policy.

---

## 2. What Data We Access

### 2.1 Photos and Videos

The app requests access to photos and videos stored on your device. This access is used solely to display your media library within the app so you can select photos for backup by swiping right.

- Photos and videos are **not uploaded to any developer-controlled server**.
- Selected photos are uploaded directly to **your own Google Drive account** via the Google Drive API.
- If you grant partial access, only the photos you selected are shown. The app does not require full access to function.

### 2.2 Google Account (OAuth Token)

To connect to Google Drive, the app uses Google's OAuth authentication. The resulting access token is:

- Stored **locally on your device** using the Android Credential Manager (backed by Android Keystore).
- Used **only** to authenticate requests to the Google Drive API on your behalf.
- **Never transmitted to or accessed by the developer.**

### 2.3 Upload Queue Data

The app maintains a local database of photos you have queued for upload, including file references and upload status (pending, uploaded, failed).

- This data is stored **locally on your device** only.
- It is **never transmitted to the developer** or any third party.
- It contains no photo content — only file references and status metadata.

---

## 3. How We Use Your Data

| Data | How it is used |
|------|---------------|
| Photos and videos | Displayed in the app UI; uploaded to your own Google Drive on your request via swipe gesture |
| OAuth access token | Maintains your authenticated session with Google Drive API |
| Upload queue metadata | Tracks which photos you have queued and their current upload status |

We do not use your data for advertising, analytics, profiling, or any purpose other than providing the upload functionality described above.

---

## 4. Data Sharing

### 4.1 Google (Google Drive API)

Photos you select for backup are uploaded to your own Google Drive account using the Google Drive API. This upload is initiated by your swipe gesture.

- The upload destination is your personal Google Drive — not a developer-controlled server.
- Google's own [Privacy Policy](https://policies.google.com/privacy) and [Terms of Service](https://policies.google.com/terms) govern data stored in Google Drive.
- Google processes this data under its [Data Processing Terms](https://cloud.google.com/terms/data-processing-addendum) and uses Standard Contractual Clauses (SCCs) for EU-US data transfers.

### 4.2 No Other Third Parties

No other third party receives any data from this version of the app. The app does not include:

- Analytics or crash reporting SDKs
- Advertising networks
- Social media integrations
- Any backend service operated by the developer

---

## 5. Data Retention

| Data | Retention period |
|------|-----------------|
| Photos and videos | Not stored by the app. Accessed at time of upload only. |
| OAuth access token | Retained until you sign out or clear app data. |
| Upload queue metadata | Retained until you uninstall the app or clear app data via Android Settings → Apps → Swipe2Cloud → Clear Data. |
| Data in Google Drive | You control your own Google Drive. Deletion of uploaded photos is your responsibility, managed directly in Google Drive. |

---

## 6. Data Security

- All data transmitted to Google Drive is encrypted in transit using **HTTPS (TLS)**.
- OAuth tokens are stored using the **Android Keystore** — system-level hardware-backed encryption.
- Local upload queue data is stored in a standard SQLite database and is **not encrypted at rest**.
- The app does not transmit any data to developer-controlled infrastructure.

---

## 7. Your Rights (GDPR)

If you are located in the European Economic Area (EEA), you have the following rights regarding your personal data:

**Right of access:** Upload queue data (file references and upload status) is visible within the app.

**Right to erasure:** All local data stored by the app can be deleted at any time by:
- Going to Android Settings → Apps → Swipe2Cloud → Clear Data, or
- Uninstalling the app.

For data you have uploaded to Google Drive, deletion is managed directly in your Google Drive account.

**Right to data portability:** Upload queue data is stored locally on your device and is accessible through standard Android data management.

**Response timeframe:** We will respond to data rights requests within 30 days.

**Cross-border transfers:** Photo uploads are processed by Google's infrastructure in the United States and other regions. Google uses Standard Contractual Clauses (SCCs) approved by the European Commission for these transfers. See [Google's Data Processing Terms](https://cloud.google.com/terms/data-processing-addendum) for details.

---

## 8. International Data Transfers

This app uploads photos to Google Drive via the Google Drive API. Google operates globally and your data may be processed in countries outside your country of residence, including the United States.

Google LLC has implemented Standard Contractual Clauses (SCCs) as a lawful transfer mechanism for EU personal data. Details are available in [Google's Privacy Policy](https://policies.google.com/privacy) and [Data Processing Terms](https://cloud.google.com/terms/data-processing-addendum).

---

## 9. Children's Privacy

This app is not directed at children under the age of 13. We do not knowingly collect personal data from children under 13. If you believe a child under 13 has used this app, please contact us at wolfbros.100@gmail.com and we will take appropriate action.

---

## 10. Changes to This Policy

We will notify you of material changes to this Privacy Policy by:
- Updating the "Effective date" at the top of this document, and
- Displaying an in-app notice or updating the Play Store listing.

Continued use of the app after changes take effect constitutes acceptance of the updated policy.

---

## 11. Contact

For privacy-related questions or data deletion requests, contact:

**Email:** wolfbros.100@gmail.com

We will respond within 30 days.
