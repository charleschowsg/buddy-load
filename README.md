# Buddy-Load

A simple desktop app to install Android **APKs** onto **BYD / DiLink** vehicle
head units over wireless ADB — no terminal, no separate tools to install.

> **Unofficial.** Buddy-Load is an independent, community project. It is **not
> affiliated with, endorsed by, or supported by BYD**. "BYD" and "DiLink" are
> trademarks of their respective owners. Use at your own risk.

## Download

Get the latest version from the [**Releases**](../../releases/latest) page.

### macOS (Apple Silicon)

Download the **`.dmg`**, open it, and drag **Buddy-Load** into your
Applications folder. The macOS build is signed and notarized by Apple, so it
opens with no security warnings.

### Windows (64-bit)

Download the **`...x64-setup.exe`** and run it (a `.msi` is also available).

The Windows build is currently **unsigned**, so Windows shows a SmartScreen
prompt the first time you run it:

> **"Windows protected your PC — unknown publisher."** Click **More info**, then
> **Run anyway**.

This is expected and safe — it just means the app isn't code-signed yet.

## How to use

1. Park the car safely.
2. Enable wireless debugging on the car (see the video guides).
3. Put this computer and the car on the same Wi-Fi (a phone hotspot works well).
4. Enter the car's IP address, connect, and approve the prompt on the vehicle.
5. Drag in a trusted `.apk` and install.

## Safety

> Only install apps while safely parked. Use a trusted local network. Approve
> only your own computer's ADB prompt on the vehicle.

Buddy-Load only connects to an IP address you enter and installs ordinary user
APKs. It never enables ADB on the car, modifies system apps, or sends anything
off your device.

## Guides

Step-by-step video walkthroughs: **[@bydbuddy on YouTube](https://www.youtube.com/@bydbuddy)**
