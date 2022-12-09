# TREASURE BOX


## Week 6

### Concept

In week 5 I had a concept about how to explore trust. I started with the idea of making a question answering machine, this came from a Japanese variety show, which is a right or wrong answering machine. But the questions can be not very practical, but highly personal and subjective opinions. If both sides chose the same answer, they would win, if not, they would be punished. So at first, the output I was thinking of was probably more of a screen-based output, it was more akin to a game. But after looking at the requirements in detail, I terminated that plan. I probably needed a concrete act to reflect the theme of trust more than a screen output. I started thinking about when people actually have more of a crisis of trust. This is when I was inspired by a friend of mine who was cheated by his friend over money. I thought this was a good point of opportunity. I started to think about making a treasure box, a box of sparkling gems that would have a form of expression, usually expressing friendliness, when you were close. The gems are beautiful and I was going to use a light strip to reflect that sense of ambience, but reaching in for the gems would set off an alarm, which is the sound of trust breaking.

### Appearance

A box, it can even be simple, I want it to be plain, that is the exterior. It's the gem inside that has more impact when opened and is more inviting to touch it.

### Input

It has to sound when a person is near, so I chose a PIR sensor to ensure that it is a warm 'human' action and not a mis-touch, it is more sensitive to human behaviour.
The same goes for the friendly indication that anyone can gain its trust, (the treasure case itself can be seen as a person) it is always generous with its display and will smile out of trust whenever it is approached, so the ultrasonic sensor was chosen.

### Output

The most important thing in the words of the display is an attitude, I think I will run it with a Micro Servo, but the exact form is still being thought about.
Then there is the siren, it could be shrill but short, or it could be an MP3 playing the siren but I think that would be too much and the exact form is still to be decided.


## Week 7

This week my goal was to make sure my input and output was achievable while I thought about the exact form of the treasure box. The thing shown above it turns when you get close, it starts as an expressionless face but turns into a smiley face, which is a way of showing friendliness. When you open the box it displays the glittering interior, but you cannot steal the treasures, the intention of the treasures leans more towards a private property and a domain and an emotion. If it was malicious he would issue a warning that its display is not the way people exploit it. I ordered some plastic diamonds and I hope it works better. At the same time I felt that the sparkle of the diamond was to be set against the light to shine and reflect the beauty of the diamond, so I anticipated borrowing some strips of light, unfortunately the labs had already been borrowed out and I purchased my own. I made sketches and I thought I could just hand make them and make the treasure box approachable. At this point I was thinking in terms of three inputs and outputs. But the response to the light strips was still on the fence for me.

![sketch](https://user-images.githubusercontent.com/119876408/206736394-68800024-5690-4865-93f8-112c7c48a2b9.png)

After two days the light strip arrived and I started to debug the code area officially, I built the code for the light strip first. After two days of thinking about it I decided that my goal was to make the strip glow continuously rather than have an input and then produce a reaction, as the emotion and preciousness should always be inside and as one of my outputs I thought it was important that it was there. I adjusted the brightness of the light strip to a higher level, initially I used the 5V power supply on the arduino, later I borrowed an external power supply. This made it more stable and didn't have to engage the other two inputs and outputs in a loop. I referenced the FASTLED library to show the colours and succeeded in getting a colourful sense of variation. I had wanted to borrow the plug for the light strip from the lab, but my teacher said it was no longer available, so I started soldering the strip with pin 7 and a common ground with the external power supply.
 

![图片1](https://user-images.githubusercontent.com/119876408/206736529-e48d76ba-7efb-4c4b-a5a2-3f9b1eb79711.jpg)

On this basis I started to write the code for the micro Servo, as I needed the micro Servo to drive the switch of the box. Referring to the code of someone else who made a smart bin, I made the micro Servo rotate about one hundred and eighty degrees, however, during the experiment, one hundred and eighty degrees was always difficult to achieve, I think it was the rotation angle of the micro Servo itself, I changed the code, I made a micro Servo that rotated 90° and painted a smiley face on it and pasted it on the top of the box, it was in the shape of a heart and it represented the change of emotions that people had towards their proximity.


![图片2](https://user-images.githubusercontent.com/119876408/206736700-0b75d12b-f9fe-4d6b-a7c9-1ee9a7f85c87.jpg)



## Week8

This week I started to run the last code, the sensor - the buzzer, as I wanted to show the feeling of a warning on approach, so the sensor should be inside the box and I set the buzzer to sound on approach. However the buzzer started sounding randomly without any conditions, I checked my code and set the time, at which point the second input and output was also successfully perfected. I then merged the three codes, where the first and second inputs and outputs were merged and the code worked fine, but there was a problem with the third code, the light strip section, which was merged and was very annoying, reporting errors on a regular basis, but it worked fine on its own, and I spent almost a couple of days working on it, finally tweaking the colours to make it simpler and mentioning the colours in a separate document.

![微信图片_20221209154253](https://user-images.githubusercontent.com/119876408/206739248-457ffc18-e65f-44ee-a3a9-e96c325ebcc7.png)
  
In the meantime I started making the box, I took the cardboard myself and started making the box, because at the beginning it was intended to be plain, so after the basic model of the box came out and was wrapped in black paper, the result seemed a bit too simple, which was a bit different from what I wanted, so I started to use some thread to show its rusticity, during this time my hand suffered a serious injury from the glue gun and after burning my hand the work stopped for a few days, during these days Finished the circuit diagram and tested it to make sure everything was theoretically possible.

![微信图片_20221209153947](https://user-images.githubusercontent.com/119876408/206739370-87d8e25d-53de-453c-98b5-ee6461db0e7c.png)

![微信图片_20221209154514](https://user-images.githubusercontent.com/119876408/206739504-1ffd69f8-61b8-4cc2-8152-544eb2d49869.png)




## Week 9

![Ingenious Maimu-Inari](https://user-images.githubusercontent.com/119876408/206739765-3e27b585-b2b8-4b74-8974-a7dad86cd817.png)


This week after the hand had largely recovered. After putting everything in the box, the servos were originally glued to the inside side of the box, but the first servo was in a condition and very sadly broke, at first I thought it was a circuit connection problem, after a long circuit test, I found that it was just the servo itself, most likely the use of the glue gun caused a lot of damage to the servo itself very scared so I still decided to put the servo on the outside of the box, because it was I bought some plastic diamonds and added a lot of my own treasurelery, on top of that I cut a lot of coloured ribbons and put them in the box to make a pavement. At first the coloured strips were glued underneath, so the light could not pass through the flat surface to create the effect, so they had to be re-glued. Thanks to the kindness of the lab for providing all the materials, I don't think I would have been able to complete this project without it, nor the students who helped me when I was confused, because of them I was able to complete this little treasure box.

![微信图片_20221209154658](https://user-images.githubusercontent.com/119876408/206739952-c71ff01c-f2ee-4953-b356-554a50860ef3.png)


I think my project can be seen as a piece of art that is an emotional experiment in itself, it is a piece of art that starts from a personal story, I think if it can be developed, it can be expressed in a variety of friendly forms, my classmates suggested to me that if I can My classmates suggested to me that it would be great if I could make a bigger box full of gems, and I think it would be even better if I could use a motor servo to control the opening of the box directly. In the future I think it would work better if instead of a box it was actually a human form, with a jeweled human feel.
 
![1](https://user-images.githubusercontent.com/119876408/206740081-60414efa-3715-47a2-b412-fe53b4f6dfb2.jpg)
