# Useful functions

Functions in JS are useful, because they can be recalled at anytime and
will do what they were written to do everytime! This saves a programmer
time from having to rewrite the same code over and over and over again!


```JS
//Function SetUp
music = function(param or params){
    user = param or params;
    list = [];
    
    for(var i = 0; i < user.length; i++){
        list.push(list[i]);
    }
};

music(classical);
```

Functions are useful for when you want the program to redo something
multiple times. In this I want to record all the answers that the user 
might type in for what type of music they like. Instead having to rewrite
the (for-loop) multiple times. I can simply run the program by calling
the function by its name (music) and passing it some values, also known
as paramaters. Then the function will automatically store the user's 
value into the array because of the (.push()) method.

# Take Aways 

I have learned several tricks from online tutorials on JS. One of which 
is that you can be more efficent by running loops inside of loops! When
I first saw this and read some documentation, I thought that these people
were insane. However after trying myself to solve a CodeCademy lesson, it was
pretty useful. It was like (Loop-Ception) talk about a cycle! *Symbols Crash* :D

``` JS
 //Loop-Ception 
 
 text = "JustRandomStuff";
 keyWord = "Stuff"; 
 list = [];
 for(var i = 0; i < text.length;i++){
     if(i === "S" ){
         for(var y = i; y < (keyWord.length + i );y++){
             
             list.push(text[i]);
         }
     }
 }


```

This code is similar to the one in the above example just written a little
different using what I like to call *Loop-Ception*. Both codes should push
something into the array.