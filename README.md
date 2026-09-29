# StructQTO — releases

Installers and the auto-update feed for **StructQTO**, the BDCON structural quantity take-off app for Windows. The source code lives in a private repository; this repo only holds release assets.

**Install:** open the latest release, download `StructQTO-<version>-setup.exe` and run it. It installs for the current Windows user, with no admin rights needed. Windows SmartScreen warns on first install because the build is unsigned: click **More info → Run anyway**. Requires 64-bit Windows 10/11.

Installed copies check this repo at startup and every 6 hours, download new versions in the background, and show **Update ready — restart to install**. `latest.yml` and the `.blockmap` files are what the updater reads; leave them alone.
