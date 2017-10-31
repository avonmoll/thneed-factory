thneed-factory
==============

An attempt at making a PC-based rhythmic analyzer.

## Background
The goal was to be able to use Python and a PC with a microphone as a rhythmic analyzer for drumming. The Jupyter (IPython) notebooks contain proof of concept code. It is shown that with my setup, there was too much temporal jitter in processing the audio and thus the project could not move forward as is.

## Ideas for Improvement
A more robust approach would be to physically detect beats using, for example, a force-sensitive resistor embedded in the drum/drumpad and connecting to an Arduino for closer-to-realtime signal processing (and then sending data/"hits" to the PC over serial connection).
