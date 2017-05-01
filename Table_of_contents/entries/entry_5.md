# Musical Terms

**Digital Audio Work Station(DAW) =** software used to record, edit and play digital 
audio files. Audio files in (DAW) are called (clips), and these clips can be combined 
together on a musical timeline.

**Tempo =**  the pace or speed at which a section of music is played.Can be measured 
in beats/minute.

**Rhythm =**  arrangement of sounds as music flows through time.

**Beats =** rhythmic movement, or is the speed at which a piece of music is played.

![musicNotes](/Table_of_contents/images/musicNotes.png)


**Sub-Beats =** the divisions of beats. Ex, eighth note, 16th note, etc..

**Measure =** is a segment of time corresponding to a specific number of beats.
(How long a section of the music is)


Most of the sounds in EarSketch are cut up into 5 measures, this means that the 
entirity of the sounds are cut up into pieces that loop several times before they
come to an end.

You can change the tempo and measure of each sound in EarSketch, however the tempo must be with
in the range of the sound. If you click on the the info tab of the sound you want to add
it will tell you the its tempo range. Most sounds on EarSketch have a tempo range of *120*.
I discovered this by picking random sounds to play and setting them to different tempos like 
this.

``` JS
//		javascript code
//		script_name:
//
//		author:
//		description:
//

init();
setTempo(120); //setTempo(100);, //setTempo(80); //setTempo(10);

//Multiple sounds can be played at once by changing the track number(The 1st number)
fitMedia(RD_EDM_DRUMROLL_BREAK_1,3,1,10); //The 1st track being played
fitMedia(RD_EDM_CHORDPART_3,4,2,20);     //The second track that plays
//fitMedia(RD_EDM_DRUMROLL_BREAK_5,3,3,20); //The third track that plays 
//fitMedia(TECHNO_LOOP_PART_002, 4, 1, 20);




fitMedia(TECHNO_LOOP_PART_002, 1, 1, 10); // Each kick drum hit lasts a quarter 
note: 1/4 of a measure.

fitMedia(TECHNO_LOOP_PART_031, 2, 1, 10); // Each cymbal hit lasts a 16th note: 
1/16 of a measure.

//Finish Section
finish();

```
From tinkering with the code, I discovered that you can group multiple sounds togther,
however they have to be in different tracks. If you set sound tracks on the same
measures then EarSketch will literally just cut out that section of the measure like
it does not exist. I was able to solve this problem by simply giving my sound tracks
their own sections and starting them all at the same time.


# EarSketch JS Code

**init();** = turns on the *(DAW)*.

**setTempo(); =** control the speed of the song, but must be in the correct range 
of the song.

**finish(); =** this code is very important, because it tells the *(DAW)* that you 
are finish and to stop.

**fitMedia();** = use this piece of code to add a sound clip anywhere between 
*setTempo(); & finish();*
 
**Functions in EarSketch are setTemp();, fitMedia();, init(); and finish();**

*Read Comments*
``` JS
//Basic Setup of  all Scripts in EarSketch

//Setup Section
init(); //DAW has been initiated 
setTempo(120); // The music will play at this pace
//Tempo can be changed, but must fit the criteria for all sounds

//Music Section
fitMedia(TECHNO_SYNTHPLUCK_001, 1, 1, 9); //Adds sounds to play
//fitmedia(paste_sound_clip, track_#1, start_measure_ #1, end_measure_#5 or any # you want)


//Finish Section
finish(); //Tells the DAW to stop here 

```
