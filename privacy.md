---
title: Privacy policy
permalink: /privacy
---

# Vault Manager privacy policy

_Last updated: 24 October 2026_

Vault Manager is a desktop password manager. It has no servers, user accounts, analytics, crash
reporting or advertising, and its author receives no data from it.

## What stays on your computer

- **Your vault**: a KeePass (KDBX 4) file in a location you choose, encrypted with your master
  password and/or key file. Vault Manager never sends it anywhere except to your own Google Drive,
  and only if you turn on Google Drive sync.
- **Preferences**, in the app's settings file: the paths of recently opened vaults, auto-lock and
  clipboard settings, which vaults use Touch ID, and, if you use Google Drive sync, your Google
  account's e-mail address and the Drive file each vault syncs with. The settings never contain
  passwords or vault contents.
- **Keychain**: if you turn on Touch ID unlock, the vault's master password is stored in your
  system keychain. If you sign in to Google Drive, the Google sign-in (a refresh token) is stored
  there too.

## Google Drive sync

Google Drive sync is optional and off until you sign in with Google in the app. When you sign in:

- **What the app asks for**: only the `drive.file` permission ("See, edit, create, and delete only
  the specific Google Drive files you use with this app"). Vault Manager can see and change only the
  vault files it uploaded or downloaded itself, never the rest of your Drive.
- **What the app reads from Google**: your Google account's e-mail address, to show which account
  is signed in, and the vault files above, with their name, size, modification time and version.
- **What the app writes to Google**: your vault file, encrypted with your master password exactly
  as it is on your computer. Google cannot read your passwords.
- **Where the data goes**: directly between your computer and Google. It is not sent to the author
  or to anyone else, and it is not used for advertising, profiling or training models.
- **Stopping**: **Sign out** in the app's settings deletes the stored sign-in and revokes it at
  Google. You can also remove the app's access at
  [myaccount.google.com/permissions](https://myaccount.google.com/permissions). Files already in
  your Drive stay there until you delete them.

Vault Manager's use and transfer of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

Google's handling of your Drive is covered by
[Google's privacy policy](https://policies.google.com/privacy).

## Links in your vault

When you open a website, e-mail or phone link from an item, Vault Manager hands it to your system,
which opens it in your browser or mail or phone app.

## Changes and contact

If this policy changes, the new version is published on this page with a new date. Questions can be
asked by opening an issue in
[this repository](https://github.com/artti-jaakkola/vault-manager-releases/issues).
