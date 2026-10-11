# Mado 窓

A calm planner for your Mac: plans, time, habits and notes in one place, with
a little buddy, Teru, who keeps you company. It's free, there's no account, and
everything stays on your Mac. Give your vault a password and it's encrypted
with it.

Mado was called Yoru until October 2026. Your data, your vaults and your
Claude setup are where they were. The installers' file names, and the app's
name in macOS, keep the old name until version 3.0.0.

This repository holds Mado's installers, and nothing else.

## Download

Which Mac do you have? Apple menu → About This Mac → Chip:

- **Apple M1, M2, M3, M4 or later:
  [download Mado for Apple silicon](https://github.com/Rabadakku/Mado-releases/releases/latest/download/Yoru-arm64.dmg)**
- **Intel:
  [download Mado for Intel](https://github.com/Rabadakku/Mado-releases/releases/latest/download/Yoru-x64.dmg)**

Both are the newest version. What's in it, and every version before:
[releases](https://github.com/Rabadakku/Mado-releases/releases).

## Install

1. Open the `.dmg` and drag the app into Applications.
2. Open it. macOS says it can't check it, because it isn't signed with an
   Apple developer certificate yet: click **Done**.
3. Open System Settings → Privacy & Security, scroll down to the message that
   the app "was blocked…", click **Open Anyway**, and confirm. You only do
   this once.

If macOS says the app "is damaged and can't be opened", run this in Terminal,
then open it again:

    xattr -dr com.apple.quarantine /Applications/Yoru.app

## Updates

Mado tells you when there's a new version, in its status bar and in Settings.
Click **Update**: it downloads the new Mado, checks it's exactly the one
published here, and **Restart to update** puts it in place and opens it. Your
data stays. A vault made before 2.5 keeps its key in your keychain, so macOS
may ask about "Yoru Safe Storage": enter your Mac's password and click
**Always Allow**, and Mado offers to keep the vault as an ordinary file so it
never asks again.

Before 2.2.0, the app couldn't update itself: quit it, then drag the new one
into Applications, replacing the old one. From then on it updates itself.

## Help and ideas

In Mado, use Help → Report a Bug or Help → Suggest an Idea. Or
[open an issue](https://github.com/Rabadakku/Mado-releases/issues) here.
