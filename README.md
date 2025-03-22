# xLume
xLume is an LED controller project built with the ESP8266. It works with the alongside the xLume Xbox application and connects via UART to receive commands from the 360. The following is a breakdown of the current commands that can be called to activate the different colors and modes.

> [!IMPORTANT]  
> In order for xLume to function properly please ensure that you have debug output enabled in your dashlaunch launch.ini
> 
> debugout = true
 
The following commands should be passed over UART (this is done via the Xbox xLume app). The first is the main commmand and passes a color to the controller/LEDs which serves as a basis for most of the effects below. In this example we're setting the R, G, B value to Blue at full brightness.<br><br>
<b>(Set Color)</b><br>
[xLume] - 0, 0, 255 <br>

<b>(Static Color)</b><br>
[xLume] - Effects: 0<br>

<b>(Static Gradient)</b><br>
[xLume] - Effects: 1<br>

<b>(Static Pulse)</b><br>
[xLume] - Effects: 2<br>

<b>(Static Twinkle)</b><br>
[xLume] - Effects: 3<br>

<b>(Turn off LEDs)</b><br>
[xLume] - Effects: 4<br>

<b>(Color Wave)</b><br>
[xLume] - Effects: 5<br>

<b>(Color Cycle)</b><br>
[xLume] - Effects: 6<br>

<b>(Dynamic Pulse)</b><br>
[xLume] - Effects: 7<br>

<b>(Dynamic Twinkle)</b><br>
[xLume] - Effects: 8<br>

<b>Setting your LED count</b></br>
[xLume] - ledCount: 10

### Demo Video:  

<a href="https://www.youtube.com/watch?v=mztqegCKXT4">
  <img src="Images/app.png" alt="xLume Demo" width="600">
</a>

## Installation Example

<img src="Images/example.png" alt="Installation Example" width="600">

## Simple Wiring Diagram

<img src="Images/diagram.png" alt="Simple Wiring Diagram" width="600">

Recommended LED Strips: https://a.co/d/2hvjQGv<br>
Recommended Programmer: https://a.co/d/huijcmV
