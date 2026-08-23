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

This section describes the **categories** of information LinkUp holds. It is a description of categories, not an exhaustive list of every individual field: the specific items within a category change as the App changes.

### 2.1 Information You Provide or Create

- **Account and identity information** — The name, username, email address, and/or phone number you register with; your password, which we store only as a cryptographic hash and never in readable form; your date of birth, which we use to apply the minimum age requirement and to determine whether you are old enough to be shown personalized advertising; and a record of the versions of these policies you have agreed to and when.
- **Content you create and share** — Groups you create or join and their names, descriptions and join codes; events, including their titles, dates, details and locations; group chat messages; direct messages; polls, reactions, replies and event tags; your RSVP responses; and event invitations, pings and reminders.
- **Reports, feedback and support requests** — Reports you submit about another user or a piece of content, including anything you write and a copy of the content being reported; and any feedback or support request you send us, including diagnostic logs if you choose to attach them.
- **Settings and preferences** — Your notification preferences, per-group mute settings, privacy toggles and advertising choices. These are held on our servers rather than only on your device, because they have to be applied before anything is sent to you.

### 2.2 Information Collected Automatically

- **Device and app information** — Device model, iOS version and app version; your Apple Push Notification Service (APNs) device token, used to deliver push notifications; and a persistent identifier for your device provided by iOS, which we record when you register and use to prevent a banned or suspended account from immediately signing up again on the same device.
- **Connection information** — IP address, connection timestamps, and WebSocket connection metadata.
- **In-app activity needed to operate features** — Which chat messages and events you have already seen, so unread counts and "new" badges are accurate, and when your device was last active.
- **Safety and enforcement records** — Sign-in attempts (the identifier used and the originating IP address), IP addresses seen on your account, warnings and posting restrictions issued to you, blocks you place on other users, and the outcome of reports involving you. Message content is also screened automatically for slurs, hate speech and threats; see Section 3.
- **Error and diagnostic data** — Technical information about App and server errors and crashes, so we can diagnose and fix faults.
- **Purchase and advertising records** — The Apple transaction identifier for a Remove Ads purchase (we never receive your payment details) and a record of which ads were shown to you.

### 2.3 Information Collected Through Device Permissions

We request the following device permissions and use each for the purposes described below:

| Permission | What We Access | How It's Used |
|---|---|---|
| **Camera** | Camera viewfinder only | Scan circular group join codes. No images are captured, stored, or transmitted. |
| **Location (When In Use)** | Precise location, only while the App is open | Center the map on where you are when you are choosing a location for an event, and show how far away an event is on its detail screen. A location you choose becomes part of that event and is shared with the group you create it in. Coordinates and addresses are sent to Apple's mapping and geocoding services to convert between the two. Not collected in the background, never sent to our advertising partner, and never sold. You can limit the App to an approximate position by turning off **Precise Location** in iOS Settings → Privacy & Security → Location Services → LinkUp. |
| **Calendar (Full Access)** | Your calendar events, and the ability to add an event to your calendar | Display your personal events alongside group events in the Calendar tab, warn you when an event you are responding to clashes with something already in your calendar, and save an event to your calendar when you choose Add to Calendar. Full access is requested because saving an event requires write access while clash and duplicate checking require read access. Your calendar data is never sent to our servers. |
| **Notifications** | Push notification delivery | Send you alerts about group chat and direct messages, new, changed and cancelled events, RSVPs, join requests and approvals, and reminders. |

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
- **Improve the App** — Analyze error and crash reports, and the feedback you send us, to find and fix faults and improve features
- **Enforce our Terms of Service** — Detect and prevent abuse, fraud, and violations. This includes screening group chat messages, direct messages, and the names and descriptions you give to groups, events and your profile automatically for slurs, hate speech and threats before they are posted, and reviewing reports submitted by other users. See Section 5.4 of the Terms of Service.
- **Comply with legal obligations** — Respond to lawful requests from authorities where required
- **Serve advertising** — If you have not removed ads, display relevant advertisements via Google AdMob

We do not sell your personal information to third parties.

---

## 4. How We Store Your Information

### 4.1 Server Storage

Your account data, group data, event data, chat messages, direct messages, and your settings and preferences are stored on our servers hosted via Render. Event location data is stored in **encrypted form** using `pgp_sym_encrypt` (pgcrypto) and is decrypted only when delivered to authorized group members.

### 4.2 On-Device Storage

The following data is stored locally on your device:

