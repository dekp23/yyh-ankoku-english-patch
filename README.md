# Yu Yu Hakusho: Ankoku Bujutsukai 120% - English patch (PS2)

Fan translation patch for **THE BATTLE OF 幽★遊★白書～死闘！暗黒武術会～120%** (PS2, SLPS-25734).  Assisted by Claude Code.
This repository contains no game data - only a binary patch. You need your own dump of the Japanese game.

## What's translated
- Menus, UI, character names and prompts
- All 14 story cutscenes (English subtitles and episode title cards)
- Arcade endings and story endings (subtitles)

Not translated: the staff roll.

## How to apply
1. Get the Japanese ISO. Check its MD5: `c6a38cb116cfaf9165778cf94319d620`
   (Redump: "Battle of Yuu Yuu Hakusho, The - Shitou! Ankoku Bujutsukai - 120% (Full Power) (Japan)").
2. Download `yyh_english_v1.xdelta` from the **Releases** page (about 1.1 GB).
3. Apply it with xdelta UI or Delta Patcher, or: `xdelta3 -d -s original.iso yyh_english_v1.xdelta english.iso`
4. The result's MD5 should be `699d128710c2b08f83d5be997a7c1fc5`. The patch has no built-in checksum, so a wrong source ISO produces a corrupt result silently.

Tested in PCSX2.
