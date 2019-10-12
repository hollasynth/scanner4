# Hollasynth Four Channel Scanning VCA

##  What is it?

The Hollasynth four-channel scanning VCA is a version of Jurgen Haible's [Interpolating Scanner](http://jhaible.com/legacy/tonline_stuff/jh_ipscan.html) idea, in 4U Serge-compatible format, complete with a beautiful front panel by [Loudest Warning](http://www.loudestwarning.co.uk/portfolio/hollasynth-four-channel-scanning-vca/)

It is a four-channel voltage controlled crossfader. As the scan CV is swept from 0V to 5V, the mix output fades from channel 1, through a mix of channel 1 and 2, to channel 2, then fades to channel 3 and finally channel 4. In addition to the main mix output, each channel has an individual output. Front panel knobs provide an offset and attenuversion on the scan CV. 

The gain of each channel is also individually controllable, so the module can be used as a four channel VCA as well. A switch allows the scanning control to be disabled so that only the VCA CV affects channel gain. Finally there are attenuators and initial gain knobs on the front panel.

##  What can I do with it?

Probably more than I can! But try some of these: 

 - Crossfade between the wave shapes of a VCO for voltage-controlled morphing, e.g. from sine to saw to triangle to square and back
 - Crossfade between up to four audio sources under voltage control
 - Voltage controlled CV mixing. The inputs and outputs are DC coupled so you can use the module to mix and morph between CV sources
 - Voltage controlled signal switching. By appying stepped CV to the scan input, e.g. from a sequencer, you can switch between signals rather than fading... if you get the CV set up just right!

## How does it work?

The scanner contains four linear VCAs, one per channel, based on the LM13700 IC. Each VCA is controlled by the sum of two CVs: the direct VCA CV and the scanning CV. The scan CV is provided by a version Don Tillman's beautiful [scanner implementation](http://till.com/articles/scanner/index.html), used with his kind permission. (But please don't bug him if you have issues with the module!)

## Build notes

 - [Bill of materials](bom.pdf) 
 - [Interactive BOM](ibom.html) to help place the parts (experimental!) 








