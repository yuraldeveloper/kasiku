# Privacy Policy

**Last updated: November 13, 2026**

## 1. Introduction

Yural Dev ("we", "our", or "us") operates Kasiku (the "Application"), a personal finance tracking application. This Privacy Policy explains how we collect, use, store, and protect your information when you use our Application.

By using Kasiku, you agree to the practices described in this Privacy Policy. If you do not agree, please discontinue use of the Application.

## 2. Information We Collect

Kasiku is designed as a **privacy-first, local-storage application**. All your financial data is stored locally on your device. We **do not** collect, transmit, or store your financial data on external servers.

### 2.1 Information You Provide

The Application stores the following information locally on your device:

| Data Category              | Specific Data                                                                                                                                                     | Purpose                                                              |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| **Financial Transactions** | Income, expense, and transfer records including amount, date, time, category, and related asset                                                                   | Core application function — personal finance tracking                |
| **Transaction Photos**     | Up to 5 photos per transaction taken from the camera or selected from the gallery; stored as files in the app's private documents folder                         | Transaction proof and context; not uploaded, not included in backup or export |
| **Asset Information**      | Asset name, type (cash, bank, e-wallet, savings, credit card, investment, crypto, property, vehicle, pension, receivable), and balance                             | Displaying and managing financial accounts                           |
| **Transaction Notes**      | Optional note and description text attached to transactions                                                                                                       | User reference and context                                           |
| **Categories**             | Custom category names, icons, and colors used to classify transactions                                                                                            | Transaction categorization                                           |
| **Reminders**              | Notification schedules including label, time, and repeat days                                                                                                     | Local recurring notification feature                                 |
| **App Preferences**        | Language, currency, onboarding status, and other display preferences                                                                                              | Personalizing the user experience                                    |
| **App Lock**               | SHA-256 hash of your 6-digit PIN, biometric status, and last verification time                                                                                    | Locking access to the Application; the original PIN is not stored     |
| **Backup PIN**             | Optional 4–6 digit PIN you choose to protect encrypted backup files (used only to encrypt/decrypt the file; never stored by us)                                    | Securing your backup files                                           |

### 2.2 Information Collected Automatically

We **do not** collect usage analytics, crash reports, usage statistics, or telemetry data about how you use the Application. The in-app **Analytics** feature (financial score, trends, habit detection, and projections) is computed locally from your data and is never transmitted anywhere.

Kasiku displays ads served by **Google AdMob**. To serve ads, the Google Mobile Ads SDK may automatically process certain standard device and usage information, such as:

- Your device's advertising ID (which can be reset in your device settings)
- IP address and general (non-precise) location data, where permitted by your consent choices
- Device model, operating system version, and advertising identifiers
- Ad interactions (for example, whether an ad was viewed or clicked)

This information is collected and processed by **Google**, not by Yural Dev, and is used to deliver and measure advertisements in accordance with Google's Privacy Policy. Your financial data (transactions, assets, categories, notes, photos, and backups) is **never** shared with Google or any ad network.

In the European Economic Area (EEA), the United Kingdom, and Switzerland, the Application uses Google's **User Messaging Platform (UMP)** to request your consent before showing personalized ads. You can change or withdraw your consent choices at any time through your device settings.

