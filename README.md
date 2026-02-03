# koreader-patches
KOReader user patches

# Customisable Sleep Screen Patch

A KOReader patch that displays reading statistics and book information on your sleep screen with extensive customisation options and the ability to save/load preset configurations.

## Features:

- Book progress, chapter progress, daily reading/goal progress, battery stats.
- Random book highlights (with location), or custom messages.
- Save your own configurations, 8 built-in presets included.
- Light/dark/monochrome modes (suitable for non-colour e-readers).
- Background: book cover (with optional overlay), images from folder, solid colour or transparent.
- Coloured progress bars for percentage stats.
- Dynamic icons for sections, with several icon-sets included.
- Reorder sections, adjust section spacing, show/hide elements.
- Customise layout, position, opacity, borders, font face/size, text alignment.
- Option to clean chapter title (remove prefixes like "Chapter 5:", leaving chapter names only).
- Option to show in file manager (displays last book's data).
- Quick access via taps and gestures shortcuts.

## Tested On:

- KOReader 2025.10 with Kobo Libra Colour & Kindle PW 10th Gen.

## Notes:

- Adding custom icon sets: Create folders in ‘customisable-sleep-screen-iconsets/’ using the same naming structure as existing icon sets. Supports PNG, JPG, and SVG formats. SVG files will be automatically recoloured when the recolour option is enabled in settings.
- Adding custom font faces: Add .ttf/.otf files to koreader/fonts/.
- Quick access shortcuts: Add preset switching and settings access to your KOReader taps & gestures. The options can be found in the taps & gestures general category.
- Better visibility: Enable "Postpone screen update after wakeup" in settings to show sleep screen with front-light when waking up the device.

## Installation:

1. Download the latest files.
2. Copy files to your KOReader directories:
	- ‘2-customisable-sleep-screen.lua’ → ‘koreader/patches/’
	- ‘customisable-sleep-screen-iconsets/’ → ‘koreader/icons/’
	- ‘customisable-sleep-screen-fonts/’ → ‘koreader/fonts/’
3. Restart KOReader.
4. Enable the patch:
	‘Settings → Screen → Sleep screen → Wallpaper → Customisable sleep screen’
5. Configure settings:
	‘Settings → Screen → Sleep screen → Customisable sleep screen settings’

## Icons & Attribution

This project includes icons from the following sources. Some icons were edited from their original sets for this project.

- Default icons: [Solar]([https://www.figma.com/community/file/1166831539721848736](https://www.figma.com/community/file/1166831539721848736)) - licensed under CC BY 4.0.
- Pixel icons: [Pixel]([https://www.figma.com/community/file/1196864707579677521](https://www.figma.com/community/file/1196864707579677521)) - licensed under CC BY 4.0.
- Sketch icons: [Doodle]([https://www.figma.com/community/file/1019353050314527791](https://www.figma.com/community/file/1019353050314527791)) - licensed under CC BY 4.0.
- Silhouette icons: [MaterialDesign]([https://github.com/Templarian/MaterialDesign](https://github.com/Templarian/MaterialDesign)) - licensed under the Apache 2.0 License.
- Comic icons: Custom icon set created for this project.

## Fonts & Attribution

This project includes fonts from Google Fonts, used under the [SIL Open Font License]([https://scripts.sil.org/OFL](https://scripts.sil.org/OFL)). OFL license files are included in ‘customisable-sleep-screen-fonts/’ for each font.
