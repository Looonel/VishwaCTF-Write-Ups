### ![Title](additional-files/The-Summit.png)

## Description

<div style="text-align: justify">Hey, I recently attended an event where I saw some notable guests on the first day. Unfortunately, I can't quite remember the exact location of the event. However, I do remember it was an important event with a lot of attention from the media. Can you identify the location of this event and find out who the prominent guests were? Use publicly available data to figure it out, and provide any additional insights you can gather about the event.</div>

## Flag Format

VishwaCTF{xx.xx,xx.xx_FirstName LastName}

## Attachments

[chall_1.jpg](additional-files/chall_1.jpg)

## Points

500

## Solved Date

March 5th 2025, 12:15 PM UTC+9

## Solving Steps

### Step 1 (Analyzing the jpg)

<div style="text-align: justify">After downloading the jpg file, I could analyze a few things:</div>

- A date in the very bottom of the picture which says "2025 01 05 11:57" which means January 5 2025, 11:57 PM.
- A robotic military looking vehicle with the words "THeMIS" printed on the front.
- Lots of trees in the background of medium to large height.
- South Asian people which I assumed were Indians because it's only logical since this CTF originates from India.

### Step 2 (Finding information online)

<div style="text-align: justify">Searching the words "THeMIS robot" online, it leads us to a lot of sources and pictures with the same exact robot in the picture. It is in fact a UGV (unmanned ground vehicle) that is used for military applications.</div>

`https://en.wikipedia.org/wiki/THeMIS`

<div style="text-align: justify">With this in mind, along with a bunch of civilians crowding the vehicle in the picture, I came up with the conclusion that this was a military event or showcase that happened in India. So I searched up what kinds of military events took place around January 5 2025 and this website showed up about the "Indian Army Day": </div>

`https://theiashub.com/upsc/indian-army-day-2025/`

<div style="text-align: justify">Reading through the article, I reached a part where it lists down different 77th Indian Army Day events that will happen in India during 2025. One event caught my eye however: Know Your Army Mela 2025. Why you might ask? Because the event is from January 3-5 which is exactly when our photo at the beggining took place. So I got to searching more about this event.</div>

### Step 3 (Finding details about the event)

<div style="text-align: justify">Searching the Know Your Mela 2025 event in Google resulted in this website recommended to me (URL is shortened due to it being way too long):</div>

`https://tinyurl.com/yc2m884p`

<div style="text-align: justify">I didn't see any information about the THeMIS robot vehicle being in this event but there was one notable feature that stood out. The trees in the background look exactly like the ones in the challenge photo.</div>

![A picture of the event](additional-files/Know-Your-Mela-2025-Event-Picture.jpg)

<div style="text-align: justify">From this, I know for sure that this must be the venue. So I got searching for the name of the venue and the coordinates. I ended up with the venue being the Pune Race Course and the coordinates being 18.5089° N, 73.8926° E (rounded off to 18.51,73.89 according to the flag format)</div><br/>

<div style="text-align: justify">All we need to find now is the name of the of the notable guest. Conviniently for me it's right there in the website too if you scroll down a bit more. His name is: Devendra Fadnavis. At this point I wasn't sure if all of these were correct but it was worth a shot. Inputting all the information I have collected into the flag format turned out to be the correct flag:</div>

`VishwaCTF{18.51,73.89_Devendra Fadnavis}`
