# Entry 3
##### 2/10/2021

## Sources

Most of the sources that I used this time are for me to learn how to code with EarSketch. Since I had already some knowledge in javascript from SEP class, I jumped right into this <a href="https://www.youtube.com/watch?v=__3sQNXdbBg">YouTube video</a> about for loops and another quick <a href="https://www.youtube.com/watch?v=SvKfVYSS5J0">video on arrays and variables.</a>

Although there weren't many documentations for coding javascript on EarSketch, there was an <a href="http://nebomusic.net/earsketchlessons/Directions_EarSketch2_Effects.pdf">AMAZING documentation</a> on how to code some things with setEffect which creates effects on the songs you make on EarSketch!


## Engineering Design Process (EDP)

I'm currently at stage 5 of the Engineering Design Process: <b>creating a prototype</b>. I am starting to create music out of the codes I learned from tutorials and documentations on EarSketch. Since I am making music, I want to have different genres of music like pop, lofi hip hop, etc. I knew I had to get some inspiration from YouTube/Spotify to hear what has been popular these days. Most of them contained lyrics and for some people, that may be hard to concentrate while doing work. Eventually, I looked for music that did not contain lyrics. Starting with this very popular <a href="https://www.youtube.com/watch?v=5qap5aO4i9A">lofi hip hop</a> with that lofi girl with the cat! The music from there has a very slow melody and has a nice drum/guitar/piano beat at the background. All of these which I will keep in mind while making one. Of course, this is only one genre that I am listing. As for the other genres, I'll be using this same method: searching up songs popular these days, noticing the small details of the melody, and instruments used.

<br>

For the next stage of the Engineering Design Process, I plan to still be on stage 5, <b>creating a prototype</b>. I think I still have a lot to work with, and it is not really that great to stuff a lot of information in one sitting. However, I will still keep in mind to what I said in my previous--to make a program that allows the user to choose the music to listen to from a list, or let the program randomly shuffle the list of music for the user to listen to, while the timer is on for however long they want it to be. This might be what I will incorporate once I am done making the music. So for the next time, I expect to <b>create music with different genres--the music itself should already have a beat/pattern/melody to it and it doesn't necessarily have to be finished.</b>

## Knowledge

From this <a href="https://www.youtube.com/watch?v=__3sQNXdbBg">YouTube video</a>, I learned about for loops and one of her code included:

```
for(var x = 0; x < 8; x = x + 3) { 
    makeBeat(HIPHOP_SOLOMOOGLEAD_001, 3, 4, "0++-0---0+++0---");
}
```

Here I modified it and coded this:

<br>

```
for(var y = 1; y < 10; y = y + 3) { 
  makeBeat(RD_RNB_OTHERPERCUSSIONBEAT_11, 4, 6 + y,"0++--+-+--+-+-0--");
}
```

<br>

<ul>
<li><b>for(var y = 1; y < 10; y = y + 3)</b>: start at 1, while y is less than 10, add 3 to y</li>
<li><b>makeBeat(RD_RNB_OTHERPERCUSSIONBEAT_11, 4, 6 + y</b>: make a beat, sound name, what track #, put pattern on measure 6 then keep adding to get next measure</li>
<li><b>"0++--+-+--+-+-0--"</b>: 0 (play), + (play a bit more), - (pause)
</ul>

From this, I learned that I am able to make my own beat that will keep on repeating if the condition is met. It is a great way if you want something to come at a certain time with a certain beat which makes the music more unique.

Of course, here is another code from the <a href="http://nebomusic.net/earsketchlessons/Directions_EarSketch2_Effects.pdf">documentation</a> mentioned earlier.

```
setEffect(5, CHORUS, CHORUS_LENGTH, 15)
```

Here I modified it, so it can fit with my music:

```
setEffect(5, VOLUME, GAIN, -12)
```

<br>

<ul>
<li><b>setEffect</b>: set an effect</li>
<li><b>(5, VOLUME, GAIN, -12)</b>: track number, effect name, parameter, start value</li>
</ul>

Here I learned how to set an effect on the music I am currently making. The easiest way to explain it is like a filter you put on your camera photos and instead of it looking more better--the music sounds better with the effect. There are also many other different effect names with different parameters which I had a lot of fun tinkering with.


## Skills

The skills I used are <b>problem decomposition</b> and <b>consideration</b>.

I used the skill, <b>problem decomposition</b> when attempting to make the music I want. If I'm being honest, making music can be really overwhelming at times. Just thinking about what goes behind the scenes (beats, melody, inspiration needed, frustration because the music doesn't sound the way how you want it, etc) is <i>a lot</i> to take in. So, I needed a way to prevent myself from stressing all that. I started breaking the parts down into smaller pieces. I created a small list on what I had to do. 

<ul>
<li> Inspiration from songs </li>
<li> Think of what genre you want </li>
<li> Select multiple songs you like 
<li> Observe closely on their melody and instruments used </li>
<li> Finish the beginning of your music </li> 
<li> ... </li>
</ul>

Just a list like this kept things organized and I was able to keep track on what I had to do next.

I used the skill, <b>consideration</b> when I had to think about what the majority of people liked, songs with lyrics or with no lyrics. Everyone has their preferences. Personally, I wanted to choose to make music with no lyrics, but I had to think about if other people would prefer that as well. Of course, I did a quick google search and it says that when people are doing work, music with no lyrics are strongly recommended than compared to with lyrics. Lyrics can sometimes be more of a distraction than helping the students work. So, I'll definitely keep that in mind.     


[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)