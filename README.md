iOS
===

This is where I am keeping iOS related things.. iOS has a sweetspot for me because it is the first thing I tried working in. When the iPhone 3GS came out one of the main features was a revamped camera, this new camera application has a feature named "Tap to focus". Pretty standard in modern smart phones, this was apples first implementation of it.. they released it to my surprise as a 3GS exclusive feature. Now as far as I know the actual focussing part is when the camera is physically readjusting the lense so that is obviously hardware, but Apple also included software that would adjust the lighting to maximize the light of what was being focused on in picture. I was a bored sophomore and I wanted that feature immdiately. I found that by adjusting the one of the core permission's in my phones filesystem would get the software behind tap to focus to work correctly... I was apart of a few blogs at the time and I wanted to share what I had found. 

I had found a clever way of packaging this application so that anyone could use it. Not everyone is comfortable messing with the permissions of there phone in the jailbreak community, so I packaged the tweak as a theme. Jay Freeman (AKA Saurik) made a *VERY* powerful theme engine that would not only override images in applications, I found it overrided anything in an application. Apple stores it's permission file in a odd location. "/System/Library/Springboard.app" (Other system applications are stored in "/applications" and "var/mobile/applications") 

So packaging it as a theme and then using the application "Winterboard" (Sauriks theme engine) you could override the default permission file safely. If something went wrong on the phone "safe mode" would happen where all Mobile Substrate Addons are turned off.. including Winterboard - This also turned off the modded permissions file making it extremely safe use.

I then released the application for free thinking only ~50 people would use it. To my surprise around 26,500 downloads later it was my first successful release and to this day my favorite. 

There is a live download count here... 
http://planetiphones.thebigboss.org/repository/pistats.php?file=iPhone%203G%20Auto%20Focus
