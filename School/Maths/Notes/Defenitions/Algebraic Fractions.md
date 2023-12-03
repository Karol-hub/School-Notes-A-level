# Simplification
[[Factorising|Factorise]] top and bottom then cancel
# Addition
$$\frac{x}{x+4}+\frac{4}{x-1}=\frac{x(x+1)}{(x+4)(x-1)}+\frac{4(x+4)}{(x+4)(x-1)}=\frac{x(x+1)+4(x+4)}{(x+4)(x-1)}$$
# Multiplication
$$\frac{x}{x+4}*\frac{4}{x-1}=\frac{4x}{(x+4)(x-1)}$$
# Division
$$\frac{x}{x+4}\div \frac{4}{x-1}=\frac{x}{x+4}*\frac{x-1}{4}=\frac{x(x-1)}{4(x+4)}$$
# Algebraic Division
If you have $$\frac{f(x)}{g(x)}$$
if $f(x)$ and $g(x)$ are polynomials we can represent it in the form $$\frac{f(x)}{g(x)}=Q(x)+r$$
where $Q(x)$ is the quotient and $r$ is the remainder of $\frac{f(x)}{g(x)}$
## Example
$$\frac{x^{3}+x^{2}-7}{x-3}$$
![[Algebraic division example|1000]]
$$\frac{x^{3}+x^{2}-7}{x-3}=x^{2}+4x+12+\frac{29}{x-3}$$
# Partial Fractions
Start with factorising the denominator
Easiest to explain with example
## Example
$$\frac{6x^{2}+5x-2}{x(x-1)(2x+1)}$$
$$\frac{6x^{2}+5x-2}{x(x-1)(2x+1)}=\frac{A}{x}+\frac{B}{x-1}+\frac{C}{2x+1}$$
$$*x(x-1)(2x+1)$$
$$6x^{2}+5x-2=A(x-1)(2x+1)+Bx(2x+1)+Cx(x-1)$$
Use substitution to make the coefficient of $A,B$ or $C$ 
let $x=0$
$$-2=A(0-1)(2(0)+1) +0B+0C$$
$$-2=-A$$
$$\therefore A=2$$
Now we have the formula
$$6x^{2}+5x-2=2(x-1)(2x+1)+Bx(2x+1)+Cx(x-1)$$
Now let $x=1$
$$6(1^{2})+5(1)-2=0+B(1)(2(1)+1)+0C$$
$$9=3B$$
$$\therefore B=3$$
Now we have the formula
$$6x^{2}+5x-2=2(x-1)(2x+1)+3x(2x+1)+Cx(x-1)$$
We can sub any value for $x$ now that $C$ is our only unknown
Now let $x=-0.5$
$$6(-0.5^{2})+5(-0.5)-2=0+0+C(-0.5)(-0.5-1)$$
$$-3=0.75C$$
$$\therefore C=-4$$
And we put it in the final form
$$\frac{6x^{2}+5x-2}{x(x-1)(2x+1)}=\frac{2}{x}+\frac{3}{x-1}-\frac{4}{2x+1}$$
# Repeated linear factors
When the denominator has repeated factor the method needs to be modified
# Example
$$\frac{2x^{2}+2x-18}{x(x-3)^{2}}$$
The factor $(x-3)$ is repeated so when we split the fraction we need to account for this.
$$\frac{2x^{2}+2x-18}{x(x-3)^{2}}=\frac{A}{x}+\frac{B}{(x-3)^{2}}+\frac{C}{(x-3)}$$
