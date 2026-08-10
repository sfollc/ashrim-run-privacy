# Ashrim Run Privacy Policy

Effective August 10, 2026

Ashrim Run is designed to work on-device first. If you choose Sign in with Apple, it also creates a private account and encrypted-in-transit backup using Supabase so your information can be recovered after reinstalling or changing phones. The app does not include advertising or analytics SDKs, sell personal information, or use information for tracking.

## Information handled by the app

- Profile, training, event, goal, saved-route, and workout information is stored locally on your device. When cloud recovery is active through Sign in with Apple, these categories are also included in your private Supabase recovery backup.
- If you use Sign in with Apple, Apple provides an identity token and account identifier and may provide your name or private-relay email address. Ashrim Run exchanges the identity token with Supabase, stores the resulting session securely in the device Keychain, and associates the backup with the resulting Supabase user ID. Ashrim Run never receives your Apple password.
- During an outdoor workout, Ashrim Run uses precise location to calculate distance, pace, and your route. The iPhone app can continue receiving location in the background while that workout is active. It stops requesting workout location when the recording finishes or is discarded. Completed route coordinates are stored with the workout and are included in a signed-in user's private recovery backup. Routes can also leave the app when you deliberately export or share them.
- With your permission, Ashrim Run uses HealthKit to read running workouts, routes, and related workout measurements and to write workouts and routes you choose to save to Apple Health. Apple Health controls those permissions and stores its own copy of Health records. A HealthKit workout imported into Ashrim Run becomes part of Ashrim Run workout history and, when cloud recovery is active, its supported workout information is included in the private recovery backup.
- The Ashrim Run Apple Watch app can record an authorized running workout, route, and supported measurements. It saves the workout through HealthKit and transfers a completed workout to the paired iPhone for inclusion in Ashrim Run history. When cloud recovery is active, that completed phone history record and its supported route data are included in the private recovery backup.
- Photo Library access is used only when you ask to save a run card. Notification permission is used only for reminders and workout notices you enable.

## Sharing and third parties

Signed-in account and recovery data is processed and hosted by Supabase solely to provide authentication, private backup, and recovery functionality. A backup can contain profile and preference information, workouts and supported route points, performance records and goals, weekly and running goals, saved routes, and training plans. Row-level security restricts each backup to its authenticated account. Ashrim Run does not share that data with advertising, analytics, or data-broker services. Information may also leave the app through an action you choose, such as sharing a run card, exporting GPX, saving to Photos, or writing an authorized workout to Apple Health. Apple and Supabase services are governed by their respective privacy and security terms.

## Retention, deletion, and choices

Local information remains until you delete the relevant item, permanently delete the account, or remove the app. The private backup remains while the cloud account exists so it can provide recovery after logout, reinstallation, or a device change. You can delete saved workouts and goals in the app and can reset profile setup without erasing workout history. Logging out removes the active session from the app but does not delete the private backup. Profile → Account → Permanently Delete Account requires confirmation and deletes the authenticated Supabase account, its private recovery backup, and the account’s on-device Ashrim Run data. Workouts already exported to Apple Health remain managed by Apple Health and can be deleted there. Because Ashrim Run does not retain an Apple refresh token, the deletion confirmation also explains how to revoke Ashrim Run manually from iPhone Settings → your name → Sign-In & Security → Sign in with Apple. You can revoke Location, Health, Photos, and Notification permissions at any time in iOS Settings or the Health app.

For privacy questions, use the App Support contact on Ashrim Run’s App Store listing.
