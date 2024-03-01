# Marker-Spinner
Marker is a project for our physics teacher Mr. Manning. Mr. Miller was giving us ideas and we decided to go with the Marker spinner idea. 
## Table of contents
*[Code progress](#Codeprogress)
*[CAD progress](#CADprogress)

[Smart Goal planning for Q2](https://docs.google.com/document/d/1IB1CjCF75Uy60dikSJuv_7jvlOusDMBG6paIRjbJVEI/edit?usp=sharing)


### Week 12 
This week we decided to change our project. Our original project was an automatic chicken feeder, that would feed chickens automatically. Our new project is now a Marker Spinner for Mr. Manning(Physics Teacher). Considering that we just changed our project we haven't yet found a lot of resources or issues to be solved. What we have done this week is talk to Mr. Manning, create a design, and start on code. Next week we plan to meet with our mentor to get some ideas, start CAD, continue code, and do more research.

### Week 13
I worked on the code, while Hope worked on the prototype. We’re using 2 D.C motors and we might even need to buy faster ones. Credits to Graham and Malachi for giving us their Github page to use their code and that is the only new source that we found. We also found Dylan Hensley’s onshape about Mr. Manning’s marker spinner. With the code, I couldn’t get it to work in the beginning. Everything, we’re almost done with our prototype and the two D.C motors are working. Understanding the code and figuring out how we want our design to look like. Finish the prototype get Mr. Manning’s input about the motors and go on from there and have a meeting with Skye.

### Week 14 
This week we finished up our prototype and met with our mentor Skye. We decided on two different ideas for the wheel of the marker spinner to spin. The first idea is to use an axle and have the wheel spin in the middle to balance the weight of the markers. The second idea is to have attachments to the DC motors and have them attached to the wheel. We discovered that the weight of the markers can impact the balance of the wheel so that's where our new ideas came from. Coming up with a solid design went ok and just getting our prototype to work was a bit difficult. Our plan for next week is to start CAD design, continue working on code, and maybe update our prototype.

### What is the problem you are trying to solve?
Trying to save drying markers

### What are the requirements for this assignment?
The requirements are Pico, breadboard, LCD, H-bridge motor driver, plugs, 3D printed materials, and acrylic sheets


# February 

## Week 1
After our brainstorming and finally deciding on our project we started doing research based on our project. I started researching how to get a D.C motor working. By the end of the first week, I found some sources to get me started. 

## Sources: 
Graham and Malachi
[Graham and Malachi Github](https://github.com/Graham913/G-Hog-mapper-notebook)
I used their motor code

[How to Use Your Raspberry Pi Pico With DC Motors](https://www.tomshardware.com/how-to/dc-motors-raspberry-pi-pico)
This source helped me wire up my motors and the code helped me understand how I want my motors to work

[How to Use Your Raspberry Pi Pico With DC Motors](https://www.tomshardware.com/how-to/dc-motors-raspberry-pi-pico)
This source kind of helped me know how to get started and I used their code to see if it was going to work, but it didn't. Later I found out that Graham and Malachi had already done their code for the D.C motor, so I asked if I could use their code and they said yes! I used their code and changed it a little bit and it worked!!!! YAYAYAYA Best day!

## Week 2
Now that I was done with the D.C. motors I worked on adding a button. wiring a button wasn't hard, but coding it was. Just because I didn't know where to add the button code and how to connect it so that it worked with the D.C motor. and it took me a day or 2 to code-wire it and connect it to the Pico

## Sources:
Mr. Miller
Thanks to him he helped me code it by adding an if statement and understand how to code works and where to put

## Week 3 
After I was done getting the button worked with the motors, I thought I was done, but I wasn't :/ Mr. Manning wanted an LCD now, I was like okay. I started doing research  and I found some useful but not useful sources. Then I found out that Ellen was doing an LCD, so I went to her Github page and I noticed that her LCD code was different than what I was looking for. So I moved on and did some more research. I did research this whole week

## Sources: 
[gventre04 LCD Button](https://github.com/gventre04/CircuitPython/blob/master/lcd_button.py)
This source helped me know how to connect my button code with LCD so that it could work 

[How to use an I2C LCD Display with Raspberry Pi Pico](https://www.tomshardware.com/how-to/lcd-display-raspberry-pi-pico)
The wiring diagram was helpful when first I started to wire an LCD 

[Using an LCD with a Raspberry Pi Pico](https://www.penguintutor.com/programming/pico-lcd)
Their code was helpful to start me off and the wiring diagram they had was super helpful because it had a button and I had no clue how to wire the button so that it's connected to a motor and an LCD


## Week 4 
This week Sky came and we talked to her about our process and she talked to me about how I can use a switch instead of an LCD, so I talked to Mr. Manning about it and he said NO and that he wants an LCD. He didn't want to let me go easy, so It took me another few days to code the LCD and I got it done!

### Images
![LCD with pico](https://github.com/hgeorge82/Marker-Spinner/assets/71345399/0ec3f89e-0f75-4fde-89b8-b5c0b2212274)

LCD wiring with pico

![LCD with button](https://github.com/hgeorge82/Marker-Spinner/assets/71345399/674ee546-c6c8-418b-8971-62215cc1b634)

LCD wiring diagram with button

![Motor with a motor control](https://github.com/hgeorge82/Marker-Spinner/assets/71345399/610a2faa-24de-40ec-b779-d7eabe364112)

D.C motor diagram with an H-bridge 

## Week 5
I showed Mr. Manning the LCD and he was like add a countdown to it now. And I was are you serious?, so I did some research and found good sources, and added the countdown. After I was done I started to combine my code and my code was officially done! I thought I was done, but when I realized that I needed to shut down the whole system, and to do that I needed to divide the voltage between the Pico and the H-bridge driver. I had a lot of trouble with that. After trying for days I gave up. So I went to Mr. Manning and we tried to solve the problem, but we couldn't so we decided to go with 2 cables. So currently I am waiting for the cable to come so I can connect it. I will also need to commend my code and I will officially be done! 

## Sources
[Countdown for LCD](https://community.element14.com/challenges-projects/project14/7segmentdisplay/b/blog/posts/pi-pico-with-clock-display---showing-a-countdown-time)

I used some of their code to code for countdown
