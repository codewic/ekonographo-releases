# Ekonographo

A desktop studio for web graphics and PDFs. This repository holds the installers; installed copies check it for updates and update themselves.

## Install

Download the newest file for your system from [Releases](https://github.com/codewic/ekonographo-releases/releases/latest).

- **Fedora, RHEL, Rocky, Alma, openSUSE (RPM):** `sudo dnf install ./ekonographo-<version>-x86_64.rpm` (on openSUSE, `sudo zypper install ./ekonographo-<version>-x86_64.rpm`)
- **Ubuntu, Debian, Mint (deb):** `sudo apt install ./ekonographo-<version>-amd64.deb`
- **Any other Linux (AppImage):** make it executable (`chmod +x ekonographo-<version>-x86_64.AppImage`) and run it.

Text recognition in scanned PDFs uses Tesseract if it's installed (`sudo dnf install tesseract` or `sudo apt install tesseract-ocr`).

## Updates

The app checks for a new version when it opens, every 15 minutes while it's open, and when you come back to it. An update found at launch installs before you start; one found later waits for you to choose "Restart now". RPM and deb installs ask for your password to install the update.
