# Photoshop Notes

# NEVER save over an original photograph file. Always use Save As

## TURN OFF Maximize Compatibility when saving or files will be double in size/too large

## General

- don't keep too many tabs/files open, uses a lot of memory and slows down computer
- to switch colours in colour panel [bottom left][x] key
- OPT + Click on group layer to see objects within it on screen
  **Adjusting Canvas**
- to expand canvas size to include image/design
  - Image menu
  - Reveal all
- manually can be done too
  - Image menu
  - Canvas size
  - click on relative
  - add pixels needed
  - can also change where to place them, i.e on grid click bottom right square[arrows point up and diagonally] to ensure pixels added to top and left side
- eyedropper tool[I] or caps lock key for crosshair cursor for more accurate colour choosing

SHIFT + RETURN to highlight first number to be adjusted in any adjustment panels
SHIFT + F to see image in full screen

## Opening Files

- **.png .jpg .dng .psd .tiff** all open in Photoshop
- sometimes Preview will open the files instead of PS so right click and click Open with PS

- \***\*Adobe Bridge\*\*** --> File --> Open in Bridge
- Content space has thumbnails for files (can change size of them at bottom of screen slider bar or click on a file and use [CMD +/-])
- Can Drag and Drop folders to navigate to it --> make it fav location
- For large screen preview of file
  - click on file
  - View menu
  - Full Screen Preview
  - to exit preview, click esc key
- **Filter** tab to select different file types, keywords, date added/created, etc.
- can use star ratings for your images (can also filter them this way)

- \***\*Camera Raw\*\***
- DNG is Adobe's raw standard file, supported by a lot of cameras including iPhones
- think of this as being a utility that is hosted either by Photoshop or by Bridge.
- can only open DNG, JPG and TIF files, does not support layers like PSD and PNG

#### Or

- highlight files
- go to **File** --> **Get Info** (CMD i)
- **Open With** dropdown menu
- select **Photoshop**
- Then click on **Change All**

### File Types

- **JPEG** is a compressed file format, it uses lossy compression in order to keep down the file size, and it's great for flat photographic images. JPEG files are always flat, no layers.

- **PNG** is also great for photographs as well as designs, does not apply lossy compression and it is very common on the web, and for mobile devices. PNG files can have translucency associated with them, but not really layers.

- **TIFF** is traditionally a print production format, owned by Adobe. TIFF files can contain layers, most people don't use them for that purpose

- **PSD** which stands for Photoshop Document and it is most commonly used for layered files. When you're saving your layered documents you want to use PSD.

# Navigation

### Zoom page

- zoom in [CMD +] zoom out [CMD -]
- fit to screen [CMD + 0]
- to zoom 100% [CMD + 1]
- zoom tool [Z] --> click on area you want to zoom in --> zoom out hold OPT key and click
- **SHORTCUT switch btwn tools**
  - zoom in CMD + spacebar and hold CMD or OPT + spacebar for zoom out
- **Scrubby zooming** press and hold [Z] key and drag mouse **left** for zoom out and **right** for zoom in
- **Marquee Zoom** press and hold [Z] key --> uncheck scrubby zoom at top menu --> make box around are you want to zoom to with mouse
- to zoom with mouse --> OPT + scrollwheel

#### Panning

**Hand Tool** [H]

- temporary hand tool use **spacebar**
- flick panning --> hold spacebar and then push/pull image in a flicking motion and it will fluidly move in that direction

#### Other Scrolling Tricks

**Bird's Eye View**

- hold [H] key and click and hold mouse button --> select area you want to work on

**Two Images Open [side-by-side]**

- have 2 open tab files
- go to **WINDOW** menu --> **ARRANGE** --> **2-up Vertical**
  - to view 1 image again **WINDOW** menu --> **ARRANGE** --> **Consolidate All to Tabs**
- to drag/pan both images at the same time SHIFT + SPACEBAR

**Overscrolling**

- to turn on -->Photoshop menu --> Preferences --> Tools --> check Overscroll box

### Cycle Images

- CTRL + TAB to move between image tabs [also CMD + ~]
- reverse direction is CTRL + SHIFT + TAB

### Screen Modes

- standard screen mode [F] or button on bottom left of tool panel [screen icons] --> SHIFT + F for reverse cycle
- full screen mode with menu bar --> no tabs or scroll bars visible, larger screen area
- full screen mode --> no panels or menu but can still cycle through open tabs with CTRL + TAB--> press ESC to exit
- to hide LEFT and RIGHT panels --> TAB
- to hide RIGHT panels --> SHIFT + TAB

