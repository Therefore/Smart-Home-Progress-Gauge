# Smart-Home-Progress-Gauge
ESPHome enabled Gauge
Monitor the progress of things in home assistant. This example shows how to do it for a Tesla battery state of charge, but you could use it for a 3D printers percent completion or other percent related activities.

![](https://imgur.com/cLniXL5.gif)

Features:
- Scales to any size LED array
- Shows sevarity in red and yellow at 10% and 20% (configurable)
- Can show a sweeping LED to show forward progress based on another sensor
- Dimmable through home assistant


Need help with:
- adding an ease-in and ease-out of the sweeping LED
- adding a delay when the sweep ends and starts again
- better start-up behaviour when it doesn't know the value of the sensor