- **JWT authentication token** — Stored securely in the iOS Keychain (encrypted by the OS). Used to authenticate your requests to our server. Expires after 7 days.
- **Cached groups, events, and profile data** — Stored in Core Data on your device for offline browsing. This cache is cleared when you log out.
- **Calendar events** — Never stored by us; read locally from iOS Calendar only

### 4.3 Retention

We keep your account for as long as it is open. Several categories of content and records are deleted automatically on a fixed schedule, whether or not your account is active:

| What | How long we keep it |
|---|---|
| Group chat messages | 30 days. We also keep only the 1,000 most recent messages in any one group. |
| Direct messages | 365 days. We also keep only the 5,000 most recent messages in any one conversation. A message you delete is purged 30 days later. |
| Events | 30 days after the event ends. |
| Groups that are disbanded or removed | 30 days, after which the group and everything in it is permanently deleted. |
| In-app notifications | 90 days, or 30 days after you read them, whichever comes first. |
| Reports | 180 days after the report is reviewed or dismissed. |
| Feedback and support requests | 30 days after we close them; 365 days if they are still open. |
| IP addresses seen on your account | 180 days after they were last seen. |
| Sign-in and join attempt records | 24 hours for sign-in attempts; 7 days for group join attempts. |
| Advertising impression records | 90 days. |
| Error and diagnostic logs | 30 days for server errors; 60 days for errors reported by the App. |
| Security and administrative action records | 180 days. |

These are maximums, not guarantees. Content can be removed sooner — by you, by a group admin, or by us for a violation of the Terms of Service.

When you delete your account, deletion happens in two stages:

- **Immediately.** Your account is closed and you are signed out. You can no longer sign in, post, or be contacted through the App.
- **Immediately.** If you owned a group that still has other members, ownership transfers to the most senior remaining member so the group is not left without an owner.
- **For 30 days.** Your account and its associated data are retained in this closed state. During this period the deletion can be reversed if you contact us — see Section 7.6.
- **After 30 days.** Your account and associated personal data are permanently deleted from our servers and cannot be recovered.
- Backups may retain data for a limited period after deletion.

**Three things survive account deletion.** If another user reported your content, the report — including the copy of the reported content saved with it — is kept for the report retention period shown above; your account identifiers are removed from it when your account is deleted. Records of an in-app purchase are kept with your account identifier removed, so that purchase and refund records remain complete. Error and diagnostic records are likewise stripped of your identifier rather than deleted, and age out on the schedule above.

---

## 5. How We Share Your Information

We do not sell your personal information. We share information only in the following circumstances:

### 5.1 With Other Users

Information you choose to share within the App is visible to other users according to the following rules:

- **Profile** — Your name and username are visible to members of groups you belong to
- **Email / Phone** — Visible to group members only if you have enabled this in Privacy Settings
- **Events** — Event details, including location and RSVP responses, are visible to all members of the group the event belongs to
- **Chat messages** — Visible to all members of the group chat
- **Direct messages** — Visible only to the one other person in the conversation. If you block someone, your messages stop being delivered to them and theirs are hidden from you.

### 5.2 With Service Providers

We share data with trusted third-party service providers who assist us in operating the App, under strict confidentiality agreements:

- **Google AdMob** — Advertising (only if ads are enabled)
- **Apple APNs** — Push notification delivery
- **Apple Maps / geocoding** — Converting between coordinates and addresses when you choose or view an event location
- **Render** — Secure server infrastructure

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
You can revoke location access at any time in **iOS Settings → Privacy & Security → Location Services → LinkUp**. In the same place you can turn off **Precise Location**, which leaves the App with only an approximate position. Location is used when you are choosing a location for an event and when you open an event's detail screen, where it is used to show how far away the event is. It is not collected while the App is closed or in the background. A location you choose for an event becomes part of that event and is visible to the members of the group it belongs to.

### 7.6 Account Deletion
You can delete your account at any time from **Profile → Help & Support → Delete Account**. Your account is closed immediately and you are signed out.

**30-day recovery window.** For 30 days after you delete your account, we keep it in a closed state so the deletion can be reversed if you change your mind or deleted it by mistake. To request restoration, email us at hello.linkupapp@gmail.com from the address on the account. After 30 days the account and its data are permanently deleted and cannot be recovered.

Two things to know about restoration:

- **Groups you owned are not returned.** Ownership transfers to another member the moment you delete, so that group members are not left without an owner. Restoring your account does not take that ownership back.
- **Creating a new account with the same email or phone number ends the window early.** If you sign up again with the same details before the 30 days are up, your previous account is permanently deleted at that point and can no longer be restored.

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
