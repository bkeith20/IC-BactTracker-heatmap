# IC-BactTracker-heatmap

This project is used in combination with <a href="https://github.com/bkeith20/IC-bact-tracker-2018">IC-bact-tracker-2018</a> to display data collected with the application.

The heatmap allows for filtering of data collected by bacteria classifications, resistances to different medications found in the samples, as well as when the samples were collected. The application allowed for viewing of the heatmap through the use of a webview.

To use this heatmap, other.js will need to be edited to access the PHP file hosted on a different server or to access the data in a different manner. The current PHP file is set to randomly generate bacteria classifications and resistances for a set of 500 coordinates around Ithaca College. 

This project also includes the python script used to generate the random coordinates in the desired area.
