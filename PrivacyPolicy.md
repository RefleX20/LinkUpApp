# LinkUp — Privacy Policy

**Effective Date:** March 13, 2026
**Last Updated:** March 13, 2026

---

## 1. Introduction

LinkUp ("Company," "we," "us," or "our") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use the LinkUp mobile application ("App").

**We reserve the right to modify this Privacy Policy at any time.** When we make changes, we will update the "Last Updated" date above. Your continued use of the App after any modification constitutes your acceptance of the updated Privacy Policy. Please review this policy periodically.

If you do not agree with this Privacy Policy, please do not use the App.

---

## 2. Information We Collect

### 2.1 Information You Provide Directly

- **Account Information** — Name, username, email address, and/or phone number when you register
- **Profile Information** — Any updates you make to your profile (name, username, email)
- **Group Content** — Group names, descriptions, join codes you create or participate in
- **Event Content** — Event titles, dates, details, and locations you enter when creating or editing events
- **Chat Messages** — Messages, reactions, replies, event tags, and polls you send in group chats
- **RSVP Responses** — Your Going / Maybe / Not Going responses to events
- **Device Token** — Your Apple Push Notification Service (APNs) device token, used to deliver push notifications to your device

### 2.2 Information Collected Automatically

- **Usage Data** — How you interact with the App (features used, screens visited, actions taken)
- **Device Information** — Device model, iOS version, app version, device language
- **Connection Data** — IP address, connection timestamps, WebSocket connection metadata
- **Crash and Error Data** — Technical information about App errors and crashes to help us diagnose issues

### 2.3 Information Collected Through Device Permissions

We request the following device permissions, each used only for the stated purpose:

| Permission | What We Access | How It's Used |
|---|---|---|
| **Camera** | Camera viewfinder only | Scan circular group join codes. No images are captured, stored, or transmitted. |
| **Location (When In Use)** | Approximate location | Center the map picker when you choose an event location. Not tracked in background, not shared with third parties. |
| **Calendar (Full Access)** | Your calendar events | Display your personal events alongside group events in the Calendar tab. Personal Calendar event times only may leave your device with your express permission. Other calendar data like location, name, etc. is never sent to our servers. |
| **Notifications** | Push notification delivery | Send you alerts about new events, RSVPs, join approvals, and reminders. |

### 2.4 Information from Third-Party Advertising

If you have not purchased the Remove Ads option, our advertising partner Google AdMob may collect:

