# Stickerfy

Stickerfy is a GIMP plugin that modifies images into proper WhatsApp' sticker
standard. It scales the image to 512x512, gives them 16px wide margins, adds a
solid color background that extends 8px outwards and adds a drop-shadow. It
supports GIFs as well, so in the end you can export the project as a GIF (or as
an animated WEBP if your sticker-pack client supports it).

## Installation
### As well as others GIMP plugins, just paste stickerfy.py on your plugins folder.

Windows: ```%APPDATA%\GIMP\2.10\plug-ins```

Nix: ```~/.config/GIMP/2.10/plug-ins```

## Stickerfying

With an open image on GIMP, go to **Filters > Plug-ins > Stickerfy...**
Select the interpolation method and the sticker's color of your choice.
