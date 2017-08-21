Latex Package defining glyphs in the unicode range `0x2800..0x28FF`. Sets up
unicode braille patterns for usage with latex.

---
**Note:** Only use this package if you are unable to use a UTF-8 enabled
distribution like luatex or xetex, e.g. when submitting to a conference using a
document class that does not support these engines.

---

This package is based on work by William Park and Dominique Unruh published as
[`braille` package in the ctan
registry](https://www.ctan.org/pkg/braille). 

__Changes from `braille` to `braille-patterns`:__

Repurpose as braille pattern renderer: removal of any braille transcription
engine capabilities, as we believe you should either transcribe by hand or use
a true braille transcription engine like [liblouis](http://liblouis.org/)
instead. Removal of any additional functionality except for basic glyph
rendering.  Addition of a unicode character declaration for each character in
the range `0x2800` to `0x28FF`.
