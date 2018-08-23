## ***HOW TO CHANGE START-ALT NAMES***

1. Open BrawlBox.
2. Open `sc_selmap.pac`.
3. Expand the `MiscData[80]` BRES.
4. Expand `AnmTextPat(NW4R)`.
5. Expand `MenSelmapPreview`.
6. Expand `pasted__stnameM_start`, then `Texture0`.
7. To find the correct file to change, you must find the stage's index number. This can be located by expanding `Textures(NW4R` in the same BRES. `MenSelmapIcon.XX` displays the icon from the SSS. Once you find the stage, mark down the `XX` value.
8. In the expanded `Texture0` file, scroll down the list of `MenSelmapFrontStname`s until the `FrameIndex` on the right side of the screen has the same number you marked down earlier.
9. Change the `Texture` to the correct file. For example, if you wanted a start-alt of `Pokémon Stadium 2` on `Fountain of Dreams`, you would find the `PAT0 Texture Entry` with the `FrameIndex` of 25, then change the texture to `MenSelmapFrontStname.59`. (25 is Fountain's Index, and 59 is Stadium's.)