# Assumptions
[[Small angle approximations]]
*small angle approximations are only in radians so you can only differentiate trig functions in radians*
$$\sin x \sim x$$
$$\cos x \sim1-\frac{1}{2}x^{2}$$
This means
$$\lim_{dx \rightarrow 0} \; \frac{\sin dx}{dx}=\frac{dx}{dx}=1$$
$$\lim_{dx \rightarrow 0} \; \frac{\sin dx}{dx}=1$$
and
$$\lim_{dx \rightarrow 0} \; \frac{\cos dx -1}{dx}=\lim_{dx \rightarrow 0} \; \frac{1-\frac{1}{2}dx^{2}-1}{dx}=\lim_{dx \rightarrow 0} \;-\frac{1}{2}dx=0$$
$$\lim_{dx \rightarrow 0} \; \frac{\cos dx -1}{dx}=0$$
# Sin
$$y=f(x)=\sin kx$$
$$\frac{dy}{dx}=f'(x)=k\cos kx$$
## Proof
use [[Chain Rule]] to prove $y=\sin kx$ but chain rule is already proved so I'm going to cover the important stuff through first principle
$$y=\sin x$$
$$y+dy = \sin (x+dx)$$
$$dy= \sin (x+dx) -\sin x$$
[[Double angle theory]]
$$dy= \sin x \cos dx + \sin dx \cos dx -\sin dx$$
$$dy= \sin x(\cos dx -1)+\cos x(\sin dx)$$
$\div dx$
$$\frac{dy}{dx}= \sin x(\frac{\cos dx -1}{dx})+\cos x(\frac{\sin dx}{dx})$$
using the assumptions
$$\frac{dy}{dx}=(0)\sin x + (1)\cos x$$
$$\frac{dy}{dx}=\cos x$$
# Cos
$$y=f(x)=\cos kx$$
$$\frac{dy}{dx}=f'(x)=-k\sin kx$$
## Proof
use [[Chain Rule]] to prove $y=\cos kx$ but chain rule is already proved so I'm going to cover the important stuff through first principle
$$y=\cos x$$
$$dy + y = \cos{(x+dx)}$$
$$dy=\cos{(x+dx)}-\cos x$$
[[Double angle theory]]
$$dy=\cos x \cos dx - \sin x \sin dx - \cos x$$
$$dy=\cos x (\cos dx -1)-\sin x(\sin dx)$$
$$\frac{dy}{dx}=\cos x (\frac{\cos dx -1}{dx})-\sin x(\frac{\sin dx}{dx})$$
using the assumptions
$$\frac{dy}{dx}=\cos x (0)-\sin x (1)$$
$$\frac{dy}{dx}=-\sin x$$
