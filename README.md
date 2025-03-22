# Crunchyroll-Downloader

A sophisticated utility for downloading your preferred series and episodes directly from [Crunchyroll](https://www.crunchyroll.com).

<p align="center">
  <a href="https://github.com/Crunchy-DL/Crunchy-Downloader">
    <img src="https://img.shields.io/github/languages/code-size/Crunchy-DL/Crunchy-Downloader?style=flat-square" alt="Code size">
  </a>
  <a href="https://github.com/Crunchy-DL/Crunchy-Downloader/releases/latest">
    <img src="https://img.shields.io/github/downloads/Crunchy-DL/Crunchy-Downloader/total?style=flat-square" alt="Download Badge">
  </a>
  <a href="https://github.com/Crunchy-DL/Crunchy-Downloader/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/Crunchy-DL/Crunchy-Downloader?style=flat-square" alt="License">
  </a>
  <a href="https://github.com/Crunchy-DL/Crunchy-Downloader/releases">
    <img src="https://img.shields.io/github/v/release/Crunchy-DL/Crunchy-Downloader?style=flat-square" alt="Release">
  </a>
</p>
<p align="center">
  <a href="https://discord.gg/QmGhqkAQBT">
    <img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
</p>

## Disclaimer

_This application is not affiliated with, maintained, authorized, sponsored, or officially associated with Crunchyroll LLC or any of its subsidiaries or affiliates. The official Crunchyroll website can be found at [https://crunchyroll.com/](https://crunchyroll.com/)._

This tool is designed for private use only. Access to premium content requires a [Crunchyroll Premium](https://www.crunchyroll.com/premium) subscription.

Using this application may violate the Terms of Service between you and the stream provider. The application enables you to download videos for offline viewing, which may be prohibited by law in your country. You are solely responsible for how you use Crunchyroll-Downloader.

## System Requirements

- Windows 10 or Windows 11
- .NET Desktop Runtime 8.0
- Visual C++ Redistributable 2015-22 ([Issue #144](https://github.com/Crunchy-DL/Crunchy-Downloader/issues/144))

## Features

Comprehensive documentation available on our [GitHub Wiki](https://github.com/Crunchy-DL/Crunchy-Downloader/wiki)

## DRM Decryption Guide

### Decryption Requirements

Place one of the following tools in the `./lib/` directory:

- **mp4decrypt** - Essential for decryption. Available at [Bento4.com](http://www.bento4.com/)
- **shaka-packager** - Alternative decryption tool. Available at [Shaka-Packager GitHub Releases](https://github.com/shaka-project/shaka-packager/releases/latest)

### Instructions

To decrypt DRM-protected content:

1. Acquire a Content Decryption Module (CDM)
2. Place the following CDM files in the `./widevine/` directory:
   - `device_client_id_blob.bin`
   - `device_private_key.pem`

For legal reasons, the CDM is not included with this software and must be obtained separately.
