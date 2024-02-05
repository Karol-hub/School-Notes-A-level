The opposite of [[Differentiation]]
$\int$ is the symbol for integration
If
$$\frac{dy}{dx}=f(x)$$
then
$$y=\int{f(x)} \; dx$$
$dx$ shows we are integrating with respect to $x$
# Definite integrals
$$\int^{b}_{a}{f'(x)}\;{dx}=[f(x)]^{b}_{a}=f(b)-f(a)$$
When dealing with definite integrals we don't have to consider the constant of integration because if we did we would get $f(b)+c-(f(a)+c)=f(b)-f(a)$ the constant cancel each other out so it doesn't need to be considered.
# Integrating polynomials
$$\int{kx^{n}}\;dx=k(\frac{x^{n+1}}{n+1})+c$$
- When differentiating you lose the $+c$ (constant of integration)
- So when integrating you need to add the $+c$ 
# Finding constant of integration
$c$ - constant of integration
- If you are given $f'(x)$ and a point in which $f(x)$ passes through eg $(a,b)$  
- find $f(x) +c$ through integration
- $f(a)+c = b$ then rearrange 
- $c=b-f(a)$ 
# Finding Areas
If we had the curve $y=f(x)$ and wanted to find the area between the two $x$ coordinates $a,b$ we can use definite integrals
$$Area=\int^{b}_{a}f(x)\; dx$$
![[Area under curve example]]
## Areas under x-axis
Area under the x-axis will be negative so when integrating 
so if we wanted to find area under curve below with the equation $y=f(x)$
![[Negative area under graph example]]
If you were to integrate from $a$ to $b$ you would get the wrong answer sine the area in red would be negative and area in blue would be positive. So you would have to do
$$\left(\int^{a}_{0}f(x)\ dx\right)+|\int^{0}_{b}f(x) \ dx|$$
## More complicated areas
### Method 1
Difference of areas
![[Complex area integration|1000]]
- Find area under curve in the segment (area in blue)
- Find area under line (area in red)
- Difference can be used to find area under curve segment (area in black)
### Method 2
![[Complex area integration example]]
Let $y=f(x)$ be the black curve
ley $y=g(x)$ be the red line
we can do
$$\int_{0}^{A_{x}}f(x)-g(x) \ dx$$
to get the area of the shaded region
# Integrating x^-1
The only function in the form of $x^n$ that cannot be integrated is $x^{-1}$ because $\frac{x^{0}}{0}$ will give us an undefined answer
$$\int \frac{1}{x} dx=ln|x|+c$$
# Integrating trig
## basic
$$\int \cos x dx = \sin x + c$$
$$\int \sin x dx = -\cos x +c$$
## harder
$$\int \sec^{2}x dx=\tan x +c$$
$$\int \csc x \cot x dx =-\csc x + c$$
$$\int \csc^{2}x dx = -\cot x + c$$
$$\int \sec x \tan x dx = \sec x + c$$
# Even harder trig
- [[Reverse Chain Rule]]
# Integration by substitution
- Use the expression for $u$ to find $\frac{du}{dx}$ and rearrange for $dx$
- Substitute $u$ into the integral and replace $dx$ in terms of $du$
- Simplify where possible and integrate with respect to $du$
- Replace $u$ with original expression
# Partial Fractions
$$\int \frac{x^{2}+3x-2}{x^2-2x-3}$$
$$\int \frac{x^{2}+3x-2}{x^{2}-2x-3}$$