# Tool Learning Log

## Tool: **Kaboom**

## Project: **Math Mind Refresh Timer**

---

### 10/26/26:
* Tinkered with beginer code on Playground of Javascript.
    * Tinkered with `pos(0, 80),` too change position of the pacman chasing the ghosts.
    * Saw many arrays designed for the npcs being the ghosts and the player
    * Uses sprite to add ghost
    * I wonder if sprite is also used to animate the player
* Observed through (Cli link)[https://www.npmjs.com/package/create-kaboom] saw a starting script of javascript code to help start a kaboom project 
* The characters come from pngs and added sprite to animate like rotate
* In kaboom strings can be used to define behaviors for certain groups
    * Can there be a limit for using a string like for example can the ghost be friendly and aggresive depending on the scenario?
* One challenge I have for this is `readd(greenBean)` what if user only wants a specific green beam to be re added is there another way to readd certain green beans?
* Next I will use Howler as Kaboom is mainly a game coder and my idea isn't really a game but rather an app that helps a user isn't meant to be fun rather helpful.

## Learning log 2
### 11/9/26:
* Switched to Howler because my project is more of an app than a game.
* Explored through the Howler Audio Sprite videos which reveal different sounds and beats.
    * You can click a section of  waveform to play the sprite so you can make infinite sprites go of back to back.
* Learned Howler can play audio files using Javascript 
    * Learned to play a sound you use `sound.play();`
    * To pause a sound `sound.pause();`
* Explored `.volume(0.5)` and learned that volume can be adjusted from 0 to 1.
* Compared `.play()`, `.pause()` ,`.stop()` to see different way to control audio
* I wonder if I can make different sounds play dependning on wether the users sleeping timer goes off.
* Considered how I could use different sounds for when a timer goes off.
* I wonder if I can let users choose thei own notification sounds.
* Next I will expirement and explore the howler.js documentation with its features to understand what it can do more clearly and how I could potentially use it in my project.

## Learning log 3
### 11/23/26:
* Explored the official Howler.js documentation to understand more of its features and how to use them in JavaScript.
* Looked through the Quick Start section and learned that you create a sound using new Howl() and provide an audio file through src.
* Explored different playback options:
   * Learned that volume controls how loud the audio is, from 0 to 1.
   * Learned that loop: true makes a sound repeat automatically.
   * Learned that rate() changes the playback speed, with 1 being normal speed.
* Discovered Audio Sprites, which allow one audio file to be divided into smaller sections that can be played separately.
* Learned that Howler.js can control multiple sounds at once and can also change individual sounds.
* Explored the fade() method, which gradually changes the volume over a certain amount of time.
* I wonder if I can use the fade feature to make notification sounds gradually get louder instead of playing at full volume immediately.
* I also wonder if I can let users choose different sounds for their timer notifications.
* Next I will experiment with the Howler.js code and test different audio features to see how they would work in my project.



<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
