The atoms in most solids are arranged in a crystal lattice structure as shown below:
![[metal lattice arrangement.png]]
- As temperature increases the particles have enough energy to release electrons through thermionic emission
	- Increases charge carrier number
	- Hence resistance is decreased
- Increased temperature also causes the particles in the lattice to vibrate and hence charge carriers are more likely to collide with the atoms but the free charge carriers outweighs the effects of this
# NTC Graphs
Negative Temperature Coefficient
- As temperature increases resistance decreases
- At low [[Current|currents]], where temperature is kept constant, Ohm’s law is obeyed
# Graphs
![[Thermistor (NTC) VI graphs.png]]
Gradient on right graph is resistance
```functionplot
---
title: NTC Resistor
xLabel: Temperature /°C
yLabel: Resistance /Ω
bounds: [0,10,0,10]
disableZoom: true
grid: false
---
y=5/(2x)
```
# This effect in a wire
- Lattice vibrations increase resistance as temperature increases
- Some charge carriers are released but not enough to counter the effect

```functionplot
---
title: 
xLabel: Temperaturr /°C
yLabel: Resistance /Ω
bounds: [0,10,0,10]
disableZoom: true
grid: true
---
y=2^(0.3x)
```