### Navigator Panel

- WINDOW menu --> NAVIGATOR [helm icon ]
- you can drag the red box around the image to show a specific area
- hold CMD key to zoom

# Layers

- to turn off all layers but one you are selecting --> hold OPT key and click eye icon
- move tool [V]
  **Flat Background into Layer file**
- to change background to a layer --> click on **lock** icon and then rename OR
  - double click on background layer and rename when box pops up, click ok-- will now be a layer

**Object Selection Tool**

- under lasso tool
- after selecting it, change mode on top drop down menu to **lasso** and trace/draw around object you want to select
- **Layer via Copy** CMD + J to add lassoed object to its own layer --> but must rename in another step
- to make layer and name at same time CMD + OPT + J

**Vector shape**

- make outline with pen tool?
- go to LAYER --> New Fill Layer --> choose colour

**Deselect** CMD + D

**To Select Path/Layer** to make mask

- hover over layer [hidden layer?] and use CMD + CLICK--> small square icon appears with mouse
- layer path now selected --> shortcut for right click and Select Pixels
- select other layer to be masked --> click on mask icon at bottom [rectangle with hole in it- add layer mask]
  - to see mask in more detail, click layer then OPT + click
  - to go back to full image, click on other layer
  - SHIFT + Click on mask layer to turn off temporarily
  - to unmask a certain area --> Rectangular Marqee Tool [M] --> Edit --> Fill --> change to Foreground Color or White --> Shortcut **OPT + Delete** to make white [foreground] OR **CMD + Delete** to make black [background]

**Clipping Mask**

- select textured layer and make sure it is above shape layer it is to be clipped to
- click burger menu in layers panel --> Create Clipping Mask OR Shortcut **OPT + CMD + G**
  - to give texture to a smaller area outside original mask area
  - select Marquee tool [M]
  - make rectangle around texture
  - click on layer that contains that texture
  - CMD + OPT + J to create and name new layer
  - drag new layer to top of layers panel
  - switch to move tool [V]
  - drag marqeed rectangle layer over object to be masked with texture
  - check if object is fully covered by using opacity
  - hover over line between the 2 layers to be clipped --> hold OPT key until you see square icon --> then click!
  - OR just click on burger menu and select Create Clipping Mask
- clipped layers are indented and have a small arrow pointing down

**To Merge 2 layers**

- click on layer to merge
- click on burger menu
- click **Merge Down** [CMD + E] --> make sure layer below is one you want to merge with
- Photoshop accepts name of lower layer so make sure it is named correctly

**Auto Select Layer Option**

- selects whichever layer is under your cursor --> warning! You may move something you don't want to!
- With MOVE TOOL selected
  - select item you want to move in layers panel --> then unclick Auto Select at top --> now wherever you drag, you will only move the item you selected in layers panel
  - alternatively --> with Auto Select off --> to select a different layer --> RIGHT click and then select item from list that pops up
  - to drag item around use CMD + hold to reverse the Auto Select behavior without turning off

OPT + click to see mask layer

**To Mask Item with Brush Tool**

- select brush tool --> resize by right clicking --> hardness 100% and size to whatever you need
- invert colour to black and click where you want mask
- select mask layer in layer panel
  - Image
  - Adjustments
  - Invert [CMD + I]
  - now mask will show area you masked off properly and show on your image

**Heal Tool**

- Spot Healing Brush Tool [J]
- right click to bring up options
- make sure Sample All Layers checkbox is off and Type is set to Content Aware

# Layer Effects

- fx button at bottom of layers panel --> option box opens
- Gradient Overlay

  - click on GRADIENT drop down menu
  - Basics and select first square
  - change Blend Mode from Normal to Screen
  - Opacity down to 15%

- Inner Shadow -left menu and click

  - Opacity 100%
  - Distance 20px
  - Size 10px to create shadow size
  - OK --> effects now listed in layer panel
  - to change settings again, just double click on one of the effects

- to add Shadow

  - click on FX button again
  - select Drop Shadow
  - Opacity 100%
  - Distance 10 px
  - Size 10px

