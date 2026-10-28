# USF4 TAG! — Pre-alpha v0.1

A 42-character combat pre-alpha for **Ultra Street Fighter IV on Steam**: character-specific launchers, pursuit air combos, juggle changes and bounce finishers.

**Languages:** [English](README.txt) · [Français](docs/fr/README.md) · [Deutsch](docs/de/README.md) · [Italiano](docs/it/README.md) · [Español](docs/es/README.md) · [简体中文](docs/zh-CN/README.md) · [日本語](docs/ja/README.md) · [한국어](docs/ko/README.md)

[All translated roster documents and installation guides](docs/README.md)

## Download

### [Download the complete pre-alpha ZIP](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/releases/download/v0.1.0/USF4TAG-PreAlpha-0.1.0-Multilingual.zip)

The multilingual ZIP includes the unchanged v0.1.0 installer, simple instructions and complete roster changes in English plus French, German, Italian, Spanish, Simplified Chinese, Japanese and Korean, along with credits and notices. The launcher interface remains English.

[Release page](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/releases/tag/v0.1.0) · [Installer only](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/releases/download/v0.1.0/USF4TAG-PreAlpha-0.1.0-Setup.exe) · [Download checksums](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/releases/download/v0.1.0/SHA256SUMS-Multilingual.txt)

## What is included?

- **42 supported characters** with individual launchers and move changes.
- **Hold Up after a launcher hits** to pursue into an air combo.
- Air normal chains start with a **light or medium**. Heavy normals act as finishers; character exceptions are listed in the roster document.
- Character-specific air specials, command normals and throws.
- A permanent launcher with installation, a patch-complete popup, updates, repair/removal, local logs and a bug-report preview.

**This release is the single-character combat pre-alpha. Team/tag gameplay is still separate. Hugo and Hakan are deferred.** The extra launcher-triggered **50% stun reduction currently applies only in offline standard Ultra Training**. Other modes do not receive that extra stun rule, and online compatibility is not claimed.

**[Read the complete roster changes](ROSTER_CHANGES.md)** for inputs, launchers, frame changes and exceptions.

## Requirements

- Your own installed **Steam copy of Ultra Street Fighter IV**.
- Windows with **PowerShell 5.1** and **.NET Framework 4.7.2 or newer**.
- The supported Steam build and required original files; Setup checks them automatically.
- Internet access for first-time Simp acquisition if the tested version is missing.

Setup reuses a matching installed Simp or downloads and verifies the tested version from its original source/archive. The Simp executable and the game are not bundled in the project download. A different installed Simp is preserved. If both download sources are unavailable, Setup lets you select an existing tested copy or cancel.

## Install and play

1. Close USF4 and Simp normally. **Extract the complete ZIP**, then run **USF4TAG-PreAlpha-0.1.0-Setup.exe**.
2. Choose your Steam USF4 folder if asked, click **Install Pre-Alpha**, and wait for installation to complete.
3. Open the desktop shortcut, click **Launch USF4**, and wait at the game's **main menu**.
4. Return to the launcher and click **Load Pre-Alpha**. In Simp, select **tag_pre_v0100** and click **Launch**.
5. Keep the launcher open until **Patching complete** appears, then enter **standard Ultra Training**.

Use standard Ultra characters. The launcher activates the Training stun rule automatically; there is no separate stun button.

Your desktop launcher remains available after deleting the downloaded installer. See [README.txt](README.txt) for the complete plain-text instructions.

## Normal play, updates and support

- **Normal USF4:** exit USF4 and Simp, then use **Play Normal USF4** or start a fresh Steam session with Simp closed. Original game files and saves are retained.
- **Updates:** use **Manage → Check for updates**. Newer published installers are downloaded and verified when you choose to update. Close USF4 and Simp before installing an update.
- **Repair/removal:** use the corresponding **Manage** actions with USF4 and Simp closed. Owned updates and repairs retain recovery copies.
- **Bugs:** use **Manage → Report a bug**, or [open an issue](https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/issues/new). Include the character/opponent, sequence, expected result and actual result. The launcher shows a diagnostics preview; you review and submit the issue on GitHub. Raw logs and files are not uploaded automatically.

## Testing status

The combat roster was accepted through local character playtesting. The working startup runtime and completion popup were checked in a real loading session. Public setup also checks source and output integrity and verifies any downloaded Simp before installation. Independent second-machine installation testing and exhaustive matchup coverage remain pending.

## Credits

USF4 Simp was created by **razor5070**. The session runtime uses **MinHook**. See [CREDITS.txt](CREDITS.txt), [THIRD_PARTY_NOTICES.txt](THIRD_PARTY_NOTICES.txt) and the project's [LICENSE](LICENSE). Game names and assets belong to their respective owners; this is a fan project.
