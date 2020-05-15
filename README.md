# Elian Bitmap Serif

This is a serif, bitmap font for the Elian script for English-like languages. It's licensed under the [SIL Open Font License 1.1](https://spdx.org/licenses/OFL-1.1.html), which affords you certain rights.

## Development notes

Goals:

- [x] Elian uppercase
- [x] elian lowercase
- [x] imagemagick [montage](https://www.imagemagick.org/Usage/montage/) command to assemble individual images into a grid
- [x] and output a text file for the use of https://yal.cc/r/20/pixelfont/
	- [x] based on filenames
	- [x] through lookup table
- [x] make sure mogrify and php have same sort order
	- bash globbing goes a A b B comma c C d D
	- php scandir goes A B C D a b c comma d
- [ ] numbers
- [ ] full punctuation (4px basis, hollow)
- [ ] apply serifs


Thanks to the following sources:
- https://yal.cc/r/20/pixelfont/
- https://silnrsi.github.io/FDBP/en-US/Characters_and_Glyphs.html
- https://scriptsource.org/cms/scripts/page.php?item_id=entry_detail&uid=gg5wm9hhd3
- https://github.com/adobe-type-tools/agl-aglfn/blob/master/aglfn.txt
