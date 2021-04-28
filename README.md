# Smart-Mirror

This Project is a Smart-Mirror that gives the user date, time, weather, a calendar, clock and compliment.
Inspired by the open source Magic Mirror, this is an attempt at creating the Magic Mirror with Python.

Warning: GUI will be extremely basic, but the methods of obtaining API data and format of said data will be sufficient.
Warning(Important): Make sure to install tkinter from the official repository. Code won't work without it!

Partlist:

[1.PIR Motion sensor](https://www.amazon.com/HC-SR501-Sensor-Infrared-Arduino-Raspberry/dp/B07KBWVJMP/ref=asc_df_B07KBWVJMP/?tag=hyprod-20&linkCode=df0&hvadid=385487162049&hvpos=&hvnetw=g&hvrand=1022388154027094341&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9005169&hvtargid=pla-823732620719&psc=1&tag=&ref=&adgrpid=79288771155&hvpone=&hvptwo=&hvadid=385487162049&hvpos=&hvnetw=g&hvrand=1022388154027094341&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9005169&hvtargid=pla-823732620719)

[2.Raspberry pi](https://www.amazon.com/ELEMENT-Element14-Raspberry-Pi-Motherboard/dp/B07P4LSDYV/ref=sr_1_3?dchild=1&gclid=CjwKCAjwj6SEBhAOEiwAvFRuKJaDVmG-X_vTkkyFqozZ5ShfL0KPAr3ZUmNeGoioLRt_3SaJXkJrtBoC54AQAvD_BwE&hvadid=329308075149&hvdev=c&hvlocphy=9005169&hvnetw=g&hvqmt=b&hvrand=16624567647923561410&hvtargid=kwd-300229776225&hydadcr=18067_9813355&keywords=raspberry+pi+raspberry+pi+3+model+b&qid=1619627274&sr=8-3)

[3.Lighting](https://www.amazon.com/DIYmall-WS2812-WS2812B-Arduino-Raspberry/dp/B0774JNSCF/ref=sr_1_4?dchild=1&keywords=arduino+led+ring&qid=1619627498&sr=8-4)

4.Display (any monitor that you would want to build your frame around, use comething cheap if you can)

5.Two-way Mirror (10" by 12")
6.Frame for the mirror(make sure it can hold the mirror snugly)


**Steps**

1. After you've built your frame and placed the mirror inside (reflective side down), put your monitor behind it and assuming you placed it correctly, you should be able to see the display behind the mirror while still being able to see the mirror's reflective properties.
2. Connect your LED's and PIR motion sensor to your preferred pins. (make sure not to use an LED that uses too much power, if you use something that consumes more than 300 to 500ma, use an external power supply.)
3. PIR motion sensor is for turning the mirror on when someone walks by. You'll have to configure the pin you connected to the PIR to call wakeup from the kernel on voltage change.
4. Run the code in the main file, and assuming tkinter is installed correctly, the Smart-Mirror should run as expected



