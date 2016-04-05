# Teensy-Prop-Shield-Visualizer
Processing Sketch to Visualize IMU orientation form Teensy Prop Shield.
 * Reads the serial data stream from Teensy and renders a realtime Visualization.
* Appends data to an output file which can be accessed for plotting a stripchart.
Built off of Ben's Processing sketch,https://forum.pjrc.com/threads/33328-Prop-Shield-Beta-Test?p=100278&viewfull=1#post100278 this adds the Teensy board, and the ability to write output to a data file.
The data file created is compatible with KSTPlot which allows realtime strip charting. 
* Here is a video of the Realtime IMU Visualization:   https://youtu.be/wPEwt0wln0A 
* Here is a video of the Realtime plotting with KST plot:   https://youtu.be/VfoFPBPQ-aQ
* Here is a link to Kst plotting software:   https://kst-plot.kde.org/

![Visualizer Screen Capture](https://raw.githubusercontent.com/Wozzy-T-3/Teensy-Prop-Shield-Visualizer/master/Visualizer.JPG)
![Plotter Screen Capture](https://raw.githubusercontent.com/Wozzy-T-3/Teensy-Prop-Shield-Visualizer/master/Plotter.JPG)
