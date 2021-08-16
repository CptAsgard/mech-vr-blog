## Weekly Update - Week 1

**NOTE:** _This is a weekly update, which are usually reserved for Captain-level Patrons and higher. I am making it public to serve as an example. If you like what you see here, consider subscribing to my Patreon at [patreon.com/mechvr](https://www.patreon.com/mechvr)._ 

_From here on out I will instead post occasional public updates that are larger in scope and show less behind-the-scenes content. Also consider joining the [Discord](http://discord.gg/qTYbdVfYmh) if you’d like to talk about this project or ask me anything._

Hey Patrons,

To understand my plans for the first month of this project, please read [this post](https://www.patreon.com/posts/54959792) on Patreon.

I have just finished my first week of work on this unnamed Mech VR project, and I’m overjoyed with the progress I’ve made. 
My goals this week were to implement mod support, create the throttle and turn control, and connecting it to a Mech and making it move. This goal was achieved and more.

<br>

### Hand Physics

First, I want to emphasize the physicality of everything. Your hands are physical objects and everything in the cockpit will be too. 
In my opinion this gives it a very immersive feeling. I looked at HL: Alyx for inspiration in this. I also attach and pose the hand for the object you’re interacting with. 
In the future I will be adding some more features to improve hand precision for interacting with the cockpit, and let mods pose the hand.

<video src="https://user-images.githubusercontent.com/1854650/129532467-9276d9d8-f2bf-49a1-addb-cc354432ef8b.mp4" width="320" height="200" controls preload></video>

<br>

### Throttle control

Secondly, I worked on the throttle control. It has weight and snaps into 5 discrete positions: neutral, two forward, and two backward. 
In my opinion this not only gives it a satisfying physicality, but it also gives you better control over the speed of your Mech. 
It lets you return your throttle to neutral without a small rest speed remaining. It also lets you set a light or full forward/backward speed. 

The configuration of this will most likely be changeable in the Mech’s user interface, and it will be exposed to the mod side regardless.

<video src="https://user-images.githubusercontent.com/1854650/129533655-dcea663f-8578-4ac5-8016-e0db2a9ed693.mp4" width="320" height="200" controls preload></video>

<br>

### Joystick control

I then worked on the joystick control, giving it a similar physicality. 

<video src="

https://user-images.githubusercontent.com/1854650/129536195-d0831dbc-8cc3-4320-ad33-f2f42305ce13.mp4

" width="320" height="200" controls preload></video>

<br>

### Mech movement

Of course, both controls can be combined into Mech movement!

<video src="https://user-images.githubusercontent.com/1854650/129533812-ccdfea89-8be9-412e-8b87-ffe431f2c40b.mp4" width="320" height="200" controls preload></video>

<br>

### Mod support

But the plot twist is that the mech and control objects you see are not a part of the base game, they’re a part of the “CoreMod”. 
This mod will be included in the base game and contains the content you’ll be playing. The mechs, weapons, game modes, maps, and missions will be part of the “CoreMod”. 
It being a mod means that anyone will be able to create content for the game. 

<video src="https://user-images.githubusercontent.com/1854650/129533545-bc7af1ef-92aa-406c-b837-5fad9e627210.mp4" width="320" height="200" controls preload></video>

<br>

Also, the Mech “model” you see in the video simply represent the bounds of the smallest mech, about 13 meters. Creating more representative placeholder art will not be done the first month but will be a priority soon after.

Talos
