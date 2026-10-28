# Translation status — v0.103

Released 28 October 2026. This is an English School Life preview for the Japanese PS1 / PSX game, SLPS-02120.

## Translated

All **18,807 / 18,807 entries in the extracted scenario catalogue** are translated across their known references. This includes the later school-year dialogue and endings, with a final pronoun and wording review. It is a text-catalogue count, not a claim that every game screen or every route has been tested.

The combat graphics work adds:

- 32 previously untranslated tutorial/exam instruction sets. All 33 instruction atlases are included; the existing July translation also received a clearer HUD title.
- 210 move-name slots across 32 edit-character cards, including repeated names.
- English category and light/heavy attack labels on 56 cards: the 32 edit-character cards and 24 regular-fighter cards.
- Shorter, outlined English lesson titles for the combat HUD.

Move names are working English localizations; the official terminology still needs a consistency review. The game continues to hide moves that the character has not learned.

## Still to translate

- Team-Up move names in the shared graphic atlas.
- Command conditions and qualifiers, including in-air, charge and repeat instructions.
- Individual move names on the 24 regular-fighter cards. Their category and light/heavy labels are already translated.
- The character-data heading and stat page.
- Some exam HUD labels and calendar exam banners.

These are known remaining screens, not an exhaustive count of every graphical string. There is no reliable percentage for this remaining work yet. The next translation pass will focus on these move-list and exam details.

## Testing still to do

The BPS patch was independently decoded and reconstructed the exact tested build. All 89 new or revised graphic streams matched the final disc, and the 103 scenario assets remained unchanged from v0.102. Compression, sector and full-disc checks passed.

Targeted PCSX-ReARMed HLE/interpreter checks loaded the July, December and March exams through normal controls from pre-exam fixtures. The English textures matched VRAM exactly; complete instructions, two edit-card types and all three exam HUD titles were visually checked. The March exam returned to the calendar normally.

The 30 ordinary lessons, every card and unlock combination, and the regular-fighter cards still need individual in-game checks. Real-BIOS and DuckStation validation, actual character registration, and a complete school-year playthrough with all branches remain pending. Earlier testing includes targeted dialogue and calendar checks for both protagonists; it does not cover every route.
