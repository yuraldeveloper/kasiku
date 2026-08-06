# Privacy Policy

**Last updated: August 6, 2026**

## 1. Introduction

Yural Dev ("we", "our", or "us") operates Kasiku (the "Application"), a personal finance tracking application. This Privacy Policy explains how we collect, use, store, and protect your information when you use our Application.

By using Kasiku, you agree to the practices described in this Privacy Policy. If you do not agree, please discontinue use of the Application.

## 2. Information We Collect

Kasiku is designed as a **privacy-first, local-first application**. All of your financial data is stored locally on your device. We do **not** collect, transmit, or store your financial data on external servers.

### 2.1 Information You Provide

The Application stores the following information locally on your device:

| Data Category              | Specific Data                                                                                                                             | Purpose                                             |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| **Financial Transactions** | Income, expense, and transfer records including amount, date, time, category, and associated assets                                       | Core app functionality — tracking personal finances |
| **Asset Information**      | Asset names, types (cash, bank, e-wallet, savings, credit card, investment, crypto, property, vehicle, pension, receivable), and balances | Displaying and managing financial accounts          |
| **Transaction Notes**      | Optional textual notes and descriptions attached to transactions                                                                          | User reference and context                          |
| **Categories**             | Custom category names, icons, and colors for classifying transactions                                                                     | Transaction categorization                          |
| **Reminders**              | Notification schedule including label, time, and repeat days                                                                              | Recurring notification feature                      |
| **App Preferences**        | Language selection, currency selection, and other display preferences                                                                     | Personalizing the user experience                   |
| **Backup PIN**             | A PIN you optionally choose to protect an encrypted backup file (used only to encrypt/decrypt that file; never stored by us)               | Securing your backup files                         |

### 2.2 Information Collected Automatically

We do **not** collect analytics, crash reports, usage statistics, or telemetry data about how you use the Application.

Kasiku displays advertisements served by **Google AdMob**. To serve ads, the Google Mobile Ads SDK may automatically process certain standard device and usage information, such as:

- Your device's advertising ID (resettable via your device settings)
- IP address and general (non-precise) location data, where permitted by your consent choices
- Device model, operating system version, and ad identifiers
- Interaction with ads (e.g., whether an ad was viewed or clicked)

This information is collected and processed by **Google**, not by Yural Dev, and is used to deliver and measure advertisements in accordance with Google's Privacy Policy. Your financial data (transactions, assets, categories, notes, and backups) is **never** shared with Google or any ad network.

In the European Economic Area (EEA), United Kingdom, and Switzerland, the Application uses Google's **User Messaging Platform (UMP)** to request your consent before personalized ads are served. You can change or withdraw your consent choices at any time through your device's settings.

