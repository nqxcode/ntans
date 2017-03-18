ntrans
==============
Nano wrapper for [translate-shell](https://github.com/soimort/translate-shell) with some features:

1. Auto determine direction of translation: **en**:**rus** <=> **rus**:**en**.
2. Copy translation to clipboard.
3. Send notify message.
4. Grab statistics for original and translated text into ~/Dropbox/Public/dictionary.db.

## Installation

Download the [executable](http://git.io/vCb3W) and place it into your path.
```bash
$ wget git.io/vCb3W -O ntrans 
$ chmod +x ./ntrans
```
### Dependencies
1. [translate-shell](https://github.com/soimort/translate-shell)
2. xclip.
3. sqlalchemy.

## Usage

All samples see [here](https://github.com/soimort/translate-shell#introduction-by-examples).
