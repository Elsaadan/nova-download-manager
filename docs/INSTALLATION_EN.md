# NOVA Download Manager — Installation guide

## Get the installer

Open the [official latest release](https://github.com/Elsaadan/nova-download-manager/releases/latest) and select the setup executable under **Assets**. The v0.15.4 asset is named `NOVA_Setup_v0.15.4.exe`.

## Install

1. Download the `.exe` installer.
2. Run it on Windows and follow the setup wizard.
3. Launch NOVA Download Manager.
4. For optional browser capture, use the NOVA browser extension and corresponding Native Messaging setup for your installation.

## Upgrade without deleting download history

When upgrading an existing NOVA installation, **leave `CLEAN START` unchecked** if you want to preserve your existing task history. Avoid deleting application data or download folders during a regular update.

## Verify SHA-256

For v0.15.4, the published file hash is:

```text
AD4F5D7E32ACEC6BF31361CE26F26DB364B768DDB52ADC83E74DE5B00625A5B4
```

Check it in PowerShell (from the download folder):

```powershell
Get-FileHash ".\NOVA_Setup_v0.15.4.exe" -Algorithm SHA256
```

Do not run a file whose hash differs.

## Why are there Source code archives?

GitHub automatically offers `Source code (zip)` and `Source code (tar.gz)` for a release tag. These are not Windows setup files. Use the `.exe` in **Assets**.

Some downloads can be limited by sites, authentication, DRM, or permissions. Download only content you're authorized to access.

[Back to project page](../README.md)