For more information about how Google handles advertising data and how to opt out, please review:
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google Ad Settings](https://adssettings.google.com)

### 2.3 Information from Third Parties

The only third-party SDK integrated into Kasiku is the **Google Mobile Ads SDK** (AdMob), used solely to display banner and interstitial advertisements. As described in Section 2.2, this SDK operates under Google's own privacy policy and does not receive any of your financial data. Kasiku does not integrate with any analytics, social media, or cloud storage services, and no other SDKs collect or transmit data to third parties.

## 3. How We Use Your Information

All information stored in Kasiku is used solely for the purpose of providing the Application's features:

- Recording and displaying financial transactions
- Calculating and displaying asset balances
- Generating financial summaries, charts, and reports
- Providing data export in CSV, Excel, and PDF formats
- Creating and restoring encrypted JSON backups of your data (optionally protected by a PIN of your choosing)
- Scheduling local push notifications for reminders
- Remembering your language and currency preferences
- Displaying advertisements via Google AdMob (see Section 2.2)

## 4. Data Storage and Security

### 4.1 Storage Location

All financial data is stored locally on your device in:

- A **SQLite database** located in the application's private data directory
- **Shared Preferences** for lightweight key-value settings
- The **local file system** for backup and exported documents

### 4.2 Data Security

- Your data in the application's SQLite database is **not encrypted at rest** on the device's storage.
- The Application does **not** implement device authentication (PIN, password, or biometric) to open the app itself.
- Anyone with physical access to your unlocked device may be able to view your financial data. We recommend enabling your device's own lock screen security.
- **Backup files are encrypted by default** using the **AES-256-GCM** algorithm. The encryption key is derived from your PIN (if you choose one) or a built-in secret, using **PBKDF2-HMAC-SHA256 with 100,000 iterations**.
- **Optional PIN protection**: when creating a backup, you may choose a 4–6 digit PIN. Backups protected by a PIN can only be restored by entering that PIN; without it, the backup content cannot be decrypted. We do not store your PIN anywhere — if you forget it, the backup cannot be recovered.
- Exported documents (CSV, Excel, PDF) are created as plaintext files on your device's file system. Be mindful when sharing or storing them.

### 4.3 Network Use

- Kasiku does not run cloud synchronization or connect to any Yural Dev server infrastructure.
- The only network connections the Application makes are to the **Google AdMob** ad network to load and display advertisements (see Section 2.2). No financial data is transmitted over these connections.

### 4.4 Platform-Specific Storage

| Platform | Storage Location             |
| -------- | ---------------------------- |
| Android  | Application internal storage |

> **Note:** Kasiku is currently available for Android. Support for additional platforms (iOS, Web, Windows, Linux, macOS) will be addressed in future updates. This policy will be updated accordingly as new platforms are supported.

## 5. Data Sharing and Disclosure

### 5.1 No Third-Party Sharing

Kasiku **does not share, sell, rent, or disclose your financial data to any third parties**. The Application has no server infrastructure, and your financial data never leaves your device — except through user-initiated actions described in Section 5.2. The only third-party network communication is the loading of advertisements via Google AdMob (see Section 2.2), which does not receive any of your financial data.

### 5.2 User-Initiated Sharing

You may choose to share your data through the following features, which require your explicit action:

- **Backup**: You can create a JSON backup file and choose to save or share it via the system share dialog.
- **Export**: You can export transactions as CSV, Excel, or PDF files and share them via the system share dialog.
- **File Sharing**: When sharing, the file is handled by your device's native share sheet and is subject to the privacy practices of the receiving application.

### 5.3 Legal Requirements

If we are required by law (such as a valid court order or subpoena) to disclose your information, we will make reasonable efforts to notify you, unless prohibited by law.

## 6. Data Retention and Deletion

### 6.1 Retention

Your data remains on your device for as long as you keep the Application installed and choose to retain the data. The Application does not enforce any data retention limits.

### 6.2 Deletion

You can delete your data in the following ways:

- **Individual records**: Delete individual transactions, assets, categories, or reminders through the Application interface.
- **Full data wipe**: Uninstall the Application to remove all associated local data. Note that backup files created prior to uninstallation may remain on your device's file system unless manually deleted.
- **Backup files**: Manually delete backup files through the Application's Backup & Restore screen or via your device's file manager.

### 6.3 Backup Data

Backup files created through the Application are encrypted (see Section 4.2) and remain on your device until you manually delete them. The Application maintains a backup history log that can be cleared at any time.

## 7. Your Rights

Depending on your jurisdiction, you may have the following rights regarding your personal data:

| Right                         | Description                                                                       |
| ----------------------------- | --------------------------------------------------------------------------------- |
| **Right of Access**           | You can view all your data within the Application at any time                     |
| **Right to Rectification**    | You can edit or correct any data through the Application                          |
| **Right to Deletion**         | You can delete individual records or uninstall the Application to remove all data |
| **Right to Data Portability** | You can export your data as JSON (backup), CSV, Excel, or PDF                     |
| **Right to Object**           | You can stop using the Application at any time                                    |
| **Right to Withdraw Consent** | You can withdraw consent by uninstalling the Application                          |

To exercise any of these rights, you may use the features available within the Application or contact us using the information below.

## 8. Children's Privacy

Kasiku is not directed at children under the age of 13 (or the applicable age of consent in your jurisdiction). We do not knowingly collect personal information from children. If you believe a child has provided personal data through the Application, please contact us so we can take appropriate action.

## 9. International Users

Your data is stored exclusively on your device and is not transferred across borders by us. However, if you choose to share or export data, such actions are initiated and controlled by you. The Application is available worldwide and complies with applicable privacy laws in the jurisdictions where it is used, including:

- **GDPR** (European Economic Area)
- **CCPA/CPRA** (California, United States)
- **LGPD** (Brazil)
- **UU ITE** (Indonesia)
- **PDP Law** (Indonesia Law No. 27 of 2022 on Personal Data Protection)

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Changes will be posted in the Application and/or on the Application's repository. The "Last updated" date at the top of this policy reflects the most recent changes.

Material changes will be communicated through the Application (e.g., via the consent form shown on first launch). Continued use of the Application after changes constitutes acceptance of the updated policy.

## 11. Advertising and Your Choices

Kasiku is free to use and is supported by advertisements served by **Google AdMob** (see Section 2.2 for details on ad data and consent). Regarding ads:

- You do not need to accept personalized ads to use the Application.
- You can change or withdraw your consent choices at any time through your device's settings.
- You can reset your Android advertising ID at any time in your device's settings (Settings → Google → Ads), which limits the ability to link your device to ad profiles.
- You can manage or opt out of personalized advertising through [Google Ad Settings](https://adssettings.google.com).
- These choices do not affect your local financial data in any way.

## 12. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy, please contact us:

- **Developer**: Yural Dev
- **Email**: yuraldeveloper@gmail.com

---

_This Privacy Policy was prepared with reference to global privacy standards including the General Data Protection Regulation (GDPR), California Consumer Privacy Act (CCPA), and Indonesia's Personal Data Protection Law (PDP Law), as well as Google's advertising requirements._
