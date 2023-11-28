The rate at which a variable changes with respect to time

# Example 1
Find the rate of change of the radius of a sphere at the instant when the radius is $4cm$, given that the surface area is increasing at a rate of $15cm^{2}s^{-1}$
$$\frac{dr}{dt}=\frac{dr}{dA}*\frac{dA}{dt}$$
$$\frac{dA}{dt}=15$$
$$A=4\pi r^{2} \therefore \frac{dA}{dr}=8 \pi r$$
$$\frac{dr}{dA}*\frac{dA}{dt}=\frac{dr}{dt}=\frac{1}{8 \pi r}*15$$
$$\frac{dr}{dt}=\frac{15}{8 \pi r}$$
$$\frac{15}{8 \pi (4)}=0.1492...= \;0.149(3sf)$$
# Example 2
The formla of a hemisphere $Vcm^{3}$ is related to it's radius $rcm$ by the formula $V=\frac{2}{3}\pi r^{3}$ and the total surface area $Scm^{2}$ is given by the formula $S=3\pi r^{2}$ Given that the rate of increase of volume is $6cm^{3}s^{-1}$, find the rate of increase of the surface area
$$\frac{dV}{dr}=2\pi r^{2} \; \; \; \frac{dS}{dr}=6\pi r \; \; \; \frac{dV}{dt}=6$$
$$\frac{dS}{dt}=\frac{dS}{dr}*\frac{de}{dV}*\frac{dV}{dt}$$
$$\frac{dS}{dt}=6 \pi r * \frac{1}{2\pi r^{2}} * 6$$
$$\frac{dS}{dt}=\frac{18}{r}$$
# Example 3
The number of bacteria, b, in a petri dish is increasing over time, t, at a rate directly proportional to the number of bacteria. Formulate a differential equation to show this information
$$\frac{db}{dt} \propto b \rightarrow \frac{db}{dt}=kb$$
for some constant $k,k>0$