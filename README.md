# protected lm2575 buck converter

all-tht adjustable step-down converter with three input protection stages.

## specs

- regulator: lm2575bt-adj (12 v input, 1.23 v to 10 v adjustable output via r1 3k and rv1 25k, plus sw1 on/off switch)
- overcurrent protection: ruef250 resettable ptc fuse (trips at 5 a)
- reverse polarity protection: fqp27p06 p-mosfet with 1n4744a 15 v zener diode and r4 10k resistor
- transient protection: 1.5ke27a tvs diode (clamps voltage spikes at 37.5 v, below the 40 v chip limit)
- pcb: 2-layer tht layout with 0.8 mm minimum trace width and 0 drc errors   
