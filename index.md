# Ashrim Run Privacy Policy

Effective August 9, 2026

Ashrim Run is designed to work on-device first. If you choose Sign in with Apple, it also creates a private account and encrypted-in-transit backup using Supabase so your information can be recovered after reinstalling or changing phones. The app does not include advertising or analytics SDKs, sell personal information, or use information for tracking.

## Information handled by the app

- Profile, training, event, goal, route, and workout information is stored locally on your device. When you sign in with Apple, these categories are also copied to your private account backup.
- With your permission, Ashrim Run reads and writes running workouts and routes through Apple Health. Apple Health controls those permissions and stores the Health records.
- During an outdoor workout, Ashrim Run uses location to calculate and preserve distance, pace, and route. The iPhone app can continue this use in the background while a workout is active. Signed-in users' completed route coordinates are included in their private recovery backup. Routes can also leave the app when you deliberately export or share them.
- If you use Sign in with Apple, Apple provides an identity token and may provide your name or relay email. Ashrim Run exchanges that token with Supabase, stores the resulting session securely in the device Keychain, and associates your private backup with the resulting account ID. Ashrim Run never receives your Apple password.
- Photo Library access is used only when you ask to save a run card. Notification permission is used only for reminders and workout notices you enable.

## Sharing and third parties

Signed-in recovery data is processed and hosted by Supabase solely to provide authentication and backup functionality. Row-level security restricts each backup to its authenticated account. Ashrim Run does not share that data with advertising, analytics, or data-broker services. Information may also leave the app through an action you choose, such as sharing a run card, exporting GPX, saving to Photos, or writing an authorized workout to Apple Health. Apple and Supabase services are governed by their respective privacy and security terms.

## Retention, deletion, and choices

Local information remains until you delete the relevant item or remove the app. The private backup remains while the cloud account exists so it can fulfill recovery. You can delete saved workouts and goals in the app and can reset your profile setup without erasing workout history. Logging out removes the local session but does not delete the backup. Profile → Account → Permanently Delete Account deletes the authenticated Supabase account, its private recovery backup, and the account’s on-device Ashrim Run data after confirmation. Workouts already exported to Apple Health remain managed by Apple Health. You can revoke Location, Health, Photos, and Notification permissions at any time in iOS Settings or the Health app. You can manage or revoke Ashrim Run’s Sign in with Apple authorization in Apple ID settings.

For privacy questions, use the App Support contact on Ashrim Run’s App Store listing.
