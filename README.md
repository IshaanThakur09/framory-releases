# Framory

Official Windows chat app and Android companion downloads.

- [Download Framory for Windows](https://github.com/IshaanThakur09/framory-releases/releases/latest/download/Framory.exe)
- [Download Framory for Android](https://github.com/IshaanThakur09/framory-releases/releases/latest/download/Framory.apk)
- [Release notes](https://github.com/IshaanThakur09/framory-releases/releases/latest)

## Windows

Download `Framory.exe` and open it. This is the local-model chat app: it uses an existing Framory host installation, its llama.cpp runtime, and your downloaded models. It is not a bundled model installer. Keep your existing host folder, or set `FRAMORY_ROOT` to its location.

## Android

Android 7 or later is required. Download `Framory.apk` and approve installation in Android. Install over your existing Framory app to retain its chats.

The app finds and verifies its configured shared host automatically. On a new phone, it displays **Waiting for approval on your PC** and a device fingerprint. On the host PC, open **Share → Manage devices**, compare the fingerprint, select the phone, and approve it once. No pairing code is typed. It reconnects automatically after that, and the host owner can revoke access at any time.

The host PC must be running the updated Framory Dashboard and sharing its model. When offline, the app shows its offline animation and retries automatically. Knowing the host address or downloading the APK does not grant permission to chat.

## Updates

Both apps check for updates at startup and have a **Check for updates** button in the sidebar. Windows offers to download and restart. Android downloads the update and asks you to approve installation; it may first ask you to allow installations from Framory.

Updates use signed metadata and SHA-256 download verification. The Android app also verifies the APK's package and signing certificate. Host discovery is signed separately; each approved device signs its chat requests with its own private key. Chats and model data are retained.

Existing builds without an updater need one manual installation of the latest download to enable it.

This repository distributes compiled applications and release metadata. Application source code is not published here.
