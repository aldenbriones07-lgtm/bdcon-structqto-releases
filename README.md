# BDCon QTO — releases

Installers and the auto-update feed for **BDCon QTO** (formerly StructQTO), BDCON's structural quantity take-off app for Windows. The source code lives in a private repository; this repo only holds release assets.

## Install

Open the [latest release](https://github.com/aldenbriones07-lgtm/bdcon-structqto-releases/releases/latest), download `BDCon-QTO-<version>-setup.exe` and run it. It installs for the current Windows user, with no admin rights needed. Windows SmartScreen warns on first install because the build is unsigned: click **More info → Run anyway**. Requires 64-bit Windows 10/11.

## Signing in

From version 1.3.0 the app opens only for people BDCON has given it. Sign in with your **ProjectHub** email and password; each account uses the app on one PC.

- The first sign-in needs the internet. After that the app works offline: it checks in with ProjectHub when it starts and every few hours, and each check-in keeps it working for another 14 days.
- To be given the app, ask the President.
- To move to another PC, sign out on the old one (**Account → Sign out**), or ask the President to clear it.
- Only the sign-in, the PC's name, a random id for the PC and the app's version go to ProjectHub. Projects stay on the PC.

## Updates

Installed copies check this repo at startup and every 6 hours when online, download new versions in the background, and show **Update ready — restart to install**. `latest.yml` and the `.blockmap` files are what the updater reads; leave them alone.
