# Simple Harmonic Motion
- [[Simple Harmonic Motion]]
# Calculations
$$a = -\omega^2 x$$

| Symbol   | Unit        | Definition        |
| -------- | ----------- | ----------------- |
| $a$      | $ms^{-2}$   | Acceleration      |
| $\omega$ | $rads^{-1}$ | [[Angular Speed]] |
| $x$        |  $m$           |   [[Displacement]] from equilibrium                |

$$x = A \cos \omega t$$
$$v = -A \omega \sin \omega t$$
$$a = -A \omega^{2} \cos \omega t$$

| Symbol | Unit | Definition |
| ------ | ---- | ---------- |
| $x$    | $m$     |  [[Displacement]]          |
| $v$       | $m \,s^{-1}$     | Linear [[Velocity]]          |
| $a$       | $m \,s^{-2}$     | [[Acceleration]]           |
| $A$      | $m$     |  [[Amplitude]]          |
| $\omega$ | $rad \,s^{-1}$     | [[Angular Speed]]         |
| $t$      | $s$     | time           |
# Calculation Time period
- [[Simple Pendulum]]
- [[Mass-spring system]]
# Graphs
*All these graphs are under the assumption there is no damping*
## Displacement
$$x = A \cos \omega t$$
```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [0,15,-10,10]
disableZoom: false
grid: true
---
y = 5 cos(2x)
```

Note that displacement can't start at 0
## Velocity 
*Derivative of displacement time graph*
$$v = -A \omega \sin \omega t$$
```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [0,15,-15,15]
disableZoom: false
grid: true
---
y = -10 sin(2x)
```
## Acceleration
*Derivative of velocity time graph*
$$a = -A \omega^{2} \cos \omega t$$
```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [0,15,-25,25]
disableZoom: false
grid: true
---
y = -20 cos(2x)
```
# Resonance
- [[Resonance]]
# Damping and energy conservation
# Free and Forced vibrations
# Effect of damping on resonance
# Reducing the amplitude of oscillation