- Softening a mask with FEATHER on vector graphic
  - select object mask to be changed
  - WINDOW menu --> Properties OR select Properties icon on left panel menu [squares]
  - select vector based mask not pixels [so square icon on right with anchor pts]
  - adjust FEATHER slide bar [0.5px]
  - to adjust on another object, just select that layer with the Property panel still open
  - Feather adjust again [1px]
  - close panel when done

# 3 Ways to Copy and Paste Layers

1. Copy and Paste shortcuts COPY[CMD + C] PASTE[CMD + V]
   - select layer you want to copy --> Shift Click second layer if you have more than one thing
   - this method centres the text on image window when it is pasted [depends on how you are zoomed in/out]

- Copy as before but instead of normal Paste [CMD+V]
  - go to EDIT
  - PASTE SPECIAL
  - PASTE IN PLACE [SHIFT + CMD + V]

2. Move Tool to Copy and Paste
   - select layers to be copied
   - Auto Selected checkbox OFF
   - drag items outside image window and onto title tab of file you want to paste into
   - release mouse and drop where you want

- to drop items where they originally were located in other file
  - press SHIFT key then release

3. Single Command [mostt elegant method]
   - select layers to be copied
   - rectangular marquee tool
   - right click on image to open option box
   - DUPLICATE LAYERS
   - select other open file in drop down menu where it is to be pasted

- this option is also available in the Layers menu --> burger menu and select Duplicate layers

# Auto Zoom one or more Layers

- select an object in the layer menu
- View Menu
- Fit Layer(s) On Screen

- can select more than one layer

  - shift click 2+ layers
  - same process as above

- OPT + Click on a layer for a shortcut to above
  - just be careful with which layers you are clicking on [accidentally click mask instead of object]
- SHIFT + OPT + Click to select more than one object to zoom on [not working currently]

# SAVE

**5 Essential Things to Know About Saving**

1.  The meaning of asterisks (..., RGB/8*)* in title tab

    - inner asterisk just tells you the image is using a different colour space than photoshop is using by default

    - asterisk ouside brackets tells you that there are unsaved changes to your work

2.  Undoing a save (or PSDC(cloud) auto-save)

    - sometimes save accidentally using CMD + S
    - Go to WINDOW menu
    - choose History --> panel pops up on right menu
    - select which move you would like to go back to

      - if OPEN state is no longer visible (more than 50 moves away)
      - click on Document title at top of history
      - it is saved by default when you open file so clicking on this reverts to original file
      - then CMD + S or save file again where step you wanted to specify is OR

3.  Undoing a revert

    - if you click revert (accident or no) it will save the bad save and not allow you to make changes in history--> all gone
    - to undo
      - Edit menu
      - Undo Revert [CMD + Z]
      - brings back history and last save

4.  Auto-saving

    - Photoshop menu
    - Preferences
    - File Handling
    - Automatically save recovery information: every 5 min

5.  Saving on close/quit

    - if you exit Photoshop, warning will pop up asking you if you want to save progress if unsaved
    - Yes, save changes before closing if you forgot!
    - History will be gone, only lasts as long as your work session

**Saving in PSD format**

- Save As [SHIFT + CMD + S]
- in save option box...
- Layer box is checked on

* Maximize Compatibility Option

  - creates a flat layer that other programs can read
  - not needed for Adobe programs so uncheck box for smaller file sizes
  - no need to save like that unless trading files with Lightroom or Premiere

    - to turn off
    - go to Photoshop menu
    - Preferences
    - File Handling
    - Maximize PSD and PSB[very very large imagery] file compatibility [Never]

**Saving a flatprint image to TIFF**

- TIFF stands for tag image file format
- save as
- drop down menu TIFF format
- UNCHECK LAYERS BOX
- save as copy fine b/c no layers
- ICC Colour Profile on for consistent colour
  - after clicking save new option box pops up
  - TIFF supports lossless compression so nothing lost
  - LZW option [checked]
  - Save Image Pyramid [unchecked]
  - Pixel Order [Interleaved]
  - Byte Order [select PC or Mac but doesn't matter really]
  - OK when done

**Saving an interactive image to PNG**

- Portable Network Graphics format [PNG] pronounced PING
- popular for interactive design, mobile and web based images
- supports full colour images, lossless compression; compression applied automatically unlike TIFF
- can assign transparency as well
  - save as
  - no need to check any boxes like save as copy because no choice but to save it without layers anyway
  - once you press save, new option box pops up
  - choose file size/speed

**Saving a flat photograph to JPEG**

- Joint Photographic Experts Group
- ideally suited to archiving continuous-tone images such as photographs
- it doesn't support layers.
- it does support full-color images, it does not support transparency and it always applies some degree of lossy compression. Meaning that it rewrites the pixels and makes images much smaller
  - FILE
  - SAVE AS
  - SAVE --> Option box pop up
  - Quality Maximum [12]
  - Baseline Optimized - lossless compression (smaller file size)
  - OK

# Brightness

- Photoshop sees Grey scale only luminance data

  - darkest colour is black[shadows]
  - lightest colour is white [highlights]
  - shades in between are [midtones]

- 3 channels of primary colour information

  - red
  - green
  - blue

- to begin adjusting a photo
  - identify the brightest and darkest spots
  - click on CHANNELS panel
  - select eyedropper tool [i]
    - to change cursor to crosshairs, click caps lock key
  - click flyout menu on top of color panel
  - select HSB[Hue/Saturation/Brightness] sliders
  - you can see the percentage of shadows and highlights missing from the image by using crosshairs on lights and darkest spots
  - limited range of luminance

**Colour Corrector tools**

- IMAGE menu
- AUTO CONTRAST
- corrects the missing percentages of light and dark very quickly

### The Three Auto Commands

- **Auto Tone:** finds the darkest pixel on a channel-by-channel basis and changes it to black and also finds the lightest pixel on a channel-by-channel basis and changes it to white. Colour cast is affected, i.e green tone removed from dollar bill, more reddish shadows

- **Auto Contrast:** also looks at the darkest and lightest pixel but does it on a composite basis, not channel-by-channel. So it just finds the darkest pixel, makes it darker, the brightest pixel, and makes it brighter. Colour cast is maintained

- **Auto Color:** It's going to take the darkest/brightest pixel on a channel-by-channel basis and make it black/white and neutralize it as well so that it doesn't have a color cast. And then it's going to try to find an exact mid-tone and make it neutral as well. And when I say neutral, I mean leech the color out of it so that it's grey

  - all three of which look at the luminance data on a channel-by-channel basis and make changes automatically without even bringing up a dialogue box

  - act differently for different photographs depending on the RGB layers within the image. Experiment with all 3 to see which produces the best result

**Auto Brightness/Contrast**

- can't use 2 of the Auto commands on one image, though it may seem like combining 2 will produce a nice result
- instead, use an adjustment layer
  - Image Menu
  - Adjustments
  - Brightness/Contrast
  - dialogue box opens
  - select Auto
  - OK
- sometimes the Auto Brightness/COntrast option goes too far and produces an awful result but you can adjust manually to correct it
- also you can fade the affect
  - Image menu
  - Fade Brightness/Contrast
  - Adjust Opacity value in dialogue box

**Custom Brightness/Contrast**

- modify luminance levels in jpg
- Image Menu
- Adjustments--> Brightness/Contrast
- click Auto in dialogue box and then make any more adjustments if you would like
- DO NOT use LEGACY - old adjustment levels not very good

**Dynamic Adjustment Layer**

- use a layer to make changes instead of making them to original image --> easier to adjust and mistakes won't affect original
- known as non-destructive modification layers
  - 2 ways to apply them
    1.  circle icon [b&w]at bottom of layers panel and select from second section of menu
    2.  Window menu -->Adjustments --> panel opens on right side
    - icons instead of menu but same order

Tips and Tricks

- you can open a saved image and change the adjustments you made in HISTORY panel
- click on icon with plus sign at bottom of History panel and you can create a new document from current state of image
- opens image in new tab

To Name Layer while you create it [3 ways]

1. Layer Menu --> New Adjustment Layer --> Brightness/Contrast and an option box pops up where you can name layer
2. Adjustments panel --> instead of clicking on Bright/Contrast icon --> OPT + Click --> Name layer in option box
3. Hold OPT key --> Click on b&w circle icon at bottom of layers panel --> drag up to Bright/Contrast --> Name layer in option box

SHIFT + RETURN to highlight first number value to be adjusted in any adjustment panels

# Adjustment Layers and Blend mode

**Blend mode** found in layers panel drop down menu

- Normal is default setting
- preview on the fly so you can hover and see changes on your image before applying it
- **4 important blend modes**

  - use **Multiply** not Darken to make image darker --> offers smoother results in dark options
  - use **Screen** not Lighten to make image lighter --> best option in the brightening group of options
  - **Overlay** best in the Contrast[3rd] group, increases images contrast
  - use Opacity to tone down some enthusiasm of the adjustment layer
  - **Luminosity** best to use to adjust luminosity, not colour when Bright/Cont affects colour

Lesson info

- double click on adjusted layer to bring up option box
- make brightness and contrast 0
- will adjust image using blend mode instead
- when using blend modes, you are using the image to do something to itself

# Histogram

- is a column graph of luminance levels inside your image from black on the left to white on the right
- Window menu
- Histogram show up on right panel above layers
- click on hamburger menu and choose expanded view
- switch channel from COLORS to LUMINOSITY to see luminance levels from black[left] to white[right]
- you do not want to see clipping in histogram

  - spike at the beginning of the graph[left] means you have clipping in the black area which are the shadows
  - spike on right side[white] then you have blown highlights in the image
  - if you have clipping on both sides, clipped shadows and clipped highlights
  - ideally should look like a mountain range with some nice soft foothills at either end

- you can update Histogram after you adjust by clicking the caution triangle on top right of graph
- you can check the different channels --> RGB

  - if there are gaps in the graph, pixels are missing at that specific luminance level [normal so don't worry unless there are too many --posterization]

**Isolate an adjustment with a layer mask**

- Turned off Automatic Adjustment Layers earlier
- Window --> Adjustments --> menu on right panel --> Add Mask by Default
- better off not to use it this way, you can paint mask off using brush tool and black/white

- now when you create an Adjustment Layer, it will not include the Layer Mask --> good
- if you do want to add a layer mask later --> click on icon at bottom of layers panel [white rectangle with hole in it]

* to convert a Selection Outline Tool to a Layer Mask on the fly
  - click and hold on Object Selection tool --> Select Quick Selection Tool
  - adjust size if needed
  - paint all around object to select background
  - to make the adjustment layer and name it --> hold Option and click adjustment icon
  - you can now adjust background brightness or other options without affecting main object
  - to feather the edge of the mask, in adjustment panel click on the mask icon and then adjust feather with slider in properties panel

# Balance

**Colour Cast VS Colour Harmony**

- identify the colour cast of a photo to correct
- do this by checking with the eyedropper tool [I]
- click and hold on an area of image --> new foreground colour on top of circle, old foreground colour on bottom
- look at COLOR menu on right panel
- click menu and select HSB sliders to see Hue, Saturation and Brightness values
- you can see which colour is cast over image--> you will want to take it in the complete opposite direction i.e cyan to red

**Correcting Colour Cast Automatically**

- Eyedropper tool to find a neutral colour
- use Auto Tone, Auto Color to see what Photoshop does automatically
  - sometimes not much difference or it doesn't work well so you need to adjust manually
- so try Colour Balance command

**Colour Balance**

- passes off as being easy but can be challenging
  - Image Menu
  - Adjustments
  - Colour Balance
  - dialogue box with options pops up --> 3 sliders with cyanto red, magenta to green, yellow to blue.
  - move sliders away from the dominant colour --> goal is to extract that colour to balance the image
  - pay attention to the percentages of HSB on right panel --> goal is to lower the saturation/ highlights and move colour away from dominant cast

Last Applied Settings

- if you choose colour balance option again, options will all be at 0 again. If you need to change something, you need to access the last applied settings
  - create a copy of the original image by OPT + Drag to top of layers
  - hold OPT key --> Image menu --> Adjustments --> Colour Balance
  - old settings will now be displayed
  - you can now readjust the balance on the copied image
  - then you can toggle layer off and on to see the previous adjustments to see if image is improved

**Correcting White Balance in Camera RAW**

- click on Camera Raw layer in layers panel [if you have different layers]
- go to FILTER menu --> Camera RAW Filter
- you can use the same HSB sliders as in Colour Balance but they are much more effective in RAW format
- instead of the sliders, there is another option

  - in top menu bar there is an icon for the White Balance Tool [shortcut of I like eyedropper tool but only used in Camera RAW filter box]
  - purpose of this tool is different, it isn't sampling a colour the way the eyedropper tool does
  - it is setting a point of neutrality
  - to choose a neutral point, you shouldn't click on an area that is dark nor light
  - you want to find a light grey within the image
  - you can click on a spot but you can also drag the tool to create a marquee on a small area and take all those pixels into consideration

- sometimes image gets brightened up too much when adjusting/ washed out
- to fix it go to EDIT menu
- select the Fade Camera RAW Filter to back off the adjustments slightly
- you don't want to affect Opacity at this point or the colour cast will come back
- change the mode in drop down menu --> Colour
- will darken image back up again and affect colours not luminance level

**When Camera RAW disappoints**

- if you have used Camera Raw Filter in the same sitting as a new image, do not select it when you are working on a new image. It will place the same adjustments on the image as the last one you were working on.
- Filter Menu
- Camera Raw Filter ... [use one with 3 dots]
- use eyedropper tool and select a small area where you think is neutral
- adjust sliders to suit
  - to preview previous image settings [original] press the P key [preview] in the filter view
- not the best edit to the image...other ways

**Adjusting a Colour Cast with Photo Filter**

- Opt + click on b&w circle at bottom of layers panel to make a new adjustment layer
- select colour balance and name layer
- adjust colour balance away from dominant colours i.e if image is blueish, move from cyan to red
- adjust sliders in all 3 Tones : Highlights/Midtones/Shadows

- need to use a photo filter to correct
- use eyedropper and find colour value you want to defeat
- add another adjustment layer by using OPT + layer icon and select Photo Filter
  - once you know you degree for the hue, you will choose the colour option in the dialogue box, input your H value and then +/- 180 to get the opposite colour to defeat dominant colour
  - if value is smaller than 180 degrees you + 180
  - if value is larger than 180 you -180
  - do math right in the H box and photoshop will calculate value

**Applying Auto Colour Nondestructively**

- Opt + click and add new adjustment layer and name
- select Levels
- you will see a histogram in the properties panel
- click on burger menu
- Auto Options
  or
- Click OPT + Auto button
- 4 algorithms options
- each one is one of the Auto options, hover over them to see which one
- for image in lesson, select Find Dark and Light Colours
- also check box Snap Neutral Midtones
- also clip some highlights to brighten--> up to 1%
- click on Midtones swatch and adjust until content
- DO NOT CLICK SAVE AS DEFAULT

# Cropping

- use crop tool to cut image to desired size and shape. Sometimes it is better to take a photo far away in order to resize and crop image to your liking later on

- Crop tool without deleting pixels (non-destructive)

  - when using crop tool, uncheck box at the top of the menu that says "Delete Cropped Pixels"
  - you can go back later and adjust crop if something is off

- You can rotate the image if the horizon isn't straight or if the photo was taken at an incorrect angle

  - hover near crop corners and look for curved arrow, rotate to your needs
  - when you rotate, it is destructive, all pixels are re-written when image rotated

- you can use move tool to move image within cropped boundaries if you need to adjust

- press and hold spacebar while dragging crop tool to move the marquee

**Aspect Ratio**

- if you shift click and drag crop, it will flip and go from vertical to horizontal and visa versa
- can also select predefined ratios on the top menu drop down menu
- if the ratio selected is in the incorrect layout, there is a swap button on same top menu
- if you want to abandon the aspect ratio selection, just click on clear on top menu

- different grid patterns available for the crop selection

  - rule of 1/3 (default)
  - golden ratio
  - normal grid lines [helpful to determine if image is crooked or not]
  - many more

- change settings in grid format to **Auto Show Overlay**

  - fades the background/cropped area outside until you move crop selection
  - easier to visualize the cropped final image

- if you always want image to stay centred on screen while moving the crop selection

  - go to settings icon at top
  - turn off **Auto Center Preview**

- **reference point** is the centre of any rotation you apply to an image
  - DEFAULT point of reference is centre
  - hold OPT key and you can see small arrows
  - OPT + click on an area to set the new rotation point of reference
  - to make reference point visible
    - Photoshop menu --> Preferences --> Tools
    - check box that says **Show Reference Point when using Transform**

**Finessing a Crop with Canvas Size**

- when cropping and there are areas left with the transparent background due to rotation
- CMD + K to open General Preferences Panel
- Units and Rulers
- change Rulers to Pixels
- switch to [M] rectangle marquee tool
- measure height value of area to be fixed and add them up
- go to IMAGE menu
- click on Canvas Size
- turn on Relative check box
- add in number from top height and click bottom dot on the diagram
- click okay and it will crop the top section of the image
- do the same for the bottom but click on top dot to crop from bottom
