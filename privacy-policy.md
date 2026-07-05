Privacy Policy
Last updated: July 5, 2026

Questly ("Questly", "we", "us") is a chore and rewards app for families. This Privacy Policy explains what information we collect, how we use it, and the choices you have — with particular attention to information about children, since Questly is used by parents and caregivers to manage chores for the kids in their household.

Questly is local-first: everything you enter lives in an encrypted database on your own device by default. Cloud features (cross-device sync, photo hand-off between a child's device and a parent's device, and push alerts) are optional and only activate if a parent signs in.

1. Information We Collect
1.1 Account information (parent/caregiver only)
Children do not create their own account. If a parent chooses to enable Cloud Backup or link a second device, we collect:

Email address, and name if provided via email/password sign-up, or
The name and email Apple or Google share with us when you use "Sign in with Apple" or "Sign in with Google" (subject to whatever you've chosen to share with those providers), and
Authentication tokens needed to keep you signed in.
1.2 Family and child profile data
Chore lists, assignment schedules, completion history, points, streaks, reward goals, and each child's profile (name, chosen avatar emoji, and optional accessibility/condition settings such as ADHD, autism, anxiety, or dyslexia preferences used only to adjust the app's wording, pacing, and visual style for that child) are entered by the parent and stored on-device. If Cloud Backup is enabled, this same data is synced to our database under the parent's authenticated account so it can be restored on a new device or shared across a family's devices.

1.3 Chore-completion photos
Questly can ask a child to take a photo as proof a chore is done. Specifically:

The camera is used to capture the photo directly — Questly never requests access to your device's photo library, and photos are not saved to your camera roll.
The photo is encrypted on the child's device (AES-256) before it is ever transmitted.
If the child and parent use separate devices, the encrypted photo passes through a private cloud storage bucket solely so it can travel from one device to the other. The decryption key is stored separately (in our database, protected so that only the authenticated parent account for that family can retrieve it) and the photo is decrypted only on the parent's device for review.
Important: this is encryption in transit and at rest, isolated per family by access controls — it is not end-to-end encryption, because the key is held server-side rather than solely on-device.
The photo is deleted automatically: immediately once a parent approves or rejects the chore, or automatically within about 12–24 hours if no action is taken. We do not view, analyze, or use these photos for any purpose other than letting a parent review the specific chore it was submitted for, and no photo is retained beyond that window.
If a child and parent share a single device, the photo never leaves that device at all.
1.4 Push notifications
If a child taps "I need help" or a chore approval is waiting, we send a push notification directly to the parent's registered device via Apple's push notification service. We store the minimum device token needed to deliver that alert. We do not use push notifications for marketing.

1.5 Purchases and subscriptions
Questly offers an optional paid "Family Plan" and optional one-time tips, sold as in-app purchases through the Apple App Store or Google Play. Purchases are processed by Apple/Google and by RevenueCat, our subscription-management provider — we never see or store your payment card details. RevenueCat receives a per-user identifier and purchase/ transaction information needed to activate your entitlements and to process restores.

1.6 Diagnostics and crash reports
Some builds of Questly may use Sentry to automatically capture crash reports and errors so we can fix bugs. This can include device model, OS version, app version, and technical error details. It is used only for troubleshooting, never for advertising or profiling.

1.7 What we do not do
No advertising SDKs and no ad identifiers are used.
No analytics or behavioral-tracking SDKs are embedded in the app.
We do not access your photo library, contacts, or location.
We do not sell personal information, and we do not share it with third parties for their own advertising or marketing purposes.
2. How We Use Information
To provide the app's core functionality (chores, points, goals, reminders).
To sync a family's data across the devices a parent has signed into, if Cloud Backup is on.
To relay a chore-completion photo from a child's device to a parent's device for review.
To send the specific push alerts described above.
To process purchases and manage subscription entitlements.
To diagnose crashes and keep the app secure and reliable.
To respond to support requests you send us.
3. Children's Privacy (COPPA / UK Age Appropriate Design Code / "GDPR-K")
Questly is designed to be used by a parent or caregiver for the children in their household — not directly by children as independent users:

The account holder is always the adult parent/caregiver. Children do not register, do not provide information to us directly, and do not see ads or third-party content.
Information about a child (name, avatar, chore history, accessibility preferences, completion photos) is entered by the parent and, by default, never leaves the family's own device(s). It only reaches our servers if the parent actively enables Cloud Backup or multi-device sync.
A parent can view, export (via the in-app CSV export, where available on the Family Plan), or delete their family's data at any time, including by contacting us at the address below.
We do not knowingly collect personal information directly from children under 13 (or the relevant age in your region), and we do not use any child's information for advertising or marketing.
4. Cloud Backup (Optional)
Cloud Backup is off unless a parent turns it on. When enabled, family data is stored in our database (hosted with our infrastructure provider, Supabase) under the parent's authenticated account, protected by row-level access rules so that only that family's signed-in parent account can read or write its data. Data in transit is protected with TLS encryption. A parent can disable Cloud Backup at any time from Settings → Cloud Backup; this stops future syncing but does not by itself delete data already stored — to request full deletion, contact us (see Section 9).

5. Local-First Design
By default, all chore, points, goal, and profile data lives in an encrypted local database on your device and the app works fully offline. Cloud features are additive and never required to use Questly.

6. Data Retention
Data	Retention
Chore-completion photos	Deleted on approval/rejection (typically seconds), or automatically within ~12–24 hours regardless
Local on-device data	Until you delete the app or clear its data
Cloud Backup data	Until you request deletion or close your account
Crash/diagnostic logs	Retained by our diagnostics provider only as long as needed to investigate an issue
7. Who We Share Information With
We do not sell your data. We use the following service providers ("processors") to operate Questly, each of which only receives what it needs to perform its function:

Supabase — database, authentication, file storage, and backend functions for Cloud Backup and cross-device photo hand-off.
Apple — Sign in with Apple, push notification delivery, and App Store payment processing.
Google — Google Sign-In, and Google Play payment processing where applicable.
RevenueCat — subscription and purchase entitlement management.
Sentry — optional crash/error diagnostics.
We may also disclose information if required by law, or to protect the rights, safety, or property of Questly, our users, or others.

8. International Data Transfers
Our service providers may process and store data in countries other than your own, including the United States. Where required, we rely on appropriate safeguards (such as standard contractual clauses) for these transfers.

9. Your Rights and Choices
Depending on where you live, you may have the right to access, correct, export, or delete your personal information, and to object to or restrict certain processing. You can exercise most of these rights directly in the app (Settings → Family Data), or by emailing nmtrade2018@gmail.com. We will respond within 30 days.

9.1 California Residents (CCPA/CPRA)
We do not sell or "share" (as those terms are defined under California law) personal information, and we do not use it for cross-context behavioral advertising.

9.2 UK / European Economic Area (GDPR)
Where GDPR or UK GDPR applies, our legal bases for processing are: performance of a contract (providing the app and Family Plan you've subscribed to), consent (Cloud Backup, push notifications), and legitimate interests (crash diagnostics, keeping the service secure). You have the right to lodge a complaint with your local data protection supervisory authority (in the UK, the ICO).

10. Security
We use encryption in transit (TLS) and at rest, on-device encryption for the local database, and access controls that scope cloud data to the authenticated family account. No method of transmission or storage is 100% secure, and we cannot guarantee absolute security.

11. Changes to This Policy
We may update this policy from time to time. If we make a material change, we'll update the "Last updated" date above and, where appropriate, notify you in the app.

12. Contact Us
Questions about this policy, or requests to access or delete your data, can be sent to nmtrade2018@gmail.com.

Questly · Family-first, privacy-first.
