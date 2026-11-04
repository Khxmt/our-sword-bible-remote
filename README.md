# Our Sword Remote

Android remote-control app for **Our Sword**. Pair your phone by scanning a QR code, then control the app over your local Wi-Fi network.

[![Download APK](https://img.shields.io/badge/Download-APK%20v1.5.0-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/Khxmt/our-sword-bible-remote/releases/download/1.5.0/OurSwordRemote-1.5.0.apk)

---

## Download

| Version | File | Size | Min. Android |
|---------|------|------|--------------|
| 1.5.0 (build 6) | [OurSwordRemote-1.5.0.apk](https://github.com/Khxmt/our-sword-bible-remote/releases/download/1.5.0/OurSwordRemote-1.5.0.apk) | 2.0 MB | Android 8.0 (API 26) |

All versions are on the [Releases page](https://github.com/Khxmt/our-sword-bible-remote/releases).

### Verify the download (optional)

SHA-256:

```
1934a6715792f648384d118412f3507271668f6263932a410f7e56ab5549c547
```

- **Windows (PowerShell):** `Get-FileHash OurSwordRemote-1.5.0.apk -Algorithm SHA256`
- **macOS / Linux:** `shasum -a 256 OurSwordRemote-1.5.0.apk`

---

## Installation

1. Download the APK on your Android phone using the link above.
2. Open the downloaded file. Android will ask you to allow installs from this source (your browser or file manager). Tap **Settings**, turn on **Allow from this source**, then go back.
3. Tap **Install**.
4. Open **Our Sword Remote**.

> Because this app is installed from outside the Google Play Store, Google Play Protect may show a warning. Tap **More details → Install anyway** to continue.

## Pairing

1. Make sure your phone and the device you want to control are on the **same Wi-Fi network**.
2. Open the pairing QR code on the device you want to control.
3. In Our Sword Remote, tap to scan and point the camera at the QR code.
4. Once paired, you can start using the remote.

Pairing links in the form `oursword-remote://pair...` also open the app directly.

---

## Requirements

- Android 8.0 (Oreo) or newer
- Wi-Fi connection on the same local network as the target device
- Camera (for scanning the pairing QR code)

## Permissions

| Permission | Why it's needed |
|------------|-----------------|
| Camera | Scan the pairing QR code |
| Internet / Network state | Communicate with the paired device |
| Local network access | Find and connect to devices on your Wi-Fi network |

## Updating

Download the newer APK from the [Releases page](https://github.com/Khxmt/our-sword-bible-remote/releases/) and install it over the current version. Your settings are kept.

## Troubleshooting

- **"App not installed"**: Uninstall any older copy that was signed differently, then install again.
- **Can't connect after pairing**: Check that both devices are on the same Wi-Fi network and that the network doesn't block device-to-device traffic (common on guest or public Wi-Fi).
- **QR scanner shows a black screen**: Make sure camera permission is granted in **Settings → Apps → Our Sword Remote → Permissions**.

---

## App info

- **Package name:** `org.oursword.remote`
- **Version:** 1.5.0 (version code 6)
- **Target SDK:** 37
