# `pywinauto-tests`

> [!WARNING]
> This is a fork.

These projects create executables that are used by `pywinauto` to test the functionality of the `pywinauto` library.

## Setup

### Install Qt

1. [Qt OSS Portal](https://my.qt.io/) > [Download Qt Online Installer](https://www.qt.io/download-qt-installer-oss)
    - [qt-online-installer-windows-x64-4.8.0.exe](https://d13lb3tujbc8s0.cloudfront.net/onlineinstallers/qt-online-installer-windows-x64-4.8.0.exe)
    - [qt-everywhere-src-6.7.1.zip](https://download.qt.io/official_releases/qt/6.7/6.7.1/single/qt-everywhere-src-6.7.1.zip)
    - [qt-everywhere-src-6.7.1.tar.xz](https://download.qt.io/official_releases/qt/6.7/6.7.1/single/qt-everywhere-src-6.7.1.tar.xz?__hstc=45788219.e9dba1c46f2e1969a08372456147125d.1689755853338.1689755853338.1689755853338.1&__hssc=45788219.1.1689755853338&__hsfp=783877104)
2. Run through installer settings
    - Prepare for ~48gb install if including everything in a single release.

```bash
qt-unified-windows-x64-[Qt Online Installer version]-online.exe --root C:\Users\[username]\installation_dir --accept-licenses --default-answer --confirm-command install qt.qt6.670.win64_msvc2019_64
```

```powershell
call "Y:\Data\Downloads\qt-online-installer-windows-x64-4.8.0.exe" --root "Y:\Tools\Qt" --accept-licenses --default-answer --confirm-command install qt.qt6.670.win64_msvc2019_64
```
