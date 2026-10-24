# Framory

Official Windows chat app and Android companion downloads.

- [Download Framory for Windows](https://github.com/IshaanThakur09/framory-releases/releases/latest/download/Framory.exe)
- [Download Framory for Android](https://github.com/IshaanThakur09/framory-releases/releases/latest/download/Framory.apk)
- [Release notes](https://github.com/IshaanThakur09/framory-releases/releases/latest)

## Windows

Download `Framory.exe` and open it. This is the local-model chat app: it uses an existing Framory host installation, its llama.cpp runtime, and your downloaded models. It is not a bundled model installer. Keep your existing host folder, or set `FRAMORY_ROOT` to its location.

## Android

Android 7 or later is required. Download `Framory.apk` and approve installation in Android. Install over your existing Framory app to retain its chats.

For a new installation, tap the connection message or open the sidebar and choose **Connect to host**. Enter the private pairing code supplied by your host's owner. The host PC must be running and sharing its model. Pairing codes are not included in public downloads.

## Updates

From version 1.5.0, both apps check for updates at startup and have a **Check for updates** button in the sidebar. Windows offers to download and restart. Android downloads the update and asks you to approve installation; it may first ask you to allow installations from Framory.

Updates use signed metadata and SHA-256 download verification. The Android app also verifies the APK's package and signing certificate. Chats and model data are retained.

Versions older than 1.5.0 need one manual installation of the latest download to enable the updater.

This repository distributes compiled applications and release metadata. Application source code is not published here.
