# Knitted synthesisers

Wouldn't you like to make [sounds with your trousers](https://www.kickstarter.com/projects/1400947701/drumpants-an-entire-band-in-your-pocket/posts/774182/comments)? Ever looked at a piece of knitwear and thought, I'd like this to produce a horrible noise? Look no further.

This tutorial is based on a workshop run by Agnes. These instructions are based on a tutorial for making two-stage astable oscillators on [Electronics Tutorials](https://www.electronics-tutorials.ws/waveforms/555_oscillator.html), which also gives a lot more information on the electronic theory.

## theory

### making waves


### resistors and capacitors

electrical waves into sound waves

vibration

2 components you need to know: resistor and capacitor

plumbing metaphor

### conductive yarn and variable resistors

Typically, conductive yarn is used differently to conductive thread: it has much higher resistance, which means that it's not used to directly connect components unless they are very close together. However, because the conductive properties of fabrics knitted with conductive yarns change according to the state of the material, they make great sensors.

When a knitted sample is relaxed, it has a high resistance as the fibres in the yarn do not make contact with one another, meaning that current can pass only along a few strands. When the sample is stretched, however, the fibres are pulled into closer contact, reducing the resistance and allowing the flow of an electric current. This means that the inclusion of a conductive yarn allows you to sense movement in the material, creating a stretch sensor.

### 555 timer

timing chip

input exceeds a certain value 

### the astable circuit

"astable" circuits 

## practice

### you will need
* 3.5mm jack breakout (socket)
* a speaker or pair of headphones
* a breadboard
* 2x 555 timers
* jumper wires
* 5V power supply
* 4 crocodile clip cables
* a 100kΩ resistor
* a 10kΩ resistor
* a 10kΩ variable resistor
* a 100kΩ variable resistor
* some conductive knit samples

### note: measuring resistance using a multimeter 

Attach the crocodile clips to the edge of the sample, and connect the other ends to the multimeter. Move the wheel of the multimeter to the setting with the Ω symbol, and press the 'mode' button until you also see a Ω on the screen.

Once the system is connected, you should see a reading of the sample's resistance on the multimeter. Try stretching the sample and the number should decrease! Note that the letters next to Ω refer to the magnitude: k stands for 'kilo' (x1000), and M stands for 'mega' (x 10,000). You want your sample to be at least a few kΩ for this to work.

### note: reading circuit diagrams

On a chip like the 555 timer, pins are numbered from 1-8, and are numbered counter-clockwise, beginning with the pin to the left of the notched end. On the circuit diagram, pins don't appear in this order -- this allows the wires to be represented without needing to cross over one another, but can be confusing when translating into reality.


Here's what the circuit looks like when assembled:

### knitted modular synthesisers

LFO = "low frequency oscillation" -- control voltage

use to time the signal


