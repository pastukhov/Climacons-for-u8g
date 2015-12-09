# Climacons for u8g library

Maked from https://github.com/christiannaths/Climacons-Font.git

```
otf2bdf -p (icon size)  climacons-webfont.ttf -o climacons-webfont_(icon size).bdf
bdf2u8g -l 448  climacons-webfont_(icon size).bdf u8g_font_climacons(icon size)  u8g_font_climacons(icon size).c

```

Icons are located between 32 and 73 symbol