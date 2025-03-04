# Fysetc Voron 2.4 R2 Pro

When I built my first Voron, I was told that I should buy a LDO kit.  I do not recall if I was given specific reasons, but I do recall hearing things like, it was one of the most complete kits out there, you didn't have to terminate any cables, etc.

So I purchased and built my Voron.  Then months later, other people were asking me about building a Voron.  Just like those before me, I recommended the LDO kit.  It was then shown to me the Fysetc kit.  This kit seemed just as complete as the LDO, and included some upgraded items like TAP that I have since added on mine.

My response was simple.  I do not have any personal experience with that kit, but there must be a reason that everyone recommended to me the LDO kit.  We've all heard the old saying, "You get what you pay for".  But does it really have to be that expensive?

Well now that I have built LDO kits for V2.4, Trident and Switchwire, and have added some upgrades, I figured perhaps I need to personally look into this Fysetc kit to see is this something for a first time Voron builder to get them started into the wonderful world of Voron without the high entry price tag of a LDO kit?  Is this kit "good enough"?  Well with it being about 2/3 the cost of the LDO, and Fysetc having a sale, I purchased one to find out if this is beginner friendly enough for most.

I hope to use this as kind of a running note board for what I find along the way.

# The package

So when the kit arrived (and rather quickly I might add), it was in two boxes.  It appears that one contains the panels, heat bed, and build plate items.  The other is the only one I have opened so far.

So I don't do "unboxings", and normally don't take pictures of how an item is packaged, but I have to say I was impressed in how this was packaged.

![Fysetc V2.4 parts](/images/box1.png)

I also greatly appreciated how the fasteners were nicely organized in a small parts box.  The LDO kits have everything separated into zip lock style bags with great labels.  But the further I got along in building my LDO kit, I had difficulty finding where that one bag of screws went.  I'm hoping this will make things easier for the Fysetc kit.  So score one for Fysetc over LDO in my book here.

![Fasteners](/images/fasteners.png)

One last thing from opening the box before moving on.  The X-gantry is an upgraded lightweight CNC item.  While I can't honestly speak to the strength/quality, the part looks very nice.

![X Gantry](/images/gantry.png)

So, when I built my LDO kits, I worked from the standard Voron manual, printed the standard Voron parts from their official repo, and had to reference back and forth to the LDO information on some extra or different parts to print or processes.  At least that was the case for the Trident and V2.4.  The Voron Switchwire manual, actually calls out the differences for the LDO kit in the manual, so that was a bit nicer.

Fysetc has their own repo with the parts to print, manual, etc.  At first glance, the manual looks to be the standard Voron one, however the STLs to print are specific to this kit.  Where a Fysetc specific printed part exists, that file is in the repo in place of the original Voron part.  This made it easier (from my initial look) to make sure I print all the required parts, and no parts that I did not need.  This to me is another advantage for the Fysetc kit.  Granted it is still very early in the build of this printer, but so far things are looking pretty good.

For this build, I decided to use Ambrosia ASA filament from West3D.  [Galactic Midnight Meteorite](https://west3d.com/products/ambrosia-asa-galactic-filament-of-the-gods-glitter-sparkle-1kg-bambu-ams-friendly-cardboard-spools-premium-3d-printing-filament-house-asa?variant=44425288253652) for the primary color and [Galactic Grape](https://west3d.com/products/ambrosia-asa-galactic-filament-of-the-gods-glitter-sparkle-1kg-bambu-ams-friendly-cardboard-spools-premium-3d-printing-filament-house-asa?variant=44020725317844) for the accents.

In initial parts printing the part [FYSETC-VORON-2.4-R2-Pro/STLs/Cleaning brush/Voron R2&2.4 Cleaning brush.STL](https://github.com/FYSETC/FYSETC-VORON-2.4-R2-Pro/blob/main/STLs/Cleaning%20brush/Voron%20R2%262.4%20Cleaning%20brush.STL), the part is not properly orientated, and will need rotated to print properly.  I initially didn't catch that the part wasn't properly orientated, as I was accustomed to Voron parts being properly laid out.  

I was not able to find any additional build information for the Fysetc kit even though there are a few changes from the stock Voron 2.4 build.  So I am following the Voron build manual, and will note when and if I run into any issues.

## Frame
I found no issues with assembly of the frame.  The extrusion quality seems just fine, and I think I even read somewhere that Fysetc uses Misumi extrusions.

While I do not see it mentioned in the manual, I do recommend using some form of thread locker (non permanent) for frame assembly.

After the frame is assembled, you move on to installing linear rails for the Z axis.  It is mentioned in the manual, but I will stress here as well, the rails come with shipping oil on them.  Clean them with IPA or similar and grease the rails.  The Voron manual has a link to a video that covers the process of lubricating the rails, so I won't go into further detail here.

You will know that you have enough grease in the rail because there will be a slight drag when sliding the carriage, and it will feel the same the entire length of the rail.

When atttaching the rails to the extrusions, the diagrams show installing a bolt in every other hole rather than every one.  On a 350mm kit this will end up with one of the end holes not having a bolt in it.  So I start from both ends skipping one hole, then the two holes in the center will both have bolts in them.  This might be a bit overkill, but I prefer this to leaving a gap of 2 holes somewhere or an end hole.

The manual does show the rail installation guide.  You should have printed 2 each of the two different sizes.  Y and Z rails are the same size, and X is slightly wider.  Use these printed parts to ensure that the rail is centered on the extrusion as you tighten the rail to the extrusion.

While this may or may not be typical, I did seem to have a bit of difficulty removing the protective cover from the acrylic deck panel.  Mine wanted to rip a lot.  Take your time, and it will all come off.

## Z-Drive
This is the first place that heat set inserts are required.  One thing the Voron manual does not seem to have is a summary of where heat sets need to go.  I have used some other manuals that do cover this in the beginning.  Since this is the first place that heat sets are installed, I will give a list of pages below of where heat set inserts are installed.

#### Heat Set Inserts

Working with the Voron2 2.4R2 Build Guide dated February 12 2022, the following pages have heat set inserts to install:

31, 
