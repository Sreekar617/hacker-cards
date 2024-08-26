# hacker-cards
thanks to hack club for sponsoring this project


# Start

I followed [this tutorial](https://jams.hackclub.com/jam/hacker-card) from Maggie Liu to make the actual electronics. For the LED, I found the same LED she used but in green, because I like the look of green on black. However, any color will work.

For the PCB, I moved the components to what looked like a good position, rotated them so the wires don't cross, and used the auto router to connect them. One of the wires didn't conenct properly, but it's fairly simple to use the trace tool and fix it. One thing to remember is not to place the NFC controller chip too far away from the antenna, because the extra copper may weaken or change the signal.

Next, I worked on decorating. This visual helps explain how to get the color you'd like:
![real](https://cloud-qega55fyl-hack-club-bot.vercel.app/7layer-effects.png)

I wasn't expecting the shiny silver to look as good as it did, so I used it sparingly in the ruler and the social media section. Had I known, I would have used it instead of silkscreen for all the decoration (keep in mind this may change the cost of the product). 
Once I had it made, I ordered it from JLC. I got it in black and 1.6mm thickness with leadfree HASL, but if you can get it thinner without the crazy expensive "we don't make this color in this variation so you have to pay extra for the special treatment" charge, go for it.

Once you have the card, make sure to format the memory by either using the NXP tag writer app on an Android phone, or use Wakadev's NFC Tools app to write this Advanced NFC Command:

```
A2:03:E1:10:6D:00,A2:04:03:04:D8:00,A2:05:00:00:FE:00
```

This will format your memory and allow it to be written to with any other app. 


This was my final result:


https://github.com/user-attachments/assets/0c28cfc7-f71e-4215-afc8-399dd9557775



<video src="https://cloud-ji8p9kfqj-hack-club-bot.vercel.app/0img_1409.mp4"/>
