<div align="center">

<img src="assets/deski-logo.png" alt="Deski logo" width="132" />

# DESKI

### Your devices. One simple setup.

**Turn your Android phone into a customizable control deck for your Windows PC.**

[**Download Deski**](https://github.com/Boyshakya/Deski/releases/latest) ·
[Report a bug](https://github.com/Boyshakya/Deski/issues) ·
[Request a feature](https://github.com/Boyshakya/Deski/issues)

</div>

---

## Your phone. Your controls.

Deski brings quick desktop actions to a customizable Android control surface. Build a deck around the actions and apps you use most, then connect your phone to **Deski Companion for Windows**.

Whether you're gaming, creating content, streaming, or just working at your PC, Deski is designed to keep useful controls close at hand.

<div align="center">
  <img src="assets/windows-companion.jpg" alt="Deski Companion for Windows showing a customizable control deck" width="100%" />
  <sub>Deski Companion · Windows control-deck editor</sub>
</div>

## See it on Android

<div align="center">
  <img src="assets/android-control-deck.png" alt="Deski Android app showing configurable control buttons" width="32%" />
  &nbsp;&nbsp;
  <img src="assets/android-connection.png" alt="Deski Android device connection screen" width="32%" />
</div>

<sub>Android control deck and companion discovery screens.</sub>

## What you can do

- **Customize your control deck** — arrange actions in a grid and organize controls into pages.
- **Trigger desktop actions** — use supported actions from your phone instead of hunting through windows and menus.
- **Control media and audio** — access supported playback, volume, and mute controls.
- **Open apps and workflows** — put frequently used applications and actions on your deck.
- **Make it yours** — create a setup that fits your gaming, streaming, editing, or everyday workflow.
- **Connect to your PC** — find and connect to a Deski Companion on your network.

> Available actions depend on the installed version and your configuration.

## Getting started

1. Open the [latest GitHub release](https://github.com/Boyshakya/Deski/releases/latest).
2. Download the Android APK and Windows Companion package, if both are published for that release.
3. Install and launch both applications.
4. Keep the devices on the network required by the current connection setup.
5. Use the Android app's companion scan/connection flow and follow the prompts shown in the apps.
6. Configure your deck and test an action.

If a connection fails, check that both applications are running, the devices can communicate over the network, and Windows Firewall is not blocking the Companion.

## Project technologies

| Component | Technology |
|---|---|
| Android app | Kotlin · Jetpack Compose |
| Windows Companion | C# · WinUI 3 · .NET |
| Local persistence | SQLite where used |
| Device communication | WebSocket-based communication |

## Current status

Deski is under active development. Some integrations and actions may depend on configuration or the current release. Check the [releases page](https://github.com/Boyshakya/Deski/releases) for published builds and release notes.

Found a bug or have an idea? [Open an issue](https://github.com/Boyshakya/Deski/issues) and include your app version, Windows/Android version, steps to reproduce, and relevant logs or screenshots. **Do not post passwords, pairing secrets, or other private information.**

## Contributing

Contributions and actionable feedback are welcome.

1. Open an issue to discuss substantial changes.
2. Fork the repository and create a branch for your work.
3. Keep changes focused and test the affected application.
4. Submit a pull request describing the change and how you tested it.

## License

Check the repository's `LICENSE` file for the terms that apply to this project. If no license file is present, reuse and redistribution permissions should not be assumed.

---

<div align="center">
  <sub><b>Deski</b> · Built for everyday control.</sub>
</div>
