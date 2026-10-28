# Shiritsu Justice Gakuen: Nekketsu Seishun Nikki 2

English translation patch for the Japanese PlayStation game (PS1 / PSX, **SLPS-02120**), focused on **School Life mode**.

**v0.103 is available.** All **18,807 / 18,807 entries in the extracted scenario catalogue** are translated, with the final pronoun and wording review included. This release also adds combat-exam instructions and move-list graphics. Some graphical text remains Japanese, and a full playthrough of every route is still pending.

[Download v0.103](https://github.com/ThallhattanCafe/Shiritsu-Justice-Gakuen-Nekketsu-Seishun-Nikki-2/releases/tag/v0.103) · [Installation guide](https://github.com/ThallhattanCafe/Shiritsu-Justice-Gakuen-Nekketsu-Seishun-Nikki-2/wiki/Installation) · [Translation status](STATUS.md)

## What's new

- The complete extracted scenario translation, including later school-year dialogue and endings, beyond the older v0.64 preview.
- 32 additional tutorial/exam instruction sets; all 33 instruction atlases now have English text.
- 210 move-name slots across 32 edit-character cards.
- English category and light/heavy labels on 56 cards, plus clearer combat HUD lesson titles.

The 18,807-entry milestone covers the extracted text catalogue. It does not mean every game screen is translated or every route has been playtested.

## What's left

Team-Up move names, command qualifiers such as in-air/charge/repeat, and individual move names on 24 regular-fighter cards still need translation. The character-data heading/stat page and some exam HUD labels and calendar banners also remain Japanese. The next pass will focus on those move-list and exam details. [STATUS.md](STATUS.md) separates remaining translation from remaining testing.

## In-game screenshots

These are actual emulator captures from translated scenes. The dialogue screenshots were taken during v0.64 development; those translations remain included in v0.103.

### Natsu at the festival food stalls

![Natsu at the festival food stalls](natsu-dialogue.png)

### Tiffany at the school festival

![Tiffany at the school festival](tiffany-dialogue.png)

### Kyoko talks about helping the drama club

![Kyoko talks about helping the drama club](kyoko-dialogue.png)

### The class representative on festival duty

![The class representative on festival duty](class-rep-dialogue.png)

## Applying the patch

Apply the BPS patch to an **original, unmodified Japanese BIN** and load the matching CUE in your emulator. Start from the original even if you have used an earlier English patch. The [installation guide](https://github.com/ThallhattanCafe/Shiritsu-Justice-Gakuen-Nekketsu-Seishun-Nikki-2/wiki/Installation) includes filenames, hashes and troubleshooting.

Only the patch, documentation and screenshots are distributed here. No game image, BIOS or translation dump is included.

## Testing

Independent BPS reconstruction and binary checks passed. Targeted emulator checks confirmed the July, December and March exam instructions and HUDs, two edit-character move-card types, and the March return to the calendar. Testing used PCSX-ReARMed HLE/interpreter. Most individual lessons and card/unlock combinations, real-BIOS/DuckStation validation and a complete school-year playthrough remain to be checked. See [STATUS.md](STATUS.md) for the scope.

## Tools

The translation tools are maintained separately in [Recast](https://github.com/ThallhattanCafe/recast).

This is an unofficial fan translation. The original game and its assets belong to Capcom. No affiliation or endorsement is implied.
