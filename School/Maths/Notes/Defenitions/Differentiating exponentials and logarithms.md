# Exponentials
$$y=e^{f(x)}$$
$$\frac{dy}{dx}=f'(x)e^{f(x)}$$
## Proof
can do it with [[Chain Rule]]
$$y=e^{f(x)}$$
$$u=f(x)$$
$$\frac{du}{dx}=f'(x)$$
$$y=e^{u}$$
$$\frac{dy}{du}=e^{u}$$
$$\frac{dy}{du}*\frac{du}{dx}=\frac{dy}{dx}=f'(x) * e^{f(x)}$$
$$\frac{dy}{dx}=f'(x)e^{f(x)}$$
# Logarithms
$$y=\ln f(x)$$
$$\frac{dy}{dx}=\frac{f'(x)}{f(x)}$$
## Proof
use [[Chain Rule]] to prove $y=\ln f(x)$ but we ain't here to prove chain rule so here's the important stuff
$$\circledast  \;y=\ln x$$
$$e^{y}=x$$
$$\frac{dx}{dy}=e^y$$
$$\frac{dy}{dx}=\frac{1}{e^y}$$
using $\circledast$
$$\frac{dy}{dx}=\frac{1}{e^{\ln{x}}}$$
$$\frac{dy}{dx}=\frac{1}{x}$$


