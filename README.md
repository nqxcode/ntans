ntrans
==============
Nano wrapper for [translate-shell](https://github.com/soimort/translate-shell) with some features:

1. Determine direction of translation by current keyboard layout: en:ru <=> ru:en.
2. Copy translation to clipboard.
3. Send notify message.
4. For **phrase** translation use quotes: ```ntrans "for example".```

## Installation

Download the [executable](http://git.io/vCb3W) and place it into your path.
```bash
$ wget git.io/vCb3W -O ntrans 
$ chmod +x ./ntrans
```
### Dependencies
1. [translate-shell](https://github.com/soimort/translate-shell) 
2. [xkblayout-state](https://github.com/nonpop/xkblayout-state).
2. xclip.

## Usage

All samples see [here](https://github.com/soimort/translate-shell#introduction-by-examples).
