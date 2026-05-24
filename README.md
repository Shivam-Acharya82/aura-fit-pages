# AURA-FIT Play Store Pages

This folder contains public pages required for Google Play review.

## Privacy Policy

File:

```text
play-store/privacy-policy.html
```

Host this page publicly and paste the final URL in Play Console, for example:

```text
https://your-domain.com/privacy
```

Before publishing, replace:

```text
your-support-email@example.com
```

with your real support email.

The policy is written for the current app setup:

- Firebase Authentication
- Firebase Firestore cloud sync
- Cloudinary image uploads
- Health Connect steps, distance, and calories
- Location for running speed
- Camera/gallery for profile and memories
- Notifications
- Account deletion

## Account Deletion

File:

```text
play-store/delete-account.html
```

Host this page publicly and paste the final URL in Play Console when Google asks for an account deletion link, for example:

```text
https://your-domain.com/delete-account
```

Before publishing, replace:

```text
your-support-email@example.com
```

with your real support email in both HTML files.

This page explains both supported account actions:

- Temporary deactivation keeps user data safe for later reactivation.
- Permanent deletion removes the account and associated cloud data.
