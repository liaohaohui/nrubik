# nrubik
An N-Curses Based, Virtual Rubik's Cube

NRubik was made due to the severe lack of n-curses based virtual Rubik's cubes. This very possibly might be the first one. 

# About

I followed https://www.maketecheasier.com/play-rubiks-cube-terminal-linux/
which leads me to a no longer existing github repository https://github.com/cheertarts/ 

I did a search and found that https://github.com/calebabutler/ kept a copy, so I forked
it (just in case the repository is closed).

I am bad with Rukik's Cube, so a handy software will save me.

A fancier nrubik is found at https://github.com/linuxCowboy/nrubik2

# How do I install it?

Simply download the single, small "nrubik" python script and run it with a curses supported python2 or python3 interpreter. (Yes, the script works with both python2 and python3 :)

On Linux:

    git clone https://github.com/calebabutler/nrubik
    cd nrubik
    chmod +x nrubik
    # To install globally
    cp nrubik /usr/local/bin/

# What does it look like?

Something like this:

![Screenshot](/nrubik-screenshot.png?raw=true)

Here is it solved (Yes, it's possible):

![Screenshot](/nrubik-screenshot-solved.png?raw=true)

# Why is orange magenta?

On 8 color terminals, there is no orange but there is magenta. If you're confused why it's labeled orange in the first place, on an ordinary Rubik's Cube that is where orange would be.
