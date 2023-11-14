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