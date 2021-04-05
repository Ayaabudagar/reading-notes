# **color**
The <color> CSS data type represents a color in the sRGB color space. A <color> may also include an alpha-channel transparency value, indicating how the color should composite with its background.

A <color> can be defined in any of the following ways:

Using a keyword (such as blue or transparent)
Using the RGB cubic-coordinate system (via the #-hexadecimal or the rgb() and rgba() functional notations)
Using the HSL cylindrical-coordinate system (via the hsl() and hsla() functional notations)

Syntax
The <color> data type is specified using one of the options listed below.

Note: Although <color> values are precisely defined, their actual appearance may vary (sometimes significantly) from device to device. This is because most devices are not calibrated, and some browsers do not support output devices' color profiles.

# **Color keywords
Color keywords are case-insensitive identifiers that represent a specific color, such as red, blue, black, or lightseagreen. Although the names more or less describes their respective colors, they are essentially artificial, without a strict rationale behind the names used.

There are a few caveats to consider when using color keywords:

HTML only recognizes the 16 basic color keywords found in CSS1, using a specific algorithm to convert unrecognized values (often to completely different colors). The other color keywords should only be used in CSS and SVG.
Unlike HTML, CSS will completely ignore unknown keywords.
The color keywords all represent plain, solid colors, without transparency.
Several keywords are aliases for each other:
aqua / cyan
fuchsia / magenta
darkgray / darkgrey
darkslategray / darkslategrey
dimgray / dimgrey
lightgray / lightgrey
lightslategray / lightslategrey
gray / grey
slategray / slategrey
Though many keywords have been adapted from X11, their RGB values may differ from the corresponding color on X11 systems since manufacturers sometimes tailor X11 colors to their specific hardware.