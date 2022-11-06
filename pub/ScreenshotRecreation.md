---
layout: page
title: "Screenshot Recreation"
permalink: /screens
---

## Examples

The accuracy of recreations is constrained precisely by the ability to verify their accuracy. Older Half-Life 2 screenshots are a useful resource for finding little details that are different, which would never be prominent enough to be discovered otherwise. This paves the way for better quality recreations. Some examples:

![](Assets/hltv.gif)
![](Assets/soldiers2.gif)
![](Assets/zombie.gif)
![](Assets/borealis_01_full.gif)

## Making your own Screenshot Recreations

Creating screenshot recreations requires a tool that can overlay separate windows with transparency, or a way to seamlessly change between windows. I use Glass2K for Windows, which allows me to use Ctrl+Shift+1 and Ctrl+Shift+0 to make the window transparent.

Without this, it won't work. High accuracy requires that nothing be in the way of directly comparing the two screenshots in the alignment process.

### Hammer

You might benefit from my guide on opening [Leak maps in Hammer++](https://hl2-beta.ru/index.php?topic=29375.0), and my [VMF updater mappack](https://drive.google.com/file/d/1K2g9dOyZ3vfHuxG3NifWzpw6oxlNP9-S/view?usp=sharing). The updated maps will require less effort to fix up compared to the unmodified WC mappack maps. 

Before you can create a screenshot recreation, you need to have a (close enough) version of the map shown available. Thus, the first step is to canvass the maps that seem to roughly match the one the shot was taken in until the closest one is found.

I would advise for comparisons to not use fast compilations. This means compilation time can chug - but if we use a cordon to remove everything the player can't see from the screenshot's angle, that's not a problem. 

The map may already have a [cordon](https://developer.valvesoftware.com/wiki/Hammer_Cordon_Usage) - click "Edit Cordon" to interact with it, and "Enable Cordon" to activate it. In order to accurately determine what the player can see, you can drag-select (Hammer++ only) everything in the 3D viewport, and put the cordon around what is selected.

### HL2

Enabling noclip is a must. Many screenshots use it, even if it doesn't look like it. Further, noclip "snaps" to the ground to a certain degree, meaning it can even serve as a more precise way to "walk". 

Valve's screenshots use both <code>fov 75</code> and <code>fov 90</code>. If you can't seem to get the rough look of it right, try changing it between these two, or others. 

### Getting it Right

An important aspect of getting the alignment right is being able to increase your precision of movement as you get it closer. These commands are important for it:

* sv_noclipspeed
* sensitivity

For further degrees of freedom in movement, you might want to <code>bind</code> a key to <code>+moveup</code> and <code>+movedown</code>. This allows you to adjust your vertical position without 

It's easy to get myopically focused on comparing one area of the screenshot. Avoid this! If you are looking at one area, it's easy to let another slip. Try to get 3 or so different areas across the screenshot roughly there. Then, you can perfect one, perfect the other, fix any issues with the first, and repeat this for the third.

As adjustments become more precise, you might want to compare the screenshots directly and plan out where you want to move. Simply unconsciously adjusting might leave you further away from accuracy than you were. 

There is never perfect perfection, but if you can get it to the point where the screenshot stops "moving" between the comparisons, that's quite enough. 

Before you finish, type <code>getpos</code> to save your position. If you're feeling nice, bundle it with your comparison to make it easier for succeeding users to get back where you were. 

### To GIF

Paint.NET: (I've been using this)[https://forums.getpaint.net/topic/118869-gif-animations-and-images-filetype-plugin-gif-agif-latest-v15-2021-11-16/]. I set the "Delay" to 500 when saving, and set the loops to 0 (why should it stop animating?). This maintains the limitation of the 256 color palette, but is still useful.

I use ezgif.com. Put both of the parallel screenshots together and then set the "Delay" to 50. Feel free to suggest something better. I prefer there be no blending frames between the two screenshots, because it makes it more difficult to spot differences.

## Prior Work

d1_borealis_01_full (noclip, 1024x768): setpos 540.532837 -157.764374 -198.184235;setang -1.157436 153.446045 0.008447

2001_borealis_hltv (1600x960(?)[^1]): borealis_003 (No coords, I wasn't satisfied enough to save them.)

soldiers (noclip, 1024x768): d3_borealis_05: setpos 474.040497 352.175690 -231.272766;setang -5.733209 220.825195 0.000001

zombie (2048x1536): d3_borealis_05_005: setpos 609.607422 102.029625 -255.968750;setang -6.403040 194.886475 -0.000071

brown comboner c1a3a_port: fov 90; setpos -867.965271 -1092.916748 288.031250;setang 37.437645 160.565186 0.000000

valvetime c1a3a_port (noclip): fov 90; setpos -334.547333 -2934.202881 309.520599;setang 29.903189 288.775635 0.000000

[^1]: This needs to be specified in the launch options.
