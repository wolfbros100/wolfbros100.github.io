---
permalink: /swipe2cloud/privacy/
---

# Privacy Policy — Swipe2Cloud

**Effective date:** 2026-11-21
**Version:** 1.1.1 (corrects section 1 and adds section 3.1; the app itself has not changed)
**Developer:** Wolf Bros — wolfbros.100@gmail.com

---

## 1. In short

Swipe2Cloud is an Android app for sorting the photos and videos on your phone: swipe right to back an item up to **your own Google Drive**, swipe left to mark it for removal. Your photos and videos go straight from your phone to your Google Drive. The developer never receives them, and has no server of its own.

What can reach the developer:

- a **crash report**, and only if you say yes to sending them (section 4);
- what you choose to send: an **email**, or a **review** on Google Play (section 3.1);
- if you join a test of the app, possibly the **email address** you joined the test with (section 3.1);
- **statistics from Google Play** that do not identify you (section 3.1).

An earlier version of this policy (1.1) said that only crash reports can reach the developer. That was incomplete; this version corrects it.

See also the [Terms of Use](/swipe2cloud/terms/).

---

## 2. What the app uses on your phone

### 2.1 Photos and videos

The app asks for access to the photos and videos on your phone, so it can show them to you one by one. If you allow access only to selected items, the app shows only those.

- Items you swipe right are uploaded to a folder you choose in **your own Google Drive**.
- Items you swipe left are never uploaded. When you finish, the app offers to move the items you sorted to your phone's **system trash**. This always goes through an Android confirmation dialog that you must approve; the app cannot delete anything on its own.

### 2.2 Google sign-in and Google Drive

You sign in with Google and allow the app to use Google Drive with the `drive.file` permission. With it, the app can see **only the files and folders it created itself** — nothing else in your Drive.

- The app does not keep your password or a Google access token on the phone. When it needs to talk to Drive, it asks Android's Google services for a short-lived permission each time.
- The app does not store your email address.

### 2.3 What the app keeps on the phone

To work, the app keeps a small amount of data **on your phone only**:

- the list of items waiting to upload and their status;
- the Drive folder you chose (its ID and name);
- your settings (for example Wi-Fi-only uploads, video sound, crash reports on or off);
- whether you have agreed to this policy and the Terms, and to which version;
- how many items you have sorted in the free daily allowance, and when it started.

None of this is sent to the developer. It is deleted when you clear the app's data (Android Settings → Apps → Swipe2Cloud → Storage → Clear data) or uninstall the app.

### 2.4 What the app adds in your Google Drive

For each uploaded file, the app saves a checksum (a SHA-256 fingerprint of the file's content) as a hidden property of that file in your Drive. It uses it to recognise a file that is already there, so the same photo is not uploaded twice. It stays in your Drive with the file.

---

## 3. Who receives your data

| Data | Who receives it |
|------|-----------------|
| Photos and videos you upload | **Google**, as the provider of your own Google Drive. Never the developer. |
| Crash reports (only if you agree) | **Google**, through Firebase Crashlytics, on behalf of the developer. See section 4. |
| Emails you send, reviews you post, the email address you joined a test with | **The developer**. See section 3.1. |
| Everything else in section 2.3 | **Nobody.** It stays on your phone. |

Your Google Drive is governed by Google's own [Privacy Policy](https://policies.google.com/privacy) and [Terms of Service](https://policies.google.com/terms).

The app contains no advertising, no usage analytics and no social media integrations. Your data is not sold or used for advertising.

### 3.1 Emails, reviews, tests and Google Play statistics

**Emails.** If you write to the developer, the developer receives your email address and what you write, and uses it only to answer you (legitimate interest in answering, GDPR Art. 6(1)(f)). It is kept as long as needed to settle the matter. If the message is a complaint or a claim, it is kept, with the reply, until a legal claim about it can no longer be brought (Art. 6(1)(f): legitimate interest in establishing or defending legal claims).

**Reviews.** A review you post on Google Play is shown to the developer in Google Play's developer console with the name Google Play shows for you. The developer can reply to it there. Google Play decides how reviews are published and kept.

**Tests.** If you join a test of the app (for example a closed test on Google Play), the developer may see the email address you joined with — for example when testers are invited by email. It is used only to run the test (Art. 6(1)(f)); ask, and it is removed from the developer's test list.

**Statistics.** Google Play shows the developer figures that do not identify you, such as installs per country and app crashes per phone model, which Android collects if you allowed it in your phone's settings.

---

## 4. Crash reports

When you first open the app, it asks whether to send crash reports. **They are off unless you tap "Send reports".** You can turn them on or off at any time in the app's **Settings → Send crash reports**.

If you agree, then when something goes wrong in the app, a report is sent to **Firebase Crashlytics**, a Google service the developer uses to find and fix problems.

**A report contains:**

- what went wrong in the app: the type of error and where in the app's code it happened;
- your phone's model and Android version, and the app's version;
- a random ID for this installation of the app, used to count how many installations a problem affects;
- for a few known problems, counts and categories — for example whether an item was a photo or a video, a rough size range (such as "under 10 MB"), or the general shape of a file name (its length range, the kinds of characters in it, and its extension if it is a common photo or video extension).

As with any internet connection, the report reaches Google from your phone's **IP address**.

**A report never contains:** your photos or videos, file or folder names, your Google account or email address, or the text of error messages (which could contain such details — the app removes it before a report is sent).

**Retention:** Google keeps crash reports and the installation ID for **90 days**, after which they are deleted.

**Legal basis:** your consent (GDPR Art. 6(1)(a)). You can withdraw it at any time in Settings; reports stop from that moment. Withdrawing does not affect reports already sent, which are deleted after 90 days. Because a report does not contain anything that identifies you, the developer cannot find a particular person's reports.

---

## 5. Security

- All data the app sends — to Google Drive and to Crashlytics — is encrypted in transit (HTTPS/TLS).
- The data the app keeps on the phone (section 2.3) is protected by Android's app sandbox, so other apps cannot read it. It is not additionally encrypted by the app.

---

## 6. International transfers

Google may process uploaded files and crash reports in countries outside your own, including the United States. Google uses the European Commission's Standard Contractual Clauses for such transfers; see Google's [Privacy Policy](https://policies.google.com/privacy).

---

## 7. Your rights

If you are in the European Economic Area, you have the right to access, correct and delete your personal data, to restrict or object to its processing, to data portability, and to withdraw consent at any time.

In practice:

- **Data on your phone:** you control it fully — see and change your settings in the app, and delete everything by clearing the app's data or uninstalling it.
- **Files in your Google Drive:** you manage them in Google Drive. You can also remove the app's access in your Google Account → Security → Third-party apps & services.
- **Crash reports:** turn them off in Settings. Sent reports are deleted after 90 days.

You also have the right to complain to a data protection authority. In Lithuania this is the State Data Protection Inspectorate (Valstybinė duomenų apsaugos inspekcija, [vdai.lrv.lt](https://vdai.lrv.lt)); you may also contact the authority in your own country.

We answer requests sent to the email below within 30 days.

---

## 8. Children

The app is not directed at children under 14. We do not knowingly collect personal data from children. If you believe a child has sent us data, contact us and we will delete what we can.

---

## 9. Changes to this policy

When this policy changes in a way that matters, the version and date above are updated, and the app shows you what changed and asks you to agree again before you continue.

---

## 10. Contact

**Wolf Bros** — wolfbros.100@gmail.com
