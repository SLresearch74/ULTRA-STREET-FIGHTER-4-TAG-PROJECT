# USF4 TAG! — Pre-Alpha v0.1.2

**Patch 01 · Combat build 119 · 42 characters**

A combat pre-alpha for **Ultra Street Fighter IV on Steam**. Patch 01 restores heavy pursuit starters and four heavy air-special routes, makes universal launches and pursuit lower and quicker, and adds diminishing lift to repeated grounded juggles.

[Download the installer](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/releases/download/v0.1.2/USF4TAG-PreAlpha-0.1.2-Setup.exe) · [Download the full ZIP](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/releases/download/v0.1.2/USF4TAG-PreAlpha-0.1.2.zip) · [Release page](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/releases/tag/v0.1.2) · [SHA-256 checksums](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/releases/download/v0.1.2/SHA256SUMS.txt)

## Apply Patch 01

### Update an existing install

1. Close USF4 and Simp normally.
2. Open **USF4 TAG Pre-Alpha** from your desktop. Choose **Manage → Check for updates**.
3. Accept **v0.1.2**. The launcher verifies the download before opening Setup. Wait for **Installation complete**.

If the launcher cannot open or reports damaged files, run the v0.1.2 installer directly, select the same Steam USF4 folder and click **Update Pre-Alpha**. If v0.1.2 launcher files are damaged later, close the launcher and rerun the same Setup. It replaces the launcher files and keeps the previous launcher folder as a backup. The update reuses the existing `tag_pre_v0100` folder and keeps a recovery copy of the previous build.

### Install for the first time

1. Close USF4 and Simp. Download **USF4TAG-PreAlpha-0.1.2-Setup.exe**. If you downloaded the ZIP, extract it first.
2. Run Setup and choose the Steam USF4 folder containing `SSFIV.exe` if asked.
3. Click **Install Pre-Alpha**. When installation finishes, use the **USF4 TAG Pre-Alpha** desktop shortcut.

Setup requires your own Steam copy of USF4 on Windows, PowerShell 5.1 and .NET Framework 4.7.2 or newer. It checks the Steam build and stock files, then reuses a verified Simp or downloads and verifies it. If the download is unavailable, Setup can use an existing copy that matches the tested Simp version.

## Play build 119

1. Open the desktop launcher and click **Launch USF4**.
2. Wait at the game's **main menu**.
3. Return to the launcher and click **Load Pre-Alpha**. In Simp, choose or confirm **tag_pre_v0100** and launch the patch.
4. Wait for **Patching complete** in the launcher. This confirms that the build 119 runtime has started.
5. Return to USF4 and enter **offline standard Ultra Training**. Select standard Ultra characters.

## Patch notes and roster

The runtime rules apply in offline standard Ultra Training. Hugo and Hakan remain deferred. Assists are part of a separate development build.

- [Patch 01 changelog](RELEASE_NOTES.md)
- [Plain-text v0.1.2 play guide](README.txt)
- [v0.1.0 roster reference](ROSTER_CHANGES.md) for character launchers and move details. Patch 01 takes precedence where it updates those rules.

### v0.1.0 translations

[Français](docs/fr/README.md) · [Deutsch](docs/de/README.md) · [Italiano](docs/it/README.md) · [Español](docs/es/README.md) · [简体中文](docs/zh-CN/README.md) · [日本語](docs/ja/README.md) · [한국어](docs/ko/README.md)

These guides cover the v0.1.0 baseline. [All translated roster documents and installation guides](docs/README.md) · [v0.1.0 multilingual ZIP](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/releases/download/v0.1.0/USF4TAG-PreAlpha-0.1.0-Multilingual.zip)

## Normal play and support

- **Normal USF4** — Exit USF4 and Simp, then choose **Play Normal USF4** or start a fresh Steam session with Simp closed.
- **Repair or remove** — Close USF4 and Simp, then use the corresponding action under **Manage**.
- **Report a bug** — Use **Manage → Report a bug** to preview local diagnostics, or open a GitHub issue. Include the characters, inputs, expected result and actual result. [Open an issue](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/issues/new)

Patch 01 was checked through a clean install, an in-place v0.1.0 upgrade, and a Steam library outside the default path. The live Steam session confirmed the completion popup, launcher stun scaling and Seth's post-Shoryuken damage scaling.

## Credits

USF4 Simp was created by **razor5070**. The session runtime uses **MinHook**. Game names and assets belong to their respective owners. [Credits](CREDITS.txt) · [Third-party notices](THIRD_PARTY_NOTICES.txt) · [License](LICENSE)
