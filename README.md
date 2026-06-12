# ScreenLink

A native macOS app for voice calls, screen sharing, and **two-way remote control** — call someone, share your screen, and either take over their screen or hand them control of yours, at any time.

## Features

- 🎙️ **Voice calls** — join by room code (no accounts to call; sign in once with Google)
- 🖥️ **Screen sharing** — share your screen over a low-latency connection
- 🖱️ **Remote control, both directions** — request control of their screen, or grant them control of yours, with an explicit accept prompt and a persistent "remote control active" banner you can revoke anytime

## Install

1. Download `ScreenLink.dmg` from the [latest release](../../releases/latest).
2. Open the DMG and drag **ScreenLink** to Applications.
3. **First launch:** the app isn't notarized (no paid Apple Developer account), so macOS will warn it's from an unidentified developer. **Right-click the app → Open**, then confirm. You only do this once.
4. Grant **Microphone**, **Screen Recording**, and **Accessibility** permissions when prompted (the app guides you to the right Settings panes). Accessibility is required for remote control (it injects mouse/keyboard events).
