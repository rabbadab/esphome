# E-paper display 
So this is inspired by many other projects and I'll try to list them below.[^1][^2][^3]

This project uses [ESPhome.io](https://esphome.io/) as a system to run on the ESP32 board.

Content for the display is fetched from [Home Assistant](https://www.home-assistant.io/).

*This is a work in progress and for the content on the display it will change many times going forward.*
### How do you use this?
The yaml code is ment as a reference not a cut and replace.

Look at the code file here:
[epaper-display-7-5.yaml](/epaper-display-7-5.yaml)

### Functionality built into the software of the display:
- Showing content depending on distance. When the car is away from home and have a longer ETA than 1 minute the display starts showing the ETA. 

### Future functionality
- Calendar upcoming events
- Weather forecast
- Mail delivery
- Alerts from different systems

## Hardware for this project:

- Waveshare E-paper ESP32 driver board
- Waveshare 7.5inch e-paper display. I got the v3.   
- IKEA picture frame is called RIBBA 13x18cm. The white border is a bit small and will hide a bit display area... 

### More pictures will come with how the display is built. 
In general it's put in as a picture and a cable to the esp32 that fit in the frame behind the display. 



![e-paper display inside a IKEA picture frame](images-readme/epaper-display.jpeg?raw=true "Title")


[^1]: Weatherman display with IKEA picture frame
  https://github.com/Madelena/esphome-weatherman-dashboard
[^2]: Other displays with similar ideas
  https://github.com/maxmacstn/HA-ePaper-Display
[^3]: https://github.com/sainz/Home-Assistant-e-Ink-Display
