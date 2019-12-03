# PCRdemo2015
## License: MIT License

Demo code for [PCR-Badge-2015 demo board](https://github.com/plocher/PCR-Badge-2015)

Includes LEDs (R/R for Xing, RYG for a signal), pushbuttons, 
a servo and an LCD.

The demo uses the buttons to raise and lower the crossing gate and
turn on/off the blinking crossing lights.

The demo also runs timed activities "in the background", so that the
signal changes aspects and the crossing automatically triggers every
once in a while.

BUGS: The board also includes provisions for an IR sensor - unfortunately,
the circuit was miswired to a digital pin instead of an analog one, so
it doesn't (and can't) work without board trace rerouting.  Oops.