- Advertising identifiers (IDFA, if you grant tracking permission via Apple's App Tracking Transparency prompt)
- Approximate location (country/region level)
- Device and app information used to serve relevant ads

Google AdMob's privacy practices are governed by [Google's Privacy Policy](https://policies.google.com/privacy).

---

## 3. How We Use Your Information

We use the information we collect to:

- **Provide and operate the App** — Create and manage your account, groups, events, and chats
- **Deliver push notifications** — Notify you about group activity, events, RSVPs, and reminders
- **Personalize your experience** — Apply your notification and in-app preferences
- **Process purchases** — Verify your in-app purchase of Remove Ads via Apple's StoreKit
- **Improve the App** — Analyze usage patterns and errors to fix bugs and improve features
- **Enforce our Terms of Service** — Detect and prevent abuse, fraud, and violations
- **Comply with legal obligations** — Respond to lawful requests from authorities where required
- **Serve advertising** — If you have not removed ads, display relevant advertisements via Google AdMob

We do not sell your personal information to third parties.

---

## 4. How We Store Your Information

### 4.1 Server Storage

Your account data, group data, event data, and chat messages are stored on our servers hosted via Render. Event location data is stored in **encrypted form** using `pgp_sym_encrypt` (pgcrypto) and is decrypted only when delivered to authorized group members.

### 4.2 On-Device Storage

The following data is stored locally on your device:

- **JWT authentication token** — Stored securely in the iOS Keychain (encrypted by the OS). Used to authenticate your requests to our server. Expires after 7 days.
- **Cached groups, events, and profile data** — Stored in Core Data on your device for offline browsing. This cache is cleared when you log out.
- **Notification preferences** — Stored in iOS app storage (UserDefaults)
- **Calendar events** — Never stored by us; read locally from iOS Calendar only

### 4.3 Retention

We retain your account data for as long as your account is active. If you delete your account:

- Your profile, groups you owned (if no other members remain), and personal data are deleted from our servers
- Groups you owned with other members will have ownership transferred to the most senior member
- Chat messages may be retained in a soft-deleted state for up to 30 days before permanent deletion
- Backups may retain data for a limited period after deletion

---

## 5. How We Share Your Information

We do not sell your personal information. We share information only in the following circumstances:

### 5.1 With Other Users

Information you choose to share within the App is visible to other users according to the following rules:

- **Profile** — Your name and username are visible to members of groups you belong to
- **Email / Phone** — Visible to group members only if you have enabled this in Privacy Settings
- **Events** — Event details, including location and RSVP responses, are visible to all members of the group the event belongs to
- **Chat messages** — Visible to all members of the group chat

### 5.2 With Service Providers

We share data with trusted third-party service providers who assist us in operating the App, under strict confidentiality agreements:

- **Google AdMob** — Advertising (only if ads are enabled)
- **Apple APNs** — Push notification delivery
- **Database / Hosting Provider** — Secure server infrastructure

### 5.3 For Legal Reasons

We may disclose your information if we believe in good faith that disclosure is necessary to:

- Comply with applicable law, regulation, or legal process
- Protect the rights, property, or safety of LinkUp, our users, or the public
- Detect, prevent, or address fraud or security issues

### 5.4 Business Transfers

If LinkUp is involved in a merger, acquisition, or sale of assets, your information may be transferred as part of that transaction. We will notify you via email or a prominent notice in the App before your information is transferred and becomes subject to a different privacy policy.

---

## 6. Apple App Tracking Transparency (ATT)

In accordance with Apple's App Tracking Transparency framework, we will ask for your permission before tracking your activity across other companies' apps and websites for advertising purposes. If you decline, you will still see ads, but they will not be personalized based on cross-app tracking. You can change your tracking preference at any time in **iOS Settings → Privacy & Security → Tracking**.

---

## 7. Your Privacy Choices and Rights

### 7.1 Notification Preferences
You can manage push notification settings within the App under **Profile → Notifications**, or through **iOS Settings → Notifications → LinkUp**.

### 7.2 Per-Group Notification Preferences
You can mute event notifications or chat notifications for individual groups through **Group Settings → Notifications**. Muted preferences are stored on our server and prevent push notifications from being sent for that group.

### 7.3 Ad Tracking
You can opt out of personalized advertising by:
- Selecting "Ask App Not to Track" when prompted by the ATT dialog
- Going to **iOS Settings → Privacy & Security → Tracking** and disabling tracking for LinkUp
- Purchasing the **Remove Ads** in-app purchase

### 7.4 Calendar Access
You can revoke calendar access at any time in **iOS Settings → Privacy & Security → Calendars → LinkUp**. This will only affect the Calendar tab; all other App features remain functional.

### 7.5 Location Access
You can revoke location access at any time in **iOS Settings → Privacy & Security → Location Services → LinkUp**. Location is only used when you are actively picking an event location.

### 7.6 Account Deletion
You can delete your account at any time from **Profile → Help & Support → Delete Account**. Deletion is permanent and cannot be undone.

### 7.7 Rights for EEA / UK Users (GDPR)
If you are located in the European Economic Area or United Kingdom, you have the following rights under the General Data Protection Regulation (GDPR):

- **Right of Access** — Request a copy of the personal data we hold about you
- **Right to Rectification** — Request correction of inaccurate personal data
- **Right to Erasure** — Request deletion of your personal data ("right to be forgotten")
- **Right to Restriction** — Request that we restrict processing of your data
- **Right to Data Portability** — Request your data in a structured, machine-readable format
- **Right to Object** — Object to processing of your data for direct marketing or legitimate interests
- **Right to Withdraw Consent** — Where processing is based on consent, withdraw it at any time

To exercise any of these rights, contact us at hello.linkupapp@gmail.com. We will respond within 30 days.

Our legal basis for processing your data is:
- **Contract** — Processing necessary to provide you with the App's services
- **Legitimate Interests** — App security, fraud prevention, and service improvement
- **Consent** — Push notifications, ad tracking (where applicable)

### 7.8 Rights for California Users (CCPA / CPRA)
If you are a California resident, you have the following rights under the California Consumer Privacy Act:

- **Right to Know** — Request disclosure of the categories and specific pieces of personal information we collect, use, and share
- **Right to Delete** — Request deletion of your personal information (subject to certain exceptions)
- **Right to Correct** — Request correction of inaccurate personal information
- **Right to Opt-Out of Sale or Sharing** — We do not sell personal information. We do share limited data with advertising partners; you may opt out via the ATT prompt or iOS Settings.
- **Right to Non-Discrimination** — We will not discriminate against you for exercising your privacy rights

To exercise your California privacy rights, contact us at hello.linkupapp@gmail.com or use the in-app account deletion feature.

---

## 8. Children's Privacy

The App is not directed to children under the age of 13. We do not knowingly collect personal information from children under 13. If we become aware that we have inadvertently collected personal information from a child under 13, we will take steps to delete that information promptly. If you believe we have collected information from a child under 13, please contact us immediately at hello.linkupapp@gmail.com.

---

## 9. Security

We implement reasonable technical and organizational measures to protect your information, including:

- **Keychain storage** for authentication tokens on-device
- **Encrypted storage** for event location data on our servers (pgcrypto)
- **HTTPS/TLS** for all data in transit (in production)
- **JWT authentication** with 7-day expiry for API access
- **Rate limiting** on all API endpoints to prevent abuse
- **Bcrypt password hashing** (14 rounds)

No method of transmission over the internet or electronic storage is 100% secure. We cannot guarantee absolute security of your information.

---

## 10. Third-Party Links and Services

The App may contain links to third-party websites or services (e.g., Waze for directions). We are not responsible for the privacy practices of those third parties. We encourage you to review the privacy policies of any third-party services you access.

---

## 11. International Data Transfers

Your information may be stored and processed in the United States or any other country where our service providers operate. By using the App, you consent to the transfer of your information to countries outside your country of residence, including the United States, which may have different data protection rules than your country.

For EEA/UK users, where we transfer personal data outside the EEA/UK, we ensure appropriate safeguards are in place in accordance with applicable data protection law.

---

## 12. Changes to This Privacy Policy

We reserve the right to update this Privacy Policy at any time without prior notice. When we make material changes, we will update the "Last Updated" date at the top of this policy. We encourage you to review this policy whenever you use the App.

Your continued use of the App after changes to this Privacy Policy constitutes your acceptance of those changes.

---

## 13. Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

**LinkUp Support**
Email: hello.linkupapp@gmail.com

For GDPR-related inquiries, you may also lodge a complaint with your local data protection authority.

---

*This Privacy Policy was last updated on March 13, 2026.*
