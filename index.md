# Infinity Mirror Clock
Throughout my three weeks at BlueStamp, I have been working on building an LED Infinity Mirror Clock. Circuits and coding with the Arduino Uno became the biggest parts of the project, but the hands on work with these circuits and putting everything together was the most fun. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Vincent A. | Saratoga High School | Mechanical Engineering | Incoming Senior

![Headstone Image](https://user-images.githubusercontent.com/88203817/137640756-1e61a5c8-199b-497d-82d9-61d0783866f3.png)

  
# Final Milestone
For my final milestone, I assembled all of the pieces together. Taking my LED strip, getting fed code from my Arduino program, I placed it on top of the mirror. Then, I placed the accrylic semi-see-through mirror in order to give that infinity effect of the clock. Now with all of the pieces together, I can now use the correct code to display the clock. Before, my code only told a certain amount of lights on my LED strip to turn on one after the other at a certain pace as a certain color I set in the code. In my new code, every light is turned on and displays white(255, 255, 255), and the colors red, blue, and green appear. Red represents the second hand, blue represents the minute hand, and green represents the hour hand. Just like a regular clock, each "hand" moves accordingly, all because of the code. At the moment, I still have to refine the physical appearance of the clock, by adding a frame for the clock to obtain that perfect circle, because right now, I have tape holding the strip together in a shape that is closest to a circle I can get it to. In order to fit the strip into the clock frame, I had to cut the strip down from the original 30 lights to 22 lights. So, I also have to make some adjustments to my code. I have to change when each light shows up so it's proportional to what it would have been if I had 60 lights for each second in a minute and each minute in an hour. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1634499382/video_to_markdown/images/youtube--Etgfciw8C6c-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/Etgfciw8C6c "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
For my second milestone, I connected the LED strip to the circuit, which includes the Arduino and the RTC module. Actually trying to connect the LED strip was the hardest because the clamps and exposed wires of the LED strip didn't want to cooperate with each other. I connected the data-in pin to the sixth pin on the Arduino and the ground and vcc pins to E5 and E6 on the breadboard. These pins are in the same column as the vcc and ground pins on the RTC, which are connected to the 5V pin and ground pin on the Arduino, actively connecting the LED strip vcc and ground pins to the Arduino pins as well. The code I used before the infinity clock code basically told each light on the strip to light up one after the other in a certain color, at a certain pace, and how many lights would light up. After getting comfortable with the LEDs, I will move on to creating the infinity mirror portion and implimenting the code for the clock. 

[![Second Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1628701629/video_to_markdown/images/youtube--8MTFRY2dXgg-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=8MTFRY2dXgg "Second Milestone"){:target="_blank" rel="noopener"}

# First Milestone
My first milestone for my project was getting familiar with the RTC module and how it works. I was able to find a tutorial on YouTube for using the RTC module with an Arduino. I used the schematic given in the video to build my circuit, connecting pin to pin with dupont wires. I connected the ground and power pins of the arduino and the module together, and I connected the SCL and SDA pins on the arduino to the same pins on the module. Using the code below I was able to input the time and date of the day I modified it to start the clock. In order for the code to read the input, obtain the information from the module, and display it, I had to first input the time and date, upload the code, then comment out those three lines and upload it again. With the clock portion of my project up and running, I was ready to move on to the bigger circuit for milestone two. 
<img src="image folder/carbon.png" width=500 align=center style="float:right; padding-right:10px">

[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1628266615/video_to_markdown/images/youtube--2-4P5dfDjyw-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/2-4P5dfDjyw "First Milestone")
{:target="_blank" rel="noopener"}
