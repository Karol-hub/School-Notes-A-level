# Laws
## Multiplication law
$$\log_a{x}+\log_a{y}=\log_a{xy}$$
### Proof
let $m=\log_{a}{x}$, $n=\log_{a}{y}$
$$m=\log_{a}{x} \rightarrow a^{m}=x$$
$$n=\log_{a}{y} \rightarrow a^{n}=y$$
Multiply them together
$$xy=(a^{m})(a^{n})=a^{m+n}$$
Take $log_a$ of both sides
$$\log_a{(xy)}=\log_{a}(a^{m+n})=m+n$$
sub $m$ and $n$ back into the equation
$$\log_{a}(xy)=\log_{a}{x} + \log_{a}{y}$$
## Division law
$$\log_{a}x-\log_{a}y=\log_{a}\frac{x}{y}$$
### Proof
let $m=\log_{a}{x}$, $n=\log_{a}{y}$
$$m=\log_{a}{x} \rightarrow a^{m}=x$$
$$n=\log_{a}{y} \rightarrow a^{n}=y$$
Divide them
$$\frac{x}{y}=\frac{a^{m}}{a^{n}}=a^{m-n}$$
Take $log_a$ of both sides
$$\log_{a}\frac{x}{y}=\log_{a}a^{m-n}=m-n$$
sub $m$ and $n$ back into the equation
$$\log_{a}\frac{x}{y}=\log_{a}{x} - \log_{a}{y}$$
## Power law
$$\log_{a}(x^{k})=k \log_{a}x$$
### Proof
let $m=\log_{a}{x}$
$$m=\log_{a}{x} \rightarrow a^{m}=x$$
Raise to the power of $k$
$$x^{k}=(a^{m})^{k}$$
$$x^k=a^{mk}$$
Take $\log_a$ of both sides
$$\log_{a}(x^{k})=\log_{a}(a^{mk})=mk$$
sub $m$ back into the equation
$$\log_{a}(x^{k})=k\log_{a}{x}$$
## Change of base law (not needed)
$$\log_{a}x=\frac{\log_{b}x}{\log_{b}a}$$
### Proof
let $m=\log_{a}x$  
$$m=\log_{a}{x} \rightarrow a^{m}=x$$
Take $\log_{any \; base}$ in this case $b$
$$\log_{b}x=\log_{b}(a^{m})$$
Apply power law
$$\log_{b}x=m\log_{b}a$$
divide both sides by $\log_{b}a$
$$\frac{log_{b}x}{\log_{b}a}=\frac{m\log_{b}a}{\log_{b}a}=m$$
sum $m$ back into the equation
$$\frac{log_{b}x}{\log_{b}a}=\log_{a}x$$
# Special cases
## Power law when power =-1
$$\log_{a}\frac{1}{x}=\log_{a}x^{-1}=-\log_a{x}$$
## Base same number
$$\log_{a}a=1$$
## Value is 1
$$\log_{a}1=0$$