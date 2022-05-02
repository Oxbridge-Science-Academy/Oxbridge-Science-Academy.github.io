# Rate Constants

You are likely to encountered rate constants (also referred to as rate coefficients) before. They allow the temperature dependence on rates of reaction to be expresed matheamtically. While not always the case, the majority of the reactions you will encounter in undergraduate chemistry speed up with temperature - they have a positive temperature dependence. 

The temperature dependence is represented in the rate constant, <img src="https://render.githubusercontent.com/render/math?math=\displaystyle k">:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle k=Ae^{-\frac{E_a}{RT}}">

Where <img src="https://render.githubusercontent.com/render/math?math=\displaystyle A"> is the pre-exponential factor (temperature independent to a first approximation), <img src="https://render.githubusercontent.com/render/math?math=\displaystyle E_a"> is the activation energy, <img src="https://render.githubusercontent.com/render/math?math=\displaystyle R"> is the gas constant and <img src="https://render.githubusercontent.com/render/math?math=\displaystyle T"> is the temperature in Kelvin. 

### Determining rate constant parameters 
A plot of <img src="https://render.githubusercontent.com/render/math?math=\displaystyle k"> against <img src="https://render.githubusercontent.com/render/math?math=\displaystyle T"> produces a curve from which it is hard to extract information about the parameter of interest, <img src="https://render.githubusercontent.com/render/math?math=\displaystyle E_a">. This is shown below for the reaction of <img src="https://render.githubusercontent.com/render/math?math=O %2B\ O_3 \rightarrow O_2 %2B\ O_2">:

![alt text](https://github.com/Oxbridge-Science-Academy/Figures/blob/master/Chemical_Kinetics/k%20v%20T.png)
 
However, we can manipulate the expression for <img src="https://render.githubusercontent.com/render/math?math=\displaystyle k"> to produce a straight line plot from which it is easier to determine important parameters.

Taking the natural logarithm of both sides:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \ln k = \ln Ae -\frac{E_a}{RT}">

Plotting <img src="https://render.githubusercontent.com/render/math?math=\displaystyle \ln k"> against <img src="https://render.githubusercontent.com/render/math?math=\frac{1}{T}"> will produce a straight line with gradient <img src="https://render.githubusercontent.com/render/math?math=-\frac{E_a}{R}"> as shown below.

![alt text](https://github.com/Oxbridge-Science-Academy/Figures/blob/master/Chemical_Kinetics/lnk%20v%201:T.png)


### Pre-Exponential Factor

While the exponential part of the rate constant allows us to include a temperature dependence, it is clear what the role of the pre-exponential factor is. So far we have made no acknowledgement of the fact that molecules are not spherically symmetric particles. The particular symmetry of atomic and molecular orbitals mean that particles must collide with a particular orientation to allow sufficiently good orbital overlap for a new bond to form. This orientational factor is included in the pre-exponential factor, <img src="https://render.githubusercontent.com/render/math?math=\displaystyle A">. This term does display a (weak) temperature dependence (~ <img src="https://render.githubusercontent.com/render/math?math=T^{\frac{1}{2}}">) but this is beyond the scope of this course and is usually negligible compared to the strong temperature dependence caused by the exponential term.
 
The <img src="https://render.githubusercontent.com/render/math?math=\frac{E_a}{RT}"> term is dimensionless as required and so is the exponential term as a whole. Therefore, the dimensions of the rate constant (see next section) are the same as the dimensions of the pre-exponential factor. It is important to remember that cannot compare a pre-exponential factor from first order and second order reactions directly just as we cannot compare rate constants for a first order and a second order reaction directly. 

### Dimensions of the Rate Constant

Unlike equilibrium coefficients which are strictly dimensionless, the units of a rate coefficient depend on the overall order of the reaction - the sum of the powers of the relevant species' concentrations. The dimensions of reaction rate are concentration per unit time with the most common units used being mol dm<sup>-3</sup> s<sup>-1</sup> for aqueous phase reactions and  molecules cm<sup>-3</sup> s<sup>-1</sup> for gas phase reactions. The dimensions of the rate coefficients must be such that the rate of reaction has the correct dimensions.

Consider a generic rate of reaction:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle rate = k[A]^{\alpha} [B]^{\beta} [C]^{\gamma} ...">

When considering the dimensions, we can merge all the concentration terms in a single concentration raised to a power, <img src="https://render.githubusercontent.com/render/math?math=\displaystyle n">, which is the sum of all the individual powers:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle n = \alpha %2B\ \beta %2B\ \gamma ...">

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle rate = k[X]^{n}">

This provides a way of determining the rate coefficient's units. 

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle k = \frac{rate}{[X]^n}">

Considering units is often the easiest method:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle units = \frac{mol dm^{-3} s^{-1}}{\left(mol dm^{-3}\right)^n} = mol^{1-n} dm^{3(n-1)} s^{-1}">

This can be easily adapted for other common units such as molecules cm<sup>-3</sup> s<sup>-1</sup>.

For a first order reaction, n=1:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle units = \frac{mol dm^{-3} s^{-1}}{mol dm^{-3}} = s^{-1}">
 
**You cannot compare rate coefficients with different units just as you cannot compare a length and an area.**

### Rate Constants and Equilibrium Constants

We can relate the rate coefficients of a reversible reaction and the equilibrium constant. 
Consider the reversible reaction:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle X \underset{k_{-1}}{\stackrel{k_1}{\rightleftharpoons}} Y">

The rate equations for the forward and reverse reactions are:

forward: <img src="https://render.githubusercontent.com/render/math?math=\displaystyle rate = k_1[X]">

reverse:  <img src="https://render.githubusercontent.com/render/math?math=\displaystyle rate = k_{-1}[Y]">
 
We can also consider the equilibrium constant:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle K = \frac{[Y]}{[X]}">
 
By definition, at equilibrium the rates of forward and reverse reactions are equal:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle k_1[X] = k_{-1}[Y]">

Rearrangement yields:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{[Y]}{[X]} = \frac{[k_1]}{[k_{-1}]} = K">
 
Therefore the equilibrium constant is equal to ratio of rate constants for the forward and reverse reactions for a single step reaction. 


