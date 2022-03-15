# IC-BactTracker-heatmap

This project was originally for use in combination with <a href="https://github.com/bkeith20/IC-bact-tracker-2018">IC-bact-tracker-2018</a> to display data collected with the application.

The heatmap allows for filtering of data collected by bacteria classifications, resistances to different medications found in the samples, as well as when the samples were collected. The application allowed for viewing of the heatmap through the use of a webview.

![image](https://user-images.githubusercontent.com/33661898/158398119-516ca6d5-225a-4ab6-bf92-103ab4cba4ee.png)

![image](https://user-images.githubusercontent.com/33661898/158398202-c2445d3a-931e-4213-a687-5d63b2ed6275.png)

The page is also responsive!

![image](https://user-images.githubusercontent.com/33661898/158398525-877575e1-1806-4872-8e30-7eb03bf4d1b4.png)

![image](https://user-images.githubusercontent.com/33661898/158398599-975df3e6-052a-42d2-b35e-192e7b5e17d6.png)

Currently the geospatial data is hardcoded in getData.js with the classifications, resistances, and dates all randomly generated.
In practive, getData would be modified to pull data from a server.

This project also includes the python script used to generate the random coordinates in the desired area.
