# undangan-jawa-vintage

A landing-page style wedding invitation built as a single HTML file.

## Features

- Customizable wedding data via `window.WEDDING_DATA`
- Full-screen welcome gate with personalized guest name support via URL query params
- Background video, photo gallery, countdown timer, and event details
- Firebase-backed RSVP/comment submission
- Copy-to-clipboard utilities for bank account and address details

## How to use

1. Open `index.html` in a text editor.
2. Update the values inside the `window.WEDDING_DATA` object.
3. Save and preview the page in a browser.

## Firebase setup

If you want live comments and RSVP submission, configure Firebase Firestore:

1. Create a Firebase project.
2. Add a web app and copy the config values.
3. Replace the `firebaseConfig` object in `index.html`.
4. Configure Firestore rules to allow read/write access for your invitation if needed.

## Notes

- The audio toggle is now always visible once the invitation opens, even if autoplay is blocked.
- The page no longer blocks right-click or keyboard shortcuts, improving accessibility and user interaction.
