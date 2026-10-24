# Changelog

What changed in each Kitback release. The newest is at the top.

## 0.2.2 beta

- Sessions, lives and the forecast now use every money reading. 0.2.1 kept
  only the old reader's occasional readings there, so lives could be missed
  or cut short. Sessions recorded on 0.2.1 are read correctly after updating.
- The life net no longer flips between plus and minus once the arrow beside
  it fades.
- A money value read with digits missing is no longer taken as a real jump
  in cash.
- Enhanced reading is faster on menus and the map.
- The first-run tour now asks whether to use Enhanced reading, and explains
  it: it gives the best results at both supported sizes, runs on your PC and
  sends nothing anywhere. Updating? It is in Settings > Reading.
- 1920x1080 is no longer experimental: it has now been tested on real 1080p
  screens. Enhanced reading reads the event feed best at that size.

## 0.2.1 beta

- Reads the money counter and the event feed more accurately, using Windows'
  own text recognition. The old reader stays as a backup.
- The life net's sign comes from the green or red arrow beside it, so a faint
  minus sign can no longer turn a loss into a gain.
- New option, Settings > Reading > Enhanced reading: reads the money and the
  feed with a small AI text-recognition model built into Kitback. It runs on
  your PC and sends nothing anywhere. In our tests it misread the feed less
  often. Off by default; it applies from your next recording.
- Fixed feed amounts with a 2, 4 or 5 that could be read as the wrong digit.

## 0.2.0 beta (first public release)

- Tracks your WARDOGS cash life by life: the kit you bought, every payout from
  the event feed, and the moment the kit has paid for itself.
- Each payout is checked against the money counter, so figures marked
  confirmed are the real amounts.
- Detects the end of a match and shows the game's own match summary
  (placement bonus, cash earned, spent, refunded and total profit). A life
  still running when the match ends is counted as surviving it.
- Live figures pause, with a note, when the HUD has not been seen for 30
  seconds (a menu, or the match is over), instead of looking live.
- Forecast: break-even odds for your kits, learned from your own lives.
- Auto-record: starts when WARDOGS opens and stops when it closes.
- Updates itself from this page's releases.
- Supports 2560x1440 borderless windowed. 1920x1080 is experimental.
