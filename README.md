# Adobe PDF Profiles for Scientific Publishing
 This repo contains some profiles I use to generate publication-quality PDF files for scientific journals. These files are usually submitted for production.

## Illustrator - PDF Presets
### Clean PDF (600 dpi, sRGB)
* Downsamples all color bitmaps to 600 dpi and monochrome ones to 1200 dpi
* Converts the color space to sRGB and embeds the color profile
* Due to Illustrator's limitations, you must manually uncheck "Preserve Illustrator Editing Capabilities" on every save to remove Illustrator-specific information (such as layers)

## Acrobat - Preflight Profiles
### Journal Figure [PDF_X-1a, FOGRA39, 600 dpi]
* Downsamples all bitmaps to 600 dpi
* Targets FOGRA39 CMYK and claims PDF/X-1a standard
* Removes all non-standard markups (including Illustrator-specific information)