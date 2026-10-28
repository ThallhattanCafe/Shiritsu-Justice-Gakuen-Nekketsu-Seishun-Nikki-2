# Translation progress

Updated 28 October 2026.

## Extracted text complete

The local v0.102 development build has English text for **18,807 of 18,807 distinct entries in the extracted scenario catalogue**, across every known reference. This covers the catalogue's School Life dialogue, events, shared menus and year-end instructions.

The final language pass checked pronouns and forms of address against scene context. Male characters use he/him/his and female characters use she/her. Singular neutral references were rewritten where needed; actual plural references remain plural. The pass also corrected spelling and spacing.

This milestone applies to the extracted catalogue. Some text is stored or drawn elsewhere, so it does not mean every screen is in English.

## Next work

1. Locate and inventory the remaining combat-exam instructions, move-list pages, technique names and related labels.
2. Translate that material and add the required format support to Recast.
3. Check the rebuilt screens in-game, including button symbols, line lengths and navigation.
4. Continue route testing and real-BIOS/emulator validation before a later release.

The March exam instructions and combat character move list are confirmed examples of Japanese text outside the completed catalogue. An exact remaining string count is not available yet.

## Checks so far

The final development build passed binary, compressed-data, disc-sector and text-structure checks, plus the date-table and protagonist-pronoun regressions. Eight targeted runtime scenarios covered both protagonists through New Year, Valentine events, a December Batsu scene, and February-to-March progression through the ending and completion/save instructions. There were 126 selected dialogue captures reviewed for rendering.

Those checks used PCSX ReARMed with HLE BIOS and interpreter settings. They do not cover every dialogue branch or certify a complete school-year playthrough. Actual character registration after the final instructions, real-BIOS behavior and DuckStation validation remain to be checked.

## Downloads

The downloadable patch is still [v0.64](https://github.com/ThallhattanCafe/Shiritsu-Justice-Gakuen-Nekketsu-Seishun-Nikki-2/releases/tag/v0.64). Its coverage is lower than the development build described here. This update publishes progress notes only; it includes no new patch, translation dump, ROM or BIOS.

Reusable parser improvements, revision checks and synthetic tests are maintained in [Recast](https://github.com/ThallhattanCafe/recast). The game-specific translation data stays separate.
