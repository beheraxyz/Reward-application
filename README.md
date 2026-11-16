# Reward-application
# UKB Rewards – Flutter starter

This is an original prototype inspired by common rewards-app features. It is not a copy of another app.

## Included in this first build
- Home dashboard
- Local demo-points balance
- Daily check-in
- Sample tasks
- Referral preview
- Points wallet and sample activity
- Profile, help and safety information

## Important limitations
- Demo points have no cash value.
- No deposits, withdrawals, payment processing, real-money rewards, or real referral payouts.
- Login, database, admin portal, surveys provider, notifications and production security are not connected yet.
- This prototype stores progress only in app memory; restarting the app resets it.

## Run
1. Install Flutter SDK on a computer.
2. Extract this project.
3. In the project folder run `flutter pub get`.
4. Run `flutter run` on an Android device or emulator.
5. Build an APK with `flutter build apk --release`.

## Next development phase
Add secure authentication, cloud database, server-side task validation, admin tools, privacy policy, and testing before any public release.

## Build APK using GitHub Actions (Android phone friendly)
1. Create a new GitHub repository named `UKB-REWARDS`.
2. Upload all files and folders from this project to the repository root (including the hidden `.github` folder).
3. Open the repository's **Actions** tab. If prompted, enable Actions.
4. The workflow runs automatically after a push to `main`. You can also choose **Build UKB Rewards APK** → **Run workflow**.
5. Open the completed workflow run, scroll to **Artifacts**, and download `ukb-rewards-release-apk`.
6. Extract the downloaded artifact ZIP to get `app-release.apk`.

The APK is an unsigned-for-store / locally installable release build produced by Flutter. For Play Store publication, configure a private Android signing key and verify the app's privacy, safety, and store requirements.
