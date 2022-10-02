# Horse Pulse

Horse Pulse is a sample library for Plogue Sforzando version 1.971 or newer. It contains samples of a bass tagelharpa played pizzicato.

## Usage

To register the Sforzando bank, drag the Horse Pulse.bank.xml file onto the Sforzando interface. Once registered, the instrument will be available in the Sforzando loading menu and the GUI will work.

## Features

Techniques:
* Pluck - a hard pluck with the tip of the finger, recorded with six round robins
* Scrape - a softer brush of the fingertip across the string, with four round robins
* Soft scrape - a very soft brush, with two round robins
* Nail - stroking the string with the fingernail, with four round robins
* Flam - several fingertip and/or nail strikes in a row
* FX - percussive, slide and handling noise FX

"VSOP" mode stands for velocity switch operation; here note velocity does not control the dynamics of the pitched notes (though it still does that for the FX), but instead different velocity ranges select different articulations:  
* 1 to 32 - soft scrape  
* 33 to 73 - scrape  
* 74 to 114 - pluck  
* 115 to 126 - nail  
* 127 - flam  

Control MIDI CC assignments:  
* 31 - width  
* 107 - release  
* 110 - preroll (at 0 approximately 100 ms, at max approximately 10 ms)  
* 113 - deep (an extra copy of the samples, transposed an octave down)

Thanks to Bragi's Workshop for making the instrument.

Royalty-free for all commercial and non-commercial use. Copyright 2022 Karoryfer Lecolds.