For more information about how Google handles advertising data and how to opt out, please review:
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google Ads Settings](https://adssettings.google.com)

### 2.3 Information from Third Parties

The only third-party SDK integrated into Kasiku is the **Google Mobile Ads SDK** (AdMob), used solely to display banner and interstitial ads. As described in Section 2.2, this SDK operates under Google's own privacy policy and does not receive your financial data. Kasiku does not integrate any analytics, social media, or cloud collection services, and no other SDK collects or transmits data to third parties.

## 3. How We Use Your Information

All information stored in Kasiku is used solely to provide the Application's features:

- Recording and displaying financial transactions
- Calculating and displaying asset balances
- Generating financial summaries, charts, reports, and local analytics
- Providing data export in CSV, Excel, and PDF formats
- Creating and restoring encrypted JSON backups of your data (optionally protected by a PIN of your choice)
- Displaying and managing transaction photos you attach
- Locking access to the Application with a PIN and/or biometrics if you enable it
- Scheduling local notifications for reminders
- Storing your language and currency preferences
- Displaying ads through Google AdMob (see Section 2.2)

## 4. Data Storage and Security

### 4.1 Storage Locations

All financial data is stored locally on your device in:

- A **SQLite database** located in the app's private data directory, including transactions, assets, categories, reminders, preferences, and the app-lock PIN hash
- The **local file system** for transaction photos and backup files in the app's private documents folder

### 4.2 Data Security

- Your data in the Application's SQLite database **is not encrypted** at rest on the device.
- The Application offers an **optional app lock** using a 6-digit PIN and/or biometrics. The PIN is stored as a SHA-256 hash, not in plaintext. After successful verification, the Application remains unlocked for **2 hours**; verification is required again afterward. The app-lock PIN cannot be recovered if forgotten.
- The app lock is an **access control**, not database encryption. If the device is rooted, modified, or infected with malware, data may still be accessible. We recommend enabling your device's screen lock security.
- **Backup files are encrypted by default** using **AES-256-GCM**. The encryption key is derived from your backup PIN (if you choose one) or a built-in secret embedded in the Application, using **PBKDF2-HMAC-SHA256 with 100,000 iterations**.
- **Optional PIN protection**: when creating a backup, you may choose a 4–6 digit PIN. A PIN-protected backup can only be restored by entering that PIN; without it, the backup contents cannot be decrypted. We do not store your PIN anywhere — if you forget it, the backup cannot be recovered.
- Backups without a PIN are still encrypted, but the key is derived from a secret embedded in the Application. This is weaker than PIN-protected backups; use a backup PIN for sensitive data.
- Backups include financial data, preferences, and Application security settings (including the app-lock PIN hash). Restoring a backup may restore the app-lock settings stored in it. Backups **do not** include transaction photos or reminders.
- **Transaction photos** are stored in the Application's private documents folder and are not uploaded, exported, or included in backups. Deleting a transaction also deletes its photo files.
- Exported documents (CSV, Excel, PDF) are created as plain text files in your device's file system. Be careful when sharing or storing them.

### 4.3 Network Usage

- Kasiku does not perform cloud sync and does not connect to any Yural Dev server infrastructure.
- The only network connections the Application makes are to the **Google AdMob** advertising network to load and display ads (see Section 2.2). No financial data is sent over this connection.

### 4.4 Storage by Platform

| Platform | Storage Location          |
| -------- | ------------------------- |
| Android  | App internal storage      |

> **Note:** Kasiku is currently available for Android. Support for additional platforms (iOS, Web, Windows, Linux, macOS) will be provided in future updates. This policy will be updated accordingly.

## 5. Data Sharing and Disclosure

### 5.1 No Third-Party Sharing

Kasiku **does not share, sell, rent, or disclose your financial data to any third party**. The Application has no server infrastructure, and your financial data never leaves your device — except through actions you take yourself as described in Section 5.2. The only third-party network communication is ad loading through Google AdMob (see Section 2.2), which does not receive your financial data.

### 5.2 User-Initiated Sharing

You may choose to share your data through the following features, which require your explicit action:

- **Backup**: You can create a JSON backup file and choose to save or share it through the system share dialog. Backup files include financial data, preferences, and security settings, but do not include transaction photos or reminders.
- **Export**: You can export transactions as CSV, Excel, or PDF files, including analytics summaries in PDF, and share them through the system share dialog. Transaction photos are not exported.
- **File Sharing**: When sharing, files are handled by your device's native share sheet and are subject to the recipient application's privacy practices.

### 5.3 Legal Requirements

If we are required by law (such as a court order or valid subpoena) to disclose your information, we will make reasonable efforts to notify you unless prohibited by law. Because we do not store your financial data on our servers, we do not hold that data to disclose.

## 6. Data Retention and Deletion

### 6.1 Retention

Your data remains on your device for as long as you keep the Application installed and choose to retain it. The Application imposes no data retention limits.

### 6.2 Deletion

You can delete your data in the following ways:

- **Individual records**: Delete individual transactions, assets, categories, or reminders through the Application interface. Deleting a transaction also deletes its associated photos from Application storage.
- **Delete all data**: Uninstall the Application or clear the Application's data through your device settings to remove the database, transaction photos, and local preferences. Backup or export files you saved outside Application storage may remain unless manually deleted.
- **Backup files**: Delete backup files manually through the Application's Backup & Restore screen or your device's file manager.

### 6.3 Backup Data

Backup files created by the Application are encrypted (see Section 4.2) and remain on your device until you delete them manually. The Application keeps a backup history that can be cleared at any time. Deleting a backup history entry also deletes the related backup file from Application internal storage.

## 7. Your Rights

Depending on your jurisdiction, you may have the following rights regarding your personal data:

| Right                     | Description                                                                                              |
| ------------------------- | -------------------------------------------------------------------------------------------------------- |
| **Right of Access**       | You can view all your data within the Application at any time                                           |
| **Right to Correction**   | You can edit or correct any data through the Application                                                |
| **Right to Erasure**      | You can delete individual records or uninstall the Application to delete all data                       |
| **Right to Portability**  | You can export your data as JSON (backup), CSV, Excel, or PDF; transaction photos are not included       |
| **Right to Object**       | You can stop using the Application at any time                                                          |
| **Right to Withdraw**     | You can withdraw consent by uninstalling the Application or disabling the relevant feature               |

Because data is stored locally, you can exercise most of these rights directly through the Application's features. For other questions, contact us using the information below.

## 8. Children's Privacy

Kasiku is not intended for children under 13 years of age (or the applicable age of consent in your jurisdiction). We do not knowingly collect personal information from children. If you believe a child has provided personal data through the Application, please contact us so we can take appropriate action.

## 9. International Users

Your data is stored exclusively on your device and is not transferred across borders by us. However, Google's processing of advertising data may involve international transfers in accordance with Google's policies and safeguards. If you choose to share or export data, those actions are initiated and controlled by you. The Application is available worldwide and complies with applicable privacy laws in the jurisdictions where it is used, including:

- **GDPR** (European Economic Area)
- **CCPA/CPRA** (California, United States)
- **LGPD** (Brazil)
- **UU ITE** (Indonesia)
- **UU PDP** (Indonesia's Personal Data Protection Law No. 27 of 2022)

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be posted in the Application and/or on the Application's repository. The "Last updated" date at the top of this policy reflects the most recent changes.

Material changes will be communicated through the Application and/or the Application's repository. Continued use of the Application after changes constitutes acceptance of the updated policy.

## 11. Advertising and Your Choices

Kasiku is free to use and supported by ads served by **Google AdMob** (see Section 2.2 for details about advertising data and consent). Regarding ads:

- You do not need to accept personalized ads to use the Application.
- You can change or withdraw your consent choices at any time through your device settings.
- You can reset your Android advertising ID at any time in your device settings (Settings → Google → Ads), which limits the ability to link ads to your device profile.
- You can manage or opt out of personalized ads through [Google Ads Settings](https://adssettings.google.com).
- These choices do not affect your local financial data in any way.

## 12. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy, please contact us:

- **Developer**: Yural Dev
- **Email**: yuraldeveloper@gmail.com

---

_This Privacy Policy was prepared with reference to global privacy standards including the General Data Protection Regulation (GDPR), California Consumer Privacy Act (CCPA), and Indonesia's Personal Data Protection Law (PDP Law), as well as Google's advertising requirements._
