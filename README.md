# NOVA Download Manager

**A modern Windows download manager for everyday files, browser capture, and supported online video workflows.**

![Windows](https://img.shields.io/badge/Platform-Windows-161B22?logo=windows&logoColor=white) ![Release](https://img.shields.io/badge/Release-v0.15.4-2563EB) ![Source](https://img.shields.io/badge/Source-Private-334155) ![Platform](https://img.shields.io/badge/.NET-8-512BD4)

### [⬇ Download NOVA v0.15.4](https://github.com/Elsaadan/nova-download-manager/releases/download/v0.15.4/NOVA_Setup_v0.15.4.exe) · [Latest release](https://github.com/Elsaadan/nova-download-manager/releases/latest) · [دليل التثبيت بالعربي](docs/INSTALLATION_AR.md)

---

## Meet NOVA

NOVA Download Manager is a Windows desktop application that helps you **organize and control your downloads in one place**. Its workflow brings together a download queue, task progress, manual pause/resume, and browser-assisted capture for compatible websites.

### Key features

| | Capability | Details |
|---|---|---|
| 📥 | Download manager | Monitor and organize download tasks in one interface |
| 📋 | Smart queue | Manage queued and active downloads |
| 📊 | Progress and status | View transfer progress, status, and download information |
| ⏯️ | Manual controls | Pause and resume compatible downloads, with checkpoint support |
| 🌐 | Browser integration | Connect the NOVA extension to the desktop app with Chrome Native Messaging |
| 🎬 | Social video capture | Download supported public/authorized media links from Facebook, Instagram, and other compatible sources; availability varies by site |
| ▶️ | YouTube support | Supported YouTube single-video and playlist workflows, subject to website restrictions |
| 📁 | Playlist organization | Supported YouTube playlist workflows can group videos into a named folder under one overall task |
| 🖥️ | Windows integration | Desktop interface and notification-area controls |
| 🔄 | Version updates | Uses the official published [update manifest](update.json) |

> **Compatibility note:** Website availability, sign-in requirements, DRM and site changes can affect media downloads. Features and behavior can differ by installed version. No automatic recovery or automatic retry of stalled downloads is promised.

## Screenshots

Screenshots of the actual NOVA desktop interface and browser extension will be added after review. No mockups are presented as product screenshots.

## Installation

1. Go to the [official Releases page](https://github.com/Elsaadan/nova-download-manager/releases/latest).
2. Under **Assets**, download the Windows setup file (for this release, `NOVA_Setup_v0.15.4.exe`).
3. Run the installer and follow the on-screen instructions.
4. When upgrading, **leave `CLEAN START` unchecked** if you want to preserve your existing download-task history.
5. Configure the NOVA browser extension / Native Messaging connection if you use browser capture.

**For installers, select the `.exe` asset — not GitHub's automatically generated `Source code (zip)` or `Source code (tar.gz)` archives.**

[English installation guide](docs/INSTALLATION_EN.md) · [دليل التثبيت بالعربي](docs/INSTALLATION_AR.md)

### File integrity

The published SHA-256 for `NOVA_Setup_v0.15.4.exe` is:

```text
AD4F5D7E32ACEC6BF31361CE26F26DB364B768DDB52ADC83E74DE5B00625A5B4
```

Verify a downloaded file from PowerShell:

```powershell
Get-FileHash ".\NOVA_Setup_v0.15.4.exe" -Algorithm SHA256
```

## Documentation

- [Install / upgrade (English)](docs/INSTALLATION_EN.md)
- [التثبيت والتحديث (عربي)](docs/INSTALLATION_AR.md)
- [Changelog](CHANGELOG.md)
- [Releases](https://github.com/Elsaadan/nova-download-manager/releases)

## FAQ

**Is NOVA open source?**  
No. The application source code is maintained in a **private** repository. This public repository contains releases, documentation, and update metadata. It does not contain the private application source. GitHub creates source archives from the *public repository contents* for every tag; those are not the proprietary application source.

**Is NOVA an official IDM product?**  
No. NOVA is an independent application and is not affiliated with Internet Download Manager.

**Can NOVA download from every website?**  
No. Availability depends on the site, account permissions, and delivery restrictions. Do not use NOVA to access or download content without permission.

---

## عربي | NOVA Download Manager

**NOVA** برنامج لإدارة التحميلات على ويندوز، بيجمع التحميلات في واجهة واحدة وبيساعدك تتحكم في قائمة الانتظار ومتابعة حالة كل تحميل، مع إمكانية الربط بإضافة المتصفح لالتقاط التحميلات من المواقع المتوافقة.

### المميزات

- **إدارة التحميلات:** عرض المهام وحالتها ومتابعة التقدم.
- **قائمة انتظار منظمة:** التحكم في التحميلات النشطة والمنتظرة.
- **إيقاف واستكمال يدوي:** للتحميلات التي تدعم الاستكمال.
- **تكامل المتصفح:** إضافة Chrome والربط مع تطبيق الويندوز عن طريق Native Messaging.
- **فيديوهات السوشيال ميديا:** تنزيل الفيديوهات المتاحة والمصرّح بها من **Facebook وInstagram** والمصادر المتوافقة، حسب تغييرات الموقع وقيود الوصول.
- **YouTube:** تحميل الفيديوهات المدعومة وتنظيم قوائم التشغيل.
- **قوائم تشغيل YouTube:** في المسارات المدعومة يمكن تجميع الفيديوهات بمجلد باسم القائمة، مع مهمة إجمالية واحدة.
- **بيانات التحديث:** معرفة إصدار البرنامج من ملف التحديث الرسمي.

### تحميل وتثبيت NOVA

1. افتح [صفحة آخر إصدار](https://github.com/Elsaadan/nova-download-manager/releases/latest).
2. من **Assets** حمّل `NOVA_Setup_v0.15.4.exe`.
3. شغّل ملف التثبيت واتبع التعليمات.
4. **مهم:** عند التحديث، اترك خيار `CLEAN START` بدون تحديد علشان تحتفظ بسجل مهامك القديم.

**[⬇ تحميل NOVA v0.15.4](https://github.com/Elsaadan/nova-download-manager/releases/download/v0.15.4/NOVA_Setup_v0.15.4.exe)** · **[شرح التثبيت بالعربي](docs/INSTALLATION_AR.md)**

> **خصوصية المشروع:** المستودع ده لتحميل البرنامج وتحديثاته، ومش بيحتوي على الكود المصدري الأصلي. روابط `Source code` التلقائية في GitHub مش ملف تثبيت البرنامج.

---

*© NOVA Download Manager — project owner's proprietary software. All rights reserved.*
