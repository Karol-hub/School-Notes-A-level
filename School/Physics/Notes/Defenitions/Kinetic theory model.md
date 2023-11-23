$$PV=\frac{1}{3}Nm<c^{2}>$$

| Symbol    | Unit      | Definition            |
| --------- | --------- | --------------------- |
| $P$       | $Nm^{-2}$ | [[Pressure]]          |
| $V$       | $m^{3}$   | Volume                |
| $N$       | None      | Number of molecules   |
| $m$       | $kg$      | mass of the molecule  |
| $<c^{2}>$ | $ms^{-1}$ | [[Mean Square Speed]] |

# Assumptions (the gas is an [[Ideal Gasses|Ideal gas]])
- No intermolecular forces act on the molecules
- The duration of collisions is negligible in comparison to time between collisions
- The motion of molecules in random, and they experience perfectly elastic collisions
- The motion of the molecules follows Newton’s laws
- The molecules move in straight lines between collisions

# Derivation
![[Kinetic theory derivation cube.png]]
1. Consider a cube with side lengths l, full of gas molecules. One of those molecules has a mass $m$ and is travelling towards the right-most wall of the container, with a velocity $u$. Assuming that it collides with the wall elastically, it's change in [[momentum]] is:
   $$mu-(-mu)=2mu$$
2. Before this molecule can collide with this wall again it must travel a distance of $2l$. Therefore the time between collisions is $t$ where:
   $$t=\frac{2l}{u}$$
3. Using these two bits of information we can find the [[Impulse]] of the molecule. As impulse is equal to the [[force]] exerted we can find the [[pressure]] by dividing our value of impulse by the surface area of one wall
   $$F=\frac{2mu}{\frac{2l}{u}}=\frac{mu^{2}}{l}$$
   $$P=\frac{\frac{mu^{2}}{l}}{l^{2}}=\frac{mu^{2}}{l^{3}}=\frac{mu^{2}}{V}$$
   $V =l^{3}$ since $V$ represents volume
4. The molecule considered is one of many, the total pressure of the gas will be the sum of all the individual pressures caused by each molecule
   $$P=\frac{m((u_{1})^{2}+(u_{2})^{2}+...+(u_{n})^{2})}{V}$$
5. Instead of considering all these speeds we can represent it as the [[Mean Square Speed]] can also be represented as $\bar{u^{2}}$ and if we multiply it be $N$ (the number of particles in the gas), to get an estimate of the sum of the molecules' speeds
   $$P=\frac{Nm\bar{u^{2}}}{V}$$
6. We need to consider all the directions of the molecules, since we only considered one dimension to this point. But the particles move in 3D, we can find the speed using [[Pythagorean theorem]]
   $$\bar{c^{2}}=\bar{u^{2}}+\bar{v^{2}}+\bar{w^{2}}$$
   where $u$, $v$ and $w$ are the components of the molecules velocity in the x, y and z directions. As the motion of the particles is random we can assume the mean square speed in each direction is the same 
   $$\bar{u^{2}}=\bar{v^{2}}=\bar{w^{2}} \; \therefore \; \bar{c^{2}}=3\bar{u^{2}}$$
   Now we put this into our equation and rearrange
   $$<c^{2}> \text{is the same as} \; \bar{c^2}$$
   $$PV=\frac{1}{3}Nm<c^{2}>$$