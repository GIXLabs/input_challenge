# Making a basic laser enclosure (no design experience needed)
1. [Open up a box generator.](https://en.makercase.com/#/basicbox)
    1. We recommend using a thickness of 0.125 inches.
    1. Adding fingers will make assembly easier. Change the "Edge Joints" to fingers. Finger size doesn't matter much, but the more fingers you have, the harder it will be to fit together.
    1. Change the size of the box. The default box is huge, so you may need to change the dimensions to fit the printed circuit board (PCB).
    1. Download files as svg. No need to change any of the other settings.
1. Ask a member of staff to invite you to the Glowforge system. You will need to sign up for an account, but it is free. Please skip any features that ask for a credit card.
    1. You will get an email and you'll need to click "Click here to get started." Feel free to skip the tutorials.
1. "Create a new design" and "Upload a file" in the [Glowforge interface](https://app.glowforge.com)

    ![Image of Glowforge home screen](/assets/glowforge_home.svg)

1. Find the 1/8" Birch Wood in the laser material storage and put a sheet of it in your laser on the black honeycomb tray. Position doesn't matter much, and you can close the lid once you have the piece in. If you can, try to use pieces that already have something cut out of them. The numbers in the top right of the Glowforge interface indicate which laser is yours. The number on the machine is near the barcode.
1. You will need to set the material to "Medium Cherry Plywood" in the top left of the Glowforge interface. You may have to search using the search box.

    ![Image showing where to select materials](/assets/glowforge_materials.svg)
    
    1. Greyed out parts are ones outside the Glowforge's cuttable area and will need to be moved onto the material.

1. Add [button holes (copy and paste to get multiple)](button_hole.svg), [potentiometer hole](potentiometer_hole.svg), and [micro-USB hole](usb_hole.svg). There is a download symbol on each of these pages that you'll need to use. You may also want this [rectangle](rect.svg) and [circle](circle.svg) file, which you can stretch and resize in the Glowforge interface.

    ![Image of Glowforge interface](/assets/glowforge_add.svg)

1. In the Glowforge interface, click and drag those holes around on the generated box pieces to place them where you want them. Be careful not to accidentally scale the pieces.

1. Set the text to "Ignore."

    ![Image showing where Ignore is found](/assets/glowforge_ignore.svg)

1. Make sure that all of your parts are on the material in the laser and are not greyed out. You can box select groups of them and move them around.
    1. If you are using scraps, you can move items you don't want to cut outside the cuttable area. Anything greyed out won't be cut, which is sometimes desirable.
1. Click "Print" in the top right of the interface.

    ![Image showing the Print button](/assets/glowforge_print.svg)

1. Press the big glowing button on the Glowforge and stay to watch your cut. Watching your cut is important as fires are common in lasers.
1. Once the laser has stopped making noise, you can open the lid and pull the parts out (don't worry, they aren't hot).
1. You've made your first box! Test it out and iterate!

# Dimensions
The main board outline is 2.2 inches wide by 2.1 inches deep x 1.6 mm tall. Please pardon the mixed units, but that's just how PCB design is.

# Models
The 3D model for the carrier board (in both Fusion 360 format and STL) are located above. If you are not proficient in Fusion 360, the STL file can be used with TinkerCAD to add features. It will be tough to 3D print something in time, but it could be ready by the time you get back for the happy hour.