# CoinOPS x Slate System View Overhaul for EmulationStation Desktop Edition (ES-DE)

This customized theme **(built on Steam Deck)** is a fusion of the Slate CoinOPS theme by BritneysPAIRS (BP) and gjsmsmith, along with influences from [ARTFLIX](https://github.com/fagnerpc/Alekfull-ARTFLIX/) by [Alekfull](https://github.com/fagnerpc/) and [ARTFLIX-Colbalto](https://github.com/galisteogames/ARTFLIX-Cobalto/) by [Galisteo](https://github.com/galisteogames/).

## Compatibility
This theme is optimized for use with the Simple theme, ensuring that hardware elements do not overlap with the system name.

## Customization
To further edit and expand the theme:
- Refer to the ConsoleWallpapers.fig file in the _inc directory to add your own additional console wallpapers.
- Update your local device by adding new images to the following directories:
  - _inc/systems/images (only paneloverlay.png was changed)
  - _inc/systems/fanart
  - _inc/systems/logos

## Artwork Credits
All credit for the original artwork goes to the respective creators. This modification involves restructuring and recoloring to align with the desired aesthetic.

## Slate Theme Reference
Explore the original Slate artwork at [Slate Theme](https://gitlab.com/es-de/emulationstation-de/-/tree/stable-2.2/themes/slate-es-de).

Feel free to contribute and enhance this theme, and share your modifications with the community. Thank you for using the CoinOPS x Slate System View Overhaul for EmulationStation Desktop Edition (ES-DE)!

## **Key Changes**
- Removed Purple Hue on screen
- Used Slate images to create a set of wallpapers
- Changed Console logos on System view to white text where there is black (ex: Playstation 2 is now white text on System view)

## **Preview**

| New System Views                                  |
|---------------------------------------------------|
| GC ![](_inc/screenshots/gcShowcase.jpg)           |
| Genesis ![](_inc/screenshots/genesisShowcase.jpg) |
| PSX ![](_inc/screenshots/psxShowcase.jpg)         |
| PS2 ![](_inc/screenshots/ps2Showcase.jpg)         |
| SNES ![](_inc/screenshots/snesShowcase.jpg)       |
| N64 ![](_inc/screenshots/n64Showcase.jpg)         |
| GBA ![](_inc/screenshots/gbaShowcase.jpg)         |
| GBC ![](_inc/screenshots/gbcShowcase.jpg)         |


| Old System View                                                                                                                                            | Gamelist View (UNCHANGED)                                                                                                                                  |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![Base Profile Screenshot 2023 04 21 - 20 11 03 68](https://user-images.githubusercontent.com/39314057/233753948-e11d35ac-d8a6-44dd-8e16-a787bcc3eec6.png) | ![Base Profile Screenshot 2023 04 21 - 20 11 17 86](https://user-images.githubusercontent.com/39314057/233753951-3a1f60e7-46ff-48dd-99ce-6f72f5b2d282.png) |


## **Configuration Options**

- The theme has a simple set of options that can be changed directly from the UI Settings menu of ES-DE 
- `Theme Variant` - sets the layout used for the sytem gamelist views.  There are 3 variants to choose from:
   - `Default` - Default view that displays system and gamelist metadata for each view
   - `No Hue` - The same as the Default view, but no blue/purple hue is applied to the system and fan art overlays
   - `Simple` - A minimalistic view with no metadata in the system or gamelist views
   - `Simple With Cover Art` - A minimalistic view with no metadata in the system or gamelist views (with cover art)
- `Theme Aspect Ratio` - sets the aspect ratio the theme will render at. If needed, this can be changed to match the aspect ratio of your screen (though it should happen automatically).
   - 16:9 and 16:10 are supported

### Preview of the Theme Variants (16:9)

| Theme Variant | System View | Gamelist View |
|----|----|----|
| Default | ![Base Profile Screenshot 2023 04 21 - 20 11 03 68](https://user-images.githubusercontent.com/39314057/233753948-e11d35ac-d8a6-44dd-8e16-a787bcc3eec6.png) | ![Base Profile Screenshot 2023 04 21 - 20 11 17 86](https://user-images.githubusercontent.com/39314057/233753951-3a1f60e7-46ff-48dd-99ce-6f72f5b2d282.png) |
| No Hue | ![Base Profile Screenshot 2023 04 24 - 15 27 29 90](https://user-images.githubusercontent.com/39314057/234110145-2d373233-012c-4f54-9e79-2f66284345c5.png) | ![Base Profile Screenshot 2023 04 24 - 15 29 26 05](https://user-images.githubusercontent.com/39314057/234110210-d368bda4-0259-4eba-8810-97cca475cab6.png)
| Simple | ![Base Profile Screenshot 2023 04 25 - 17 47 33 42](https://user-images.githubusercontent.com/39314057/234423620-a94bc4a4-b3b0-4685-9eee-36843844e58c.png) | ![Base Profile Screenshot 2023 04 25 - 17 47 39 11](https://user-images.githubusercontent.com/39314057/234423703-8da13b27-6f26-4faf-a8c9-64467e825bfb.png) 
| Simple With Cover Art | ![Base Profile Screenshot 2023 07 09 - 09 19 43 39](https://github.com/TheGrizzMD/coinops-es-de/assets/39314057/4255255a-b932-4cb3-8740-471db66a8ee4) | ![Base Profile Screenshot 2023 07 09 - 09 20 24 19](https://github.com/TheGrizzMD/coinops-es-de/assets/39314057/e8a91c04-b7b3-4cce-a098-e3ae91e864ed)

## **Additional Notes**

### Scraping:

* This theme looks best when the following are set to be scraped under Scraper > Content Settings:
   * Game Names
   * Ratings
   * Other Metadata
   * Videos
   * Box Cover Images
   * Marquee (Wheel) Images
   * Fan Art Images
* Other media is optional and will be used in cases where one of the above is missing (for example Screenshot images will be used if Videos are missing)

### Per game cabinet art:
* This theme supports using a unique cabinet or TV images for each game
* I have made a set of these images available via a theme addon here: https://github.com/TheGrizzMD/coinops-es-de-addons

## **Acknowledgments**

- Cabinet Wheel theme from the CoinOPS project by BritneysPAIRS (BP).
- TV/Arcade Cabinet artwork by gjsmsmith.
- System Logos, and System images from [ARTFLIX](https://github.com/fagnerpc/Alekfull-ARTFLIX/) and [ARTFLIX-Colbalto](https://github.com/galisteogames/ARTFLIX-Cobalto/)
- If I overlooked any credits or acknowledgements, please let me know and I will add them.

## **License**

Creative Commons CC-BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/2.0/
You are free to share and adapt this theme as long as you provide attribution back as well share any updates you make under the same licence terms.
