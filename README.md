# Smart-Home-Progress-Gauge
ESPHome enabled Gauge

Monitor the progress of things from Home Assistant. This example shows the state of charge of a Tesla, but you could use it for a 3D printers percent completion or other percent related activities.

<img src="https://imgur.com/cLniXL5.gif" width="250"/>

Assembly:
1. Print Top Cover, Bottom Cover, and Diffuser
2. glue LED ring to diffuser
3. Cut leads from ringlight red goes to vin, green goes to D4, and white goes to ground
4. Copy and modify code to fit your needs and flash with ESPhome
5. power and enjoy.


Features:    
📈 Scales to any size LED array - circular or bar.    
⚠️ Shows sevarity in red and yellow at 10% and 20% (configurable)     
🔄 Can show a sweeping LED to show forward progress based on another sensor. In this case the LED sweeps if the car is plugged in.    
💡 Dimmable through Home Assistant    




Need help with:
- Adding an ease-in and ease-out of the sweeping LED
- Adding a delay when the sweep ends and starts again
- Better start-up behaviour when it doesn't know the value of the sensor
