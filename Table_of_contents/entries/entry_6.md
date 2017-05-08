# Different Effects 

In Earsketch there is a function known as **setEffect();**, and setEffect allows
the user to alter any sounds with in EarSketch. It allows users to create new and
unique sounds, or alter audio files to make them sound better. Effect, also lets
users chane the quality of the sound.

# **setEffect();** 
Takes 4 arugments
1. **Track Number :** The track that you want to affect.
2. **Effect Name :** The specific effect being used.
3. **Effect Parameter:** The parameter, or setting for the effect.
4. **Effect Value:** The value of the parameter: a number in a specific range.

``` JS
//Examples of setEffect();

setEffect(1, DELAY, DELAY_TIME, 500);
//The Delay effect will affect track #1, and it will a have delay in sound for half a second
// 500 = 500 milliseconds
```

**Decibel(dB):**  is used to measure sound level

The delay feedback lowers the default of -3dB to -20dB, which results in fewer 
repeats and a more pleasing sound.

**Sound Pressure Level(SPL):**  is a ratio of the absolute, Sound Pressure.

**Harmful noise to human ears occurs at (140dB)**

# Takeaways

Most audio files in EarSketch do not need altering at all, because they sound good
as they are. However I can probably use *setEffect* to alter sounds that are too loud
or to fast for the music that I am trying to produce. 

I would like to keep any affected sounds from reaching 140dB, as that can be harmful 
to human ears.

You can play the same sound multiple times through out the song by simply just 
changing the track number. This means that I can keep a beat or rythem playing
through out the entire song.

```JS
//Having sounds play out through the a whole song

//Pecdrum is a variable that stores in the value of the sound DUBSTEP_PERCDRUM_006;
pecdrum = DUBSTEP_PERCDRUM_006; 
fitMedia(pecdrum,1,1,5);
fitMedia(pecdrum,2,2,8);
fitMedia(pecdrum,3,3,10);
// By changing the track I can have this sound play at key moments or play through
//out the entire song

//If I want this sound to play through out the entire song then I would just write the code like this 
fitMedia(pecdrum,1,1,10;




```