# NetRain — Downloads

Public download for **NetRain** (a.k.a. the Active Matrix Screensaver) — a
movie-style Matrix digital rain screensaver for Windows that **reacts to your
network activity**. The rain speeds up, brightens, and shifts color as your
machine sends and receives data.

**▶ Live demo:** https://evident-dev.github.io/NetRain/

## Download & install (Windows)

1. Download **[NetRain-win.zip](https://github.com/Evident-Dev/NetRain-download/releases/latest/download/NetRain-win.zip)**.
2. Extract it (right-click → **Extract All**).
3. Inside the extracted folder, right-click **`Install-Screensaver.ps1`** → **Run
   with PowerShell** (or run
   `powershell -ExecutionPolicy Bypass -File .\Install-Screensaver.ps1`).

It installs the app and sets it as your screensaver — 5-minute idle timeout and
password-on-resume on by default. You can delete the extracted folder afterward.

- **Exit the screensaver:** move the mouse, press any key, or hit **Escape**.
- **Settings:** Windows Screen Saver dialog → **Settings…** (palette, letter size,
  trail length, frame rate, network interface, and more, with a live preview).
- **Uninstall:** run `Uninstall-Screensaver.ps1`.

> First launch shows a Windows SmartScreen prompt because the build isn't
> code-signed — click **More info → Run anyway**.

This repo hosts only the public release. The source code is maintained privately.
