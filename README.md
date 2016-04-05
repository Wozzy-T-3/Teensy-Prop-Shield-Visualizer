# Teensy-Prop-Shield-Visualizer
Processing Sketch to Visualize IMU orientation from Teensy Prop Shield.
* Reads the serial data stream from Teensy and renders a realtime Visualization.
* Appends data to an output file which can be accessed for plotting a stripchart.
Built off of Ben's Processing sketch,https://forum.pjrc.com/threads/33328-Prop-Shield-Beta-Test?p=100278&viewfull=1#post100278

This modification adds the Teensy board to the rendering, and the ability to write output to a data file.
The data file created is compatible with KSTPlot which allows realtime strip charting.

* Here is a video of the Realtime IMU Visualization:   https://youtu.be/wPEwt0wln0A 
* Here is a video of the Realtime plotting with KST plot:   https://youtu.be/VfoFPBPQ-aQ
* Here is a link to Kst plotting software:   https://kst-plot.kde.org/

https://raw.githubusercontent.com/Wozzy-T-3/Teensy-Prop-Shield-Visualizer/master/images/Screen%20Capture.jpg

<img src=https://raw.githubusercontent.com/Wozzy-T-3/Teensy-Prop-Shield-Visualizer/master/images/Screen%20Capture.jpg width=650 height=400 />

<img src=https://raw.githubusercontent.com/Wozzy-T-3/Teensy-Prop-Shield-Visualizer/master/images/Visualizer.JPG width=400 height=400 />

<img src=https://raw.githubusercontent.com/Wozzy-T-3/Teensy-Prop-Shield-Visualizer/master/images/KST%20Cap.jpg width=450 height=400 />

Keyboard Menu (When Focus is Processing Graphics output window)
* press H to show/hide Help
* press F to show/hide Fps
* press U to show/hide orientation Update rate
* press N to show/hide yaw, pitch and roll Numbers
* press L to open to start/stop data Logging
*press Z or X to adjust yaw to match view angle
