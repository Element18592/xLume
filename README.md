# xLume
xLume is an LED controller project built with the ESP8266. It works with the alongside the xLume Xbox application and connects via UART to receive commands from the 360. The following is a breakdown of the current commands that can be called to activate the different colors and modes.
 
The following commands should be passed over UART
	
- **[xLume] - 0, 0, 255** (This is the main commmand and passes a color to the controller/LEDs which serves as a basis for most of the effects below. In this example we're setting the R, G, B value to Blue at full brightness.)	

- **[xLume] - Effects: 0** (Static Color)
- **[xLume] - Effects: 1** (Static Gradient)
- **[xLume] - Effects: 2** (Static Pulse)
- **[xLume] - Effects: 3** (Static Twinkle)
- **[xLume] - Effects: 4** (Turn off LEDs)
- **[xLume] - Effects: 5** (Color Wave)
- **[xLume] - Effects: 6** (Color Cycle)
- **[xLume] - Effects: 7** (Dynamic Pulse)
- **[xLume] - Effects: 8** (Dynamic Twinkle)

### Demo Video:  

<a href="https://www.youtube.com/watch?v=mztqegCKXT4">
  <img src="https://img.youtube.com/vi/mztqegCKXT4/maxresdefault.jpg" alt="Sentry Demo" width="550">
</a>

## Installation Example

<img src="example.png" alt="Installation Example" width="600">

## Simple Wiring Diagram

<img src="diagram.png" alt="Simple Wiring Diagram" width="600">
