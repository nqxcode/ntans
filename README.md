ntrans
==============
Micro wrapper for [translate-shell](https://github.com/soimort/translate-shell).

It provides the following:

1. Determine direction of translation by current keyboard layout: en:ru <=> ru:en (used [xkblayout-state](https://github.com/nonpop/xkblayout-state)).
2. Copy translation to clipboard (used xclip).
3. Send notify message.

For phrase translation use quotes: ntrans "for example".
