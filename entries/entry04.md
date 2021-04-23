# Entry 4
##### 4/22/2021

## Sources

Sources I found helpful this time include this <a href="https://workshops.nuevofoundation.org/python-earsketch/7-activity-3-organize-songs-using-functions/">website</a> that helped me get a short review about functions. I realized that this only worked on python and I had to use javascript for EarSketch which I used my prior knowledge from SEP class. Of course, I can't forget about the trusty, <a href="https://www.w3schools.com/js/js_functions.asp">w3schools</a> with a great review on javascript functions!


Since there were no sources or videos that gone over methods I can use in EarSketch <i>USING JAVASCRIPT</i>, I recently found out that there was a section called API below Content Manager of <a href="https://earsketch.gatech.edu/earsketch2/">EarSketch</a> where it explains all the methods in detail! Make sure you login to see this all in action. I decided to learn how to use createAudioSlice() and selectRandomFile(). I will further explain createAudioSlice() below since it is more interesting.



## Engineering Design Process (EDP)

Currently, I am still at stage 5 of the Engineering Design Process: <b>creating a prototype</b>. Since music is going to be the big piece of my program, I need to push myself to finish it. So far, I made at least four music that has no lyrics. I generally think that people will be more likely to focus on what they are doing with music that has no lyrics much better. This is even backed up on multiple researches which you can search up on your own time. Back to what I was saying, I have been revising my music weekly. All of them are different genres or moods when you hear them: hip hop, sad, relaxing, etc. I don't want to give too much away, but I really like how the music is at the moment. I've also started making a dropdown menu of all the music that users can click on to listen to. As for the timer, I haven't started it yet, but I will start creating it soon.

<br>

For the next stage of the Engineering Design Process, I plan to be on stage 6, <b>test and evaluate the prototype</b>. I'm going to be testing if the timer works by counting down, but ends at 0. I will also be testing if the music chosen is running when the timer is clicked. I'll also be evaluating if there are no major bugs happening as well. I'll evaluate if my prototype is easy to use by using small icon images and making sure I don't write long paragraphs for the directions.






## Knowledge

As mentioned earlier, I relearned about functions from this <a href="https://workshops.nuevofoundation.org/python-earsketch/7-activity-3-organize-songs-using-functions/">website</a>. On the website, it showed one of this code:

<br>

```
def sectionA(startMeasure, endMeasure):
    fitMedia(RD_UK_HOUSE__AIRYPAD_1, 1, startMeasure, endMeasure)
    fitMedia(HOUSE_MAIN_BEAT_002, 4, startMeasure, endMeasure)
    fitMedia(HOUSE_ROADS_BASS_001, 5, startMeasure, endMeasure)

sectionA(1, 9)
```

<br>

Here I modified it to Javascript while I was tinkering in EarSketch:

```
function sectionA(startMeasure, endMeasure) {
    fitMedia(RD_POP_PADCHORD_1, 1, startMeasure, endMeasure)
    fitMedia(YG_POP_SNAP_1, 2, startMeasure, endMeasure)
    fitMedia(RD_POP_MAINBEAT_3, 3, startMeasure, endMeasure)
}

sectionA(3, 6)

```


<br>

Here what this code does is very simple. Once the function is called, it will make the song listed in the function play from the 3rd measure till the 6th measure.


From this, I learned that now I'm able to make multiple sounds play at once a certain time without having to do all that tedious work of ```fitMedia(soundName, what track, what measure to start, what measure to end);``` constantly. It was very efficient indeed.


<br>

Another code from <a href="https://earsketch.gatech.edu/earsketch2/">EarSketch</a> itself on the API section under Content Manager is shown below:

<br>

```
var slice = createAudioSlice(HOUSE_BREAKBEAT_001, 1.5, 2.5);
fitMedia(slice, 1, 1, 3);
```

Here I changed it to this:

```
var end = 21;
var slice1 = createAudioSlice(RD_EDM_ANALOGLEAD_1, 2.2, 4.5);
fitMedia(slice1, 1, 1, end);
```

<br>


<ul>
<li><b>createAudioSlice</b>: cuts parts of your audio on what you like</li>
<li><b>RD_EDM_ANALOGLEAD_1</b>: audio name</li>
<li><b>2.2</b>: start of audio measure you'll keep </li>
<li><b>4.5</b>: end of audio measure you'll keep </li>
</ul>


Here I learned that createAudioSlice() will literally slice some parts of the music out on what you do like. This is extremely helpful since if a certain part of the audio is too loud or quiet, it might be unpleasant for some users.

<br>


## Planning for MVP


As for my process of planning for my MVP, I have been working once a week on this project of small tasks I want to get done. I've decided that this project was going to be a website that has music and a timer that help users to study, relax, etc. This is my plan so far:

<ul>
<li>Prompt that asks user how many minutes they want the timer to run</li>
<li>Displays a timer that counts down</li>
<li>Dropdown menu for music list</li>
<li>A button to start timer</li>
</ul>

I also have many other ideas like adding a reset button, dark mode/light mode background option, and more. All of these I will add if I have extra time when I finish the general purpose of how I want my website to run.

So far, I'm revising my music and making final finish touches to it! I've also started making a dropdown menu for the music list and if everything goes to plan...I'll be working on the timer by next week!


## Skills

The skills I used are <b>attention to detail</b> and <b>time management</b>.

I used the skill, <b>attention to detail</b> when I started to revise all my current music. I mostly paid attention on whether if the music didn't flow, if it was too loud, too quiet, too much sounds, etc. All of these played a major role for good quality music to which users don't really ponder much about. All these changes do make a difference--even if it is a small difference.

I also used the skill, <b>time management</b> when it came to working on my MVP plan. Since I only have a month left to finish this year long project, time is very limited. I recently started using a sheet of looseleaf as my planner where I would create checklists on tasks that I needed to complete. I always complete the easier tasks first and then work on the more difficult tasks. I would use the Pomodoro technique to help me know when to take breaks. All of these helped me immensely on time management.




[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)