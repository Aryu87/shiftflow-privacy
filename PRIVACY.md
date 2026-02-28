# Privacy Policy — ShiftFlow

**Last updated:** February 28, 2026  
**Effective date:** February 28, 2026

---

## 1. Introduction

This Privacy Policy describes how **ShiftFlow** ("the App", "we", "our") handles information when you use our Android application.

ShiftFlow is a work shift tracking application developed by **Lorenzo M.** ("Developer"). The App is designed with privacy as a core principle: **all data remains exclusively on your device**.

---

## 2. Information We Collect

**ShiftFlow does not collect any personal data.**

The App allows you to enter and store the following information **locally on your device only**:

- Work shift records (dates, times, shift types)
- App settings and preferences (hourly rate, standard shift duration, notification preferences, theme, language)

This information is entered voluntarily by the user and is never transmitted outside the device.

---

## 3. How We Use Your Information

The information stored by the App is used exclusively for:

- Displaying your shift history and monthly/yearly statistics
- Calculating worked hours, overtime, and absence days
- Generating PDF reports for personal use
- Sending local reminder notifications (if enabled by the user)

**No data is used for advertising, profiling, analytics, or any purpose other than the App's core functionality.**

---

## 4. Data Storage and Security

- All data is stored locally in a database on your device using **Android Room** (SQLite).
- Settings are stored locally using **Android DataStore**.
- **No data is ever transmitted to external servers**, the developer, or any third party.
- **No internet connection is required or used** by the App (`android.permission.INTERNET` is not declared in the manifest).
- **Cloud backup is disabled** (`android:allowBackup="false"` is set in the AndroidManifest; `data_extraction_rules.xml` explicitly excludes App data from cloud backup).

---

## 5. Third-Party Services

ShiftFlow **does not integrate any third-party service**, including but not limited to:

- No analytics (no Google Analytics, Firebase Analytics, etc.)
- No crash reporting services (no Crashlytics, Sentry, etc.)
- No advertising networks
- No social media SDKs
- No cloud storage services (no Firebase, Google Drive, Dropbox, etc.)
- No authentication services

---

## 6. Permissions

The App requests the following Android permissions:

| Permission | Purpose |
|---|---|
| `POST_NOTIFICATIONS` | To display local reminder notifications (user-configurable, can be disabled at any time) |
| `SCHEDULE_EXACT_ALARM` | To schedule the daily reminder notification at a precise time |
| `WAKE_LOCK` | To briefly wake the device processor when a notification is due |
| `RECEIVE_BOOT_COMPLETED` | To reschedule alarms after device reboot |

**None of these permissions are used to collect, transmit, or process personal data.**

---

## 7. Notifications

If the user enables reminder notifications:

- Notifications are generated and displayed **entirely on-device**.
- No notification content is sent to any server.
- Notifications can be disabled at any time through the App's Settings screen or through Android system settings.

---

## 8. Backup and Restore

The App provides an optional manual backup feature:

- Backup files are exported in **JSON format** to a location chosen by the user on their own device.
- The App does **not** automatically upload backup files anywhere.
- The user is solely responsible for the security and storage of exported backup files.

---

## 9. Data Retention and Deletion

- Your data exists only on your device.
- **Uninstalling the App permanently deletes all data** stored by the App, including shifts and settings.
- There is no account to delete, and no server-side data to request deletion of.

---

## 10. Children's Privacy

ShiftFlow is intended for adults managing their professional work schedule. The App does not knowingly collect any information from children under the age of 13. Since no data is collected whatsoever, there is no risk of inadvertent collection from minors.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be posted on this page with an updated "Last updated" date. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 12. Contact

If you have any questions about this Privacy Policy or the App's data practices, you can contact the developer:

**Developer:** Lorenzo M.  
**App:** ShiftFlow  
**Package:** `it.lorenzo.shiftflow`  
**Contact:** quasar87@hotmail.com

---

## 13. Governing Law

This Privacy Policy is governed by the laws of Italy and the European Union, including the General Data Protection Regulation (GDPR — EU 2016/679).

Under GDPR, since ShiftFlow collects no personal data and processes no data on external servers, the App acts solely as a local data processor for the user's own personal use on their own device.

---

*Privacy Policy for ShiftFlow — Developed by Lorenzo M.*

---

> **Note for Google Play Store:** This privacy policy is publicly accessible at the GitHub Pages URL associated with this repository and satisfies Google Play's requirement for apps that request sensitive permissions (`POST_NOTIFICATIONS`, `SCHEDULE_EXACT_ALARM`, `RECEIVE_BOOT_COMPLETED`).
