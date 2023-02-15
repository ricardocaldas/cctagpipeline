# cctagpipeline
*A Photogrametry pipeline of Alicevision Meshroom with CCTAG scaling feature*

**KeyfremeSelection** - *How to extract the frames from video to obtain Image Files*

1 - Open Alicevision Meshroon, Drag and drop the desired video file

2 - A "KeyframeSelection" node will be automaticaly inserted

3 - Select "KeyframeSelection" node

4 - In Attributes panel (botton right at screen), uncheck "Use Sparce Distance Selection" and "Use Shapness Selction"

5 - Right-click on "KeyframeSelection" node and Compute

6 - The extraction will start

7 - Files can be found at "Output Folder", described in Attributes panel

**Photogrametry with CCTag**

1 - Print the "CCTag Guide 100mm A4 sheet complete.pdf" file in a A4 sheet. Make sure the printer scale is corret by cheking the 10cm bar.

2 - Place the object in the middle os the Printed Sheet

3 - Take pictures or record a movie of the object. Do not cover the circle tags at the corners.

4 - Open the "Pre_defined_cctag.mg" in Meshroom (https://alicevision.org/#meshroom)

5 - Import the Pictures and "Start" the pipeline
