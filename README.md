# ResetEra-GiftHelper

A userscript to improve GiftBot usage in ResetEra. All credit goes to PeteTNT for his NeoGAF version[NeoGAF version](https://github.com/petetnt/neogaf-monkeybot). I merely adapted it without much success (only some basic functions work at this moment). I even copied most of this README.

## Features
- "In library" highlighting for raffles

## How-to use
1. Download [GreaseMonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) (Firefox) or [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en) (Chrome)
2. Open [this link](https://github.com/fcostantini/resetera-gifthelper/raw/master/resetera-gifthelper.user.js). *Monkey should prompt you for install.
3. Navigate to any ResetEra thread (e.g. https://www.resetera.com/threads/steam-march-2018-sensible-chuchel.26449/)
4. Follow the instructions prompted to you: ResetEra should now prompt you for your Steam profile name and the Steam API key...
5. ... and start collecting games!

## FAQ
### Where to get a SteamAPI key?
All use of the Steam Web API requires the use of an API Key. You can acquire one by [filling out this form](http://steamcommunity.com/dev/apikey). Use of the APIs also requires that you agree to the [Steam API Terms of Use](http://steamcommunity.com/dev/apiterms).

### Where to get the SteamID64?
The script automatically obtains the 64-bit Steam key based on your profile name, but you can also retrieve it yourself. Just add `?xml=1` after your profile name, for instance http://steamcommunity.com/id/YOURPROFILENAMEHERE/?xml=1 and get the key inside of `<steamID64></steamID64>`.

### I already own the game but it still isn't highlighted as "In library"
The games list is updated once per day maximum and the parser might/will miss games that are spelled differently than the actual Steam name, sorry about that.

## Contributing
Contributions are very welcome! File an issue or send a PR!
