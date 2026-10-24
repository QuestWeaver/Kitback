# Kitback — WARDOGS cash tracker

**Does this kit pay for itself before I die?** WARDOGS never tells you.
Kitback watches the money counter and event feed on your screen, logs each
life, learns how fast you earn and how long you usually survive, and tells you
whether a kit is above or below break-even.

Kitback is **free, and always will be**. It is in **beta**: expect rough edges,
and figures that are occasionally wrong.

> **Unofficial fan tool.** Kitback is made by an independent player. Neither
> Kitback nor its author is associated or affiliated with, employed by,
> partnered with, endorsed or sponsored by BULKHEAD, Team17, or anyone else
> involved in making or publishing WARDOGS. WARDOGS and its names and logos are
> trademarks of their owners, used here only to say which game Kitback works
> with.

## Download

Get **`Kitback-win-Setup.exe`** from the
[Releases page](https://github.com/QuestWeaver/Kitback/releases/latest) and run
it. This page is the only official source; copies from anywhere else are not
authorized and may have been tampered with.

- It installs for your Windows user only (no admin rights) and adds Start menu
  and desktop shortcuts.
- Windows SmartScreen may say "Windows protected your PC" because the app is
  not code-signed. Click **More info → Run anyway**.
- Updates download by themselves and install the next time you start Kitback.
- Uninstall from Windows Settings → Apps. Your recorded data is kept.

## Requirements

| | |
|---|---|
| OS | Windows 10 or 11, 64-bit (tested on Windows 11) |
| Game resolution | **2560x1440 or 1920x1080.** Turn on Settings > Reading > Enhanced reading (the first-run tour asks): it reads best at both sizes, above all at 1920x1080. Other sizes are refused rather than misread. |
| Display mode | **Borderless windowed.** Exclusive fullscreen captures a black screen. |
| HUD settings | **Session cash** and **Event feed** set to *On*. |
| Language / colours | English, default colours. Other settings are untested. |

## Using it

- **Auto-record** (on by default): with Kitback open, recording starts when
  WARDOGS opens and stops when it closes. Turn it off in **Settings**.
- **Dashboard:** this life and this session: money, kills, where your money
  came from, and whether your kit has paid for itself yet.
- **Sessions:** every recorded session, broken into lives, with the game's own
  end-of-match summary.
- **Forecast:** break-even odds for your kits. It needs about 20 lives before
  the odds can be trusted, and says so until then.

Closing the Kitback window quits it.

## How it works, and fair play

Kitback only reads what WARDOGS already shows on your screen, from screen
pixels. It does **not** read or change game memory, does not touch game files,
does not send any input to the game, does not automate anything, and never
draws over the game.

You are responsible for making sure your use of Kitback follows the rules of
WARDOGS and of the platform you play it on.

## Privacy

- Everything Kitback records stays on your PC, in `%LOCALAPPDATA%\Kitback Data`
  (Settings → **Open data folder**).
- No accounts, no telemetry, no analytics.
- Its only network request is the update check to this repository's releases.
- The Ko-fi link opens your browser only when you click it.

## What's new

See [CHANGELOG.md](CHANGELOG.md).

## Bugs and questions

Open an issue on the [Issues page](https://github.com/QuestWeaver/Kitback/issues).
Include your Kitback version (Settings → About) and your screen size. Settings →
**Open data folder** has the session logs (`.jsonl`), which hold only game
numbers and are safe to attach.

`errors.log` can contain folder paths that include your Windows user name.
Check it before posting it publicly, or email it instead to
QuestWeaverMedia@gmail.com, which is also the address for anything you would
rather not post in public.

## Support

If Kitback helps you, you can support it on
[Ko-fi](https://ko-fi.com/questweaver). Tips are a gift and never required.

## License

© 2026 QuestWeaver. All rights reserved.

Kitback is **not open source**. You may download and use it for free, for
yourself, under the [license agreement](LICENSE.txt) that ships with it. You
may show it in screenshots, videos and streams. You may not redistribute,
re-host, sell, modify or reverse engineer it. The source code is not
published.

Kitback includes open-source components under their own licenses; see
`THIRD_PARTY_NOTICES.txt` in the install folder.
