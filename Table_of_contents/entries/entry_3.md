
# JS Notes

For loops are used to make a piece of code run a certain number of times. When using
a for loop, beware of infinite loops. Infinite loops are created, when you create 
a condition that evaluates to true and has no way of becoming false. All this also
applies when using a while loop. The only difference between a "for loop" and a 
"while loop", is a "for loop" is used when you know exactly how many time you want
something to run. If you do not know how many times something should run then you 
would use a while loop.

``` JS
For Loop Syntax

for(var i = 0; i < 10; i++){
    console.log(i);
}
```
 This for loop will print out the numbers 1 through 9. because they are all
lower than the number 10. Once the counter (i++) reaches the number 10 the loop 
ends because it has reached a condition that evaluates to "false", because 10 is not
less than 10, but 10 is = to 10. Therefore it evaluates to "false" and ends.

```  JS
While Loop Syntax

var i = 0;
while(i<10){
    i++;
    console.log(i);
}
```

When using the while loop, it will include the number 10, unlike the for loop unless
specified.

# EarSketch

**Digital Audio Workstation Studio(DAW)-** software used to record, edit and play digital 
audio files. Audio files in (DAW) are called (clips), and these clips can be combined 
together on a musical timeline.

**Tempo-** The speed at which the music is playing.

**Tracks-** layers of sounds and beats to create a song or remix.



![EarSketch_Setup](/Table_of_contents/images/EarSketch_SetUp.png)

This is the basic setup to use when creating a new work space. This is the JS version,
so the python version will look a little different, but will have the same concept.
It is worthy to note that the "clips" can be stored into arrays and be accessed through
array indentation.

