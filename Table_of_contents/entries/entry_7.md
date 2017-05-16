# The setEffect(); Function

The *setEffect();* function is very unique function in EarSketch, because it allows
the users to alter the sounds with in ear sketch as they please. The one affect that 
I am certain that exist with in EarSketch is the **Delay Effect**. The *Delay Effect*,
allows users to slow down a track(a section in a song) by certian number of milliseconds.
I am currently unaware of what other effects can be used in *setEffect();* to alter
the tracks in the song.

``` JS
//Here is an example of a setEffect(); using the Delay method

setEffect(1, DELAY, DELAY_TIME, 500);

//This will give track #1 a half a second delay before playing the next sound in the measure

```
The delay feedback lowers the default of -3dB to -20dB, which results in fewer repeats 
and a more pleasing sound.

# Envelope

Envelopes allows us to add effects to smaller portions of a track and define how 
an effect’s parameters change over time. They can be used with any effect parameter.

Envelope uses a set of parameters that are a time set value, EX: (-60,1,-10,5) ---> 
means a point is placed at measure #1 and value -60, another point is placed at measure 
5 and value -10.

The envelope creates a line between these points, a smooth transition called a *“ramp”.*

**Volume =** how loud the music is.

**Fade =** the gradual increase or decrease in volume.

Fades should be used at the beginning, end, or even transitions between tracks.

Volume can also be used to effectively mix a song.

**Reverb =** creates a slowly decaying echo after the sound was initially played.

**setEffect();** actually has 7 parameters, however the last 5 are optional parameters, 
which means you do not have add in values unless you want too. 

# The 7 Parameters of setEffect();

1. Track Number
2. Effec tName
3. Effect Parameter
4. Effect Start Value
5. Effect Start Location
6. Effect End Value
7. Effect End Location


# Takeaways 

Most tracks do not need to be altered by setEffect();, and it is better too envelope
small portions of a song, rather than add an effect to the whole track. It is hard
to detect the little change that is added by the setEffect();, however sometimes it
is noticeable by the pleasing delay of the song.

I am currently unaware of other affects other than *Delay* that may exist with in
EarSketch, but I am looking for documents online.



# Next Steps

1. Figure how to add picture from Google Drive into my C9
2. Discover what other effects exist with in EarSketch
3. Add sounds to my blogs by making an account with Clyp.it 







