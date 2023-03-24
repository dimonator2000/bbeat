# Enhanced-Bytebeat

You can check it out [here](https://dimonator2000.github.io/bbeat/).

Bytebeat music (or one-liner music) was invented in September 2011. They're generally a piece of rhythmic and somewhat melodic music with no score, no instruments, and no real oscillators. It's simply a single-line formula that defines a waveform as a function of time, processed (usually) 8000 times per second, resulting in an audible waveform with a 256-step resolution from silence (0) to full amplitude (256). If you put that formula into a program with a loop that increments time variable (t), you can generate the headerless unsigned 8 bit mono 8kHz audio stream on output, like in this application. Since these directly output a waveform, they have great performance in compiled languages and can often be ran on even the weakest embedded devices.

This player includes new functions to play with! Like `br()`, `bre()`, and more...

To some people, this is against bytebeat; the whole point is to have everything needed in the code itself; if that's what you want, you can use [another player.](https://dollchan.net/bytebeat/) I just want to have some fun making my own \:3

Post your creations [here!](https://www.reddit.com/r/Enhanced_Bytebeat/)
