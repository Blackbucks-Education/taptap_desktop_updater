# TapTap Desktop

The TapTap desktop app for Windows and Mac. Download the latest version from **[Releases](https://github.com/Blackbucks-Education/taptap_desktop_updater/releases/latest)**.

| Your computer | Download |
|---|---|
| Windows 10 / 11 | [`TapTap_x64-setup.exe`](https://github.com/Blackbucks-Education/taptap_desktop_updater/releases/latest) |
| Mac with Apple Silicon (M1, M2, M3, M4, M5, M6 or newer) | [`TapTap_aarch64.dmg`](https://github.com/Blackbucks-Education/taptap_desktop_updater/releases/latest) |

Not sure which Mac you have? Click the Apple menu → **About This Mac**. If it says **Chip: Apple M…**, use the `.dmg`. Intel Macs aren't supported yet.

Once installed, the app updates itself.

## Installing

The app isn't signed with a paid Apple or Microsoft certificate yet, so both systems show a warning the first time. This is expected. Follow the steps below once; after that it opens normally.

### Windows

1. Run the `.exe` you downloaded.
2. Windows shows **"Windows protected your PC"**. Click **More info**, then **Run anyway**.
3. Finish the installer. It installs for your user only, so no admin password is needed.
4. On first launch TapTap shows a **Device check** screen. There's no popup on Windows: TapTap uses the camera and mic directly, and the screen shows ✓ when both work.

**Camera blocked?** Click **Open camera settings** on the Device check screen and make sure **Camera access** and **Let desktop apps access your camera** are both on. Then click **Check again**.

### Mac

1. Open the `.dmg` and drag **TapTap** into **Applications**.
2. Open TapTap from Applications. macOS says it **"cannot verify the developer"** (or "Apple could not verify TapTap is free of malware"). Click **Done** (or **OK**). Don't click **Move to Bin**.
3. Open **System Settings → Privacy & Security**, scroll down to the line about TapTap being blocked, and click **Open Anyway**. Enter your Mac password if asked.
4. Open TapTap again and click **Open** in the dialog.
5. On first launch TapTap shows a **Device check** screen. macOS asks for **camera** and **microphone** access. Click **Allow** for both.

Right-clicking the app and choosing Open doesn't work on recent macOS. Use **Open Anyway** as in step 3.

**Clicked "Don't Allow" by mistake?** On the Device check screen, click **Open camera settings** (or **Open microphone settings**) and turn TapTap on. Then quit TapTap with **Cmd+Q** and open it again; macOS only applies the change after a restart.

**"TapTap is damaged and can't be opened"?** You have an older build. Delete it and install the latest one.

## Device check

Press **Ctrl+Shift+D** (Windows) or **Cmd+Shift+D** (Mac) to open the Device check again. It's disabled during a test.

## Updates

TapTap checks for updates in the background. When one is downloaded you'll see **"TapTap x.y.z is ready"** at the bottom right. Click **Restart now**, or **Later** to be reminded again later. It never updates during a test.
