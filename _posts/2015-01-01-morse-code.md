---
title: Morse Code
---

<br>
Some of you last week noticed that with our LED switch, we could send messages in <a href="http://en.wikipedia.org/wiki/Morse_code">Morse code</a> if we wanted to. This is a really cool idea, so we thought we'd look at it in a bit more detail and see if we can maybe even get scratch to send some messages in morse code by itself. For those of you that don't know what Morse code is, here's the wikipedia definition : 

> Morse code is a method of transmitting text information as a series of on-off tones, lights, or clicks that can be directly understood by a skilled listener or observer without special equipment.

It was developed in the 1830's to send messages quickly over long distances using an <a href="http://en.wikipedia.org/wiki/Electrical_telegraph">electrical telegraph.</a> It was invented a several decades before the telephone, and was so useful it was still used at sea until 1999. 


Here is a chart of the letters A-Z, and the numbers 0-9 in Morse Code :

![Morse Alphabet](../img/International_Morse_Code.png "Morse Alphabet")

The timing between the dots and dashes is important because we don't want our message to be misunderstood. Everything depends on how long a single dot is, so if a dot was 1 second long : 

- A dash would have to be 3 seconds long.
- The space between two parts of the same letter would have to be 1 second long.
- The space between letters would have to be 3 seconds long.
- The space between words would have to be 7 seconds long.

<br>
Using a whole second for a dot would take aaaaages to send a very long message so we probably don't want to do that. Have a look at these words, and see if you can translate them. Notice how many seconds each one would take if each square was a second : 

<br>
![Morse 1](../img/morse_1.png "Morse 1")
<br>
![Morse 2](../img/morse_2.png "Morse 2")
<br>
![Morse 3](../img/morse_3.png "Morse 3")

## Morse code challenge

<br>
Let's try and write our own program to send Morse code. We have made this little guy out of a light dependent resistor (something we will look at next week) and programmed him so he can read your morse code transmissions!

So that we can understand everyone's Morse code, let's all use 0.1 seconds as the length of a dot. This means that :

- A dash would have to be 0.3 seconds long.
- The space between two parts of the same letter would have to be 0.1 second long.
- The space between letters would have to be 0.3 seconds long.
- The space between words would have to be 0.7 seconds long.

<br>
Have a go at making a program that sends your name in Morse code, and then we'll talk about how different people have approached the problem, and show you how we decided to do it.

