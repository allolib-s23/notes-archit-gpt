# notes-archit-gpt

# archit_demo01: lofi piano
- this piece is an original composition
- to run: change into the demo1-archit-gpt directory. run ./run.sh tutorials/synthesis/archit_demo01.cpp
- this was my first time having the opportunity to play around with allolib and all of its various paramaters. my goal was to try using additive synthesis to create a very simple lofi piano piece that utilizes simple drums in the background.

# archit_demo02: loft music
- this piece is an original composition
- to run: change into the demo1-archit-gpt directory. run ./run.sh tutorials/synthesis/archit_demo02.cpp
- my goal was to expand on my original composition. I used the same piano instrument (sine wave) as in my first demo to create an entirely different melody, but used a metronome function to add a separate hihat for more complexity. I also added different melodic elements to differentiate between separate bars, and a unique ending that fades out.

# archit_demo03: lounge 64
- this piece is an original composition
- to run: change into the demo1-archit-gpt directory. run ./run.sh tutorials/synthesis/archit_demo03.cpp
- my focus was turning loft music into a complete song, and also experimenting with adding one of my favorite modern day instruments utilized across popular music of all types today: the sub bass, aka the 808. To accomplish this, I used a function called playBass(), which would play sine waves at extremely low frequencies. From my own knowledge of music production and audio engineering, I knew that we can take a sine wave and play its signal at a very low frequency on the 20-20000hz bandwith to get the same effect as a sub bass.
- i also added a secondary melody that contrasts the first to give the entire song a less repetitive feeling, and an ending that is previewed slightly in the third to last bar, before being fully displayed at the end.
- i also added basic graphics to the final piece; the blue circle corresponds to the bass being played

# archit_demo04: passionfruit
- this piece is a transcription of the song "passionfruit" by drake. 
- to run: change into the demo1-archit-gpt directory. run ./run.sh tutorials/synthesis/archit_demo04.cpp
- i wanted to take a different sonic approach to this incredibly popular song by drake, who is one of the biggest artists in the world. Instead of using the marimba or xylophone, i wanted to transcribe passionfruit into an orchestral sounding song for heavy contrast, as opposed to its famous tropical vibe. to accomplish this, i experimented with the karplus plucked string technique using the plucked string class, and was able to emulate the sound of a classical organ. I also added an entirely different drum pattern than the 4on4 drum beat we see in the original song
- i utilized Christine's approach of converting sheet music to midi, and then midi to json, to be able to process the actual music. Thank you Christine!

# archit_demo05: interstellar (main theme)
- this piece is a transcription of the soundtrack OST "interstellar (main theme)" composed by hans zimmer. 
- to run: change into the demo1-archit-gpt directory. run ./run.sh tutorials/synthesis/archit_demo05.cpp
- for my final project, i wanted to take on a challenge that would incorporate all my learning in this class, and all of the various sonic techniques that i've had the opportunity of experimenting with in the past several weeks. this includes sine wave modulation, additive/FM synthesis, and the karplus-plucked string. For this task, i decided to recreate one of my favorite musical compositions of all time, the main theme from the movie interstellar. 
- i decided to attempt an integration of the sine wave functions and the plucked string, to create a hybrid transcription of sorts, where the underlying tones are played with the plucked string, and the higher frequencies are played with the sine wave instruments.
- once again, i utilized Christine's approach of converting sheet music to midi, and then midi to json, to be able to process the actual music.
- finally, for graphics, i really liked how Sirui did his for the project he presented at the allosphere, where he had the galactic looking circles rain down from the sky and fade into the bottom of the screen, corresponding to the sine notes being played. as this piece is from interstellar, my favorite space exploration movie of all time, i decided that replicating something similar in my piece would only be fitting. 
- as such, my graphics consist of a combination of these circles and the spectogram graphics for the plucked string
 
