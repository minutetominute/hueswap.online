# hueswap.online

## What is Hueswap?
Hueswap is a web app for editing GIF color tables. Upload your favorite GIF, change the colors around, and then download the result!

## Does Hueswap only work with GIFs? What about WEBP/MP4/etc?
Hueswap only works with _real GIF files_ because it relies on the GIF's color table to work. It does not work with any fake pseudo-GIF formats like WEBP. (Fortunately there are free tools online for converting WEBP and similar formats into real GIFs.)

## What are color tables?
The way GIFs handle color info is fairly unique — it's called [indexed color mode](https://en.wikipedia.org/wiki/Indexed_color). This means that every GIF* contains an index (or list) of all the colors used in the image. This index is called a color table.

Hueswap hacks directly into a GIF's color table and lets you change the color values, leaving everything else unchanged. The arrangement of the pixels remains the same — only the colors change.

## Who is responsible for this?
Hueswap was developed by Jos&#233; Garza and Benjamin Berg, based on a concept by Benjamin Berg.

_* It is possible to create a GIF that has no color table (or more than one), but quite rare._
