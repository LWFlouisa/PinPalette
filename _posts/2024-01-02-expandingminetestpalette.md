---
title: "Expanding Minetest Painting Palette"
author: "S.R. Weaver"
tags: painting colorpalette toscaandgunmetal
---
![Preview](https://github.com/LWFlouisa/PinPalette/blob/main/Images/MinetestPalette.png?raw=true)

I've just expanded the color palette available for me to use in minetest:

Just as these lines to painting.hexcolors:

~~~lua
    -- My personal color palette.
    mineral = "414c44",
    bastille = "302e35",
    blackrock = "282a36",
    palliser = "775531",
    nightrider = "373133",

    -- Homemade ink color palette.
    revolver = "39363b",
    tosca = "75443f",
    blackpearl = "131d1f",
    bunker = "25292a",
    empress = "796b6b",
    woodbrown = "5b444a",
    barossa = "443135",
    vulcan = "34373c",
    gunmetal = "2f3438",

    -- Colonial Whisper color palette.
    avacado = "97986b",
    hillary = "a4a177",
    chino   = "b1ab84",
    coriander = "beb490",
    vanilla   = "cbbe9d",
    heather = "b4bbc0",
    linkwater = "c3cad5",
~~~

Now add these color name to painting.revcolors:

~~~lua
    "mineral", "bastille", "blackrock", "palliser", "nightrider",

    "revolver", "tosca", "blackpearl", "bunker", "empress", "woodbrown", "barossa",
    "vulcan", "gunmetal",

    "avacado", "hillary", "chino", "coriander", "vanilla", "heather", "linkwater",
~~~

Note however that these colors are a bit more subtle than the ones in the default Minetest painting palette.
