---
title: "PCB Hacker Badge Pro"
author: "Eddy Zhao (@eddyzow)"
description: "A PCB business card for Hack Club's Undercity hackathon with Type 5 NFC, two LEDs, increased field range, and additional updated information about myself."
created_at: "2025-06-26"
---

*Total hours spent: 7* | *Date started: 26 June 2025*

# PCB Hacker Badge Pro
_new me, new hacker badge!_

## entry #1 - 6/28

with undercity coming up, I realize that there will be epic attendee badges being made for us. that made me think about something personal I could show people in college. i've spent the past two days making this PCB business card. while i've made one over a year ago, I decided to take this one to the next level by upgrading nearly every component! there are two LEDs (blue and green) instead of one yellow one, and the main chip has been upgraded from a Type 2 NT3H2111 to a Type 5 ST25DV. 

the first source of inspiration i used was the original schematic for my PCB Hacker Card from the OnBoard jam. while this was great, it didn't help too much since I was going to use a different chip to begin with. i had to learn manually how to work with the new chip, which has a specific energy harvesting pin that i was able to make good use of.

i also had to swap the antenna because this chip is way more powerful and i had to do something called "impedance matching" which is basically finding the proper antenna with the proper inductance to match the chip. this chip is more complicated, so it has an inductance rating that is higher (4.8 microhenries) than the original (2.5 ish microhenries). as a result, I had to use a different antenna.

i also added two LEDs by searching on the JLC parts library from the same source as the original hacker card jam. these new ones are green and blue versus the original yellow. here's the final schematic:

![image](https://github.com/user-attachments/assets/1258719f-2eb7-4888-bc24-e0a3b4bdb593)

### design

design was based off my old design, but I added some new relevant stuff (new school, github, and some stars for art!) I also switched up the clipart drawings at the bottom of the front. here's a comparison of the front:

![image](https://github.com/user-attachments/assets/5d5482ad-2c16-4776-9fce-7ed2d826fc52)
![image](https://github.com/user-attachments/assets/9991b72b-87ec-4ccc-8091-fc57f6e8e5bb)

can you guess which one is the newer one?

i made all this in google drawings, and it was truly a pain to make it fit into easyeda. after 10 tries (!!) i was able to finally crop and shape the artwork into the way I wanted.

i'll make one more addition after this entry, and that is adding my signature in silver to the card front. this is a short project so I'm only expecting four points for highway. either way still had a lot of fun and will (im)patiently await my cards!
