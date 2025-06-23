# Hexapod
I built a Hexapod robot that moves via a wireless remote control. (TBD)

```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Cody C | Aliso Niguel High School | Mechanical Engineering | Incoming Junior

![Headstone Image](CodyChau.jpeg)
  
# Starter Project: Retro Arcade Console

<iframe width="560" height="315" src="https://www.youtube.com/embed/MOtjQcMDxQQ?si=XrkvdSWTWXNjZnzv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For my first milestone, I assembled a retro arcade console. Using a 2.8x3.8inch PCB as a base, I soldered on a 12 mm 5V passive buzzer, a 220uF 16V electric capacitor, a 4-pin 90 micro usb, a 8x8mm self-switch, a 3631AS digitron display, a STC8H3K64S2 IC chip, two 1088BS 8x8mm LED dot matrix modules, and a battery case to the PCB. Then, using a variety of colored caps and acrylic shells, I finalized my project. It functions by switching on the red power button and selecting the level at which to play using the left and right blue buttons. After then pressing the yellow button to confirm the level, it starts playing tetris. It plays a little tertris tune at the beginning and keeps score in the top right corner. Once finished, the power switch can be pushed again to turn it off.

During my assembly, I struggled soldering on specific pieces. For example, the two wires connecting the battery pack to the PCB are very small and in close proximity not only to each other, but to other parts as well. So, while soldering on the wires, my soldering iron accidently touched the power switch and melted one of its corners. It still functions, but if I had soldered any longer, it may have permantly damaged and shut down the power switch. So next time, when I begin soldering my intensive project, the Hexapod, I will be more mindful of not only my surroundings, but the surrounds of my soldering iron.

<!---
# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
-->

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Raspberry Pi Spider Sheild | This is used to connect everything for the robot | only sold with Hexapod | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| WLAN module | This connects the hexapod to the computor or phone wirelessly | $15 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Wireless Module (2) | This is used to connect the controller and the robot | $9 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Servo motors (18) | This makes the legs move | $18 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Arduino Uno (2) | One is used for the controller the other is used for the modifications | $17 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Remote Sheild | This is used to control the robot | only sold with Hexapod | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| LCD I2C | This is one of the modifications | $10 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Photoresister | This is another modification that controls the LCD I2C | $6 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| LED Matrix (2) | This is the last modification and its used to make the eyes | $8 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Wires | These connect everything | $10 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| 10k ohm resister | This completes the photoresister circuit | $9 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| 2x400 Breadboard | This will connect everthing together without soldering | $10 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
