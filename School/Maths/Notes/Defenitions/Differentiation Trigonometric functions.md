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

# Tan
$$y=f(x)=\tan kx$$
$$\frac{dy}{dx}=f'(x)=k\sec kx^{2}$$
## Proof
use [[Quotient Rule]]
$$y=\frac{\sin x}{\cos x}$$
$$\frac{dy}{dx}=\frac{(\cos x *\cos x)-(\sin x*-\sin x)}{\cos^{2}x}$$
$$\frac{dy}{dx}=\frac{\cos^{2}x + \sin^{2}x}{\cos^{2}x}=\frac{1}{\cos^{2}x}$$
$$\frac{dy}{dx}=\sec^{2}x$$
# Cosec
$$y=\csc kx$$
$$\frac{dy}{dx}=-k \csc kx \;\cot kx$$
## Proof
$$y=\csc x =\frac{1}{\sin x}=\sin^{-1}x$$
applying [[Chain Rule]]
$$\frac{dy}{dx}=-1*\cos x*\sin^{-2}x$$
$$\frac{dy}{dx}=-\frac{\cos x}{\sin x}*\csc x=-\csc x \;\cot x$$
# Sec
$$y= \sec kx$$
$$\frac{dy}{dx}=k \sec kx \; \tan kx$$
## Proof
$$y=\csc x = \frac{1}{\cos x} = \cos^{-1}x$$
applying [[Chain Rule]]
$$\frac{dy}{dx}=-1*-\sin x*\cos^{-2}x$$
$$\frac{dy}{dx}=\frac{\sin x}{\cos x}*\sec x=\tan x \sec x$$
# Cot
$$y=\cot kx$$
$$\frac{dy}{dx}=-k \csc^{2}kx$$
## Proof
$$y=\frac{\cos x}{\sin x}$$
apply [[Quotient Rule]]
$$\frac{dy}{dx}=\frac{(\sin x*\sin x)-(\cos x*-\cos x)}{\sin^{2}x}$$
$$\frac{dy}{dx}=\frac{\sin^{2}x+\cos^{2}x}{\sin^{2}x}=\frac{1}{\sin^{2}x}$$
$$\frac{dy}{dx}=\csc^{2}x$$
