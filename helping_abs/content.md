# Readme_helping_abs
what You find here is some abstractions and links helping You to dealing with sensor data:

## scaling:

fom the famous [rjdj-lib](https://puredata.info/downloads/rjlib) use the m_* objects for different mapping purpurses. Of course also the oser abstractions are worth exploring. The help files give You information how to use them<br>
 For Your convienience I copied the most important also to this directory:<br>
**m_autoscale** - scale numbers with a dynamically detected input range<br>
**m_scale** - scale ranges<br>
**m_sm2ms** - convert duration in samples to duration in milliseconds<br>
**m_ms2sm** - convert duration in milliseconds to duration in samples<br>
**m_speedlimit** - impose upper limit on message speed<br>
**m_thresholds** - detect threshold crossings<br>
## bonus:
**a_breath** - breath controller that analyses the mic input volume

## fyi:

some abstractions might need an external or other abstractions to work (You'll get an error message in the pd console). You find at least the playback, recorder, soundoutput, soundinput abstractions here. For more on the library open the _OVERVIEW.pd_ patch or look at  https://puredata.info/downloads/rjlib<br>
the s_* objects are synths and other sound generating abstractions<br>

## P.S.:
if You still don't know what an abstraction or subpatch is, look here: https://www.youtube.com/watch?v=6BfC6ovRRPs

## P.S.P.S
If You need an [external](http://write.flossmanuals.net/pure-data/introduction2/) and Deken vie help->find externals did't find it look at https://puredata.info/docs/ListOfPdExternals/. If its necessary for the final object You have to check if its running/available for RaspberryPi's
