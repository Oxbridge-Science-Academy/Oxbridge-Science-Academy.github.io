# Differential Equations

 A key progression from high school to university is thinking about rates with a more quantitative mindset. This is done by linking the two different rate equations – the differential equation and the power law equation. 

Consider the simple reaction <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X \rightarrow Y">

We can express the rate of reaction as:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle rate=k[X]">

or 

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle rate=-\frac{d[X]}{dt}">

Equating these expression, we can write:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[X]}{dt} = -k[X]">

Solving this differential equations allows us to describe how the concentration of a particular reactant, in this case X, varies over time. This approach can also be used for intermediates and final products and is important in many fields. 
In pharmacology it is necessary to know how quickly a drug is destroyed in the body to calculate the required dosage while the field of atmospheric chemistry is centred around the production and destruction of chemical species in the atmosphere. 
We can also use knowledge of how a concentration should vary over time to calculate, from experimental data, the order of a reaction with respect to a particular species.

## 1st Order Reactions 

Consider the reaction <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X \rightarrow Y">  which is 1st order with respect to <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X">

As discussed above we can write:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[X]}{dt} = -k[X]">

Consider the resulting differential equation - we can solve this using the method of separation of variables. (See Integration course if you have not encountered this method before) 

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \int \frac{1}{[X]} d[X]  = -k \int dt">

The integral can be treated as indefinite for now, resulting in:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \ln [X]  = -kt %2B\ c">

Where we have combined the two constants of integration into on constant,<img src="https://render.githubusercontent.com/render/math?math=\displaystyle c">. 

To assign a value to this constant, we consider the boundary conditions. At the start of the reaction <img src="https://render.githubusercontent.com/render/math?math=\displaystyle t=0"> and the concentration of <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X]">
 was some initial value <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X]_0">.

Substituting these values into the equation directly above, we arrive at:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \ln [X]  = -kt %2B\ \ln [X]_0">

Removing the natural logarithm by raising <img src="https://render.githubusercontent.com/render/math?math=\displaystyle e">
to the power of each side results in:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X] = [X]_0 e^{-kt}">

Thus we arrive at the conclusion that a species which is destroyed in a first order reaction will have its concentration decay exponentially with time. This is precisely the same as the mathematics behind radioactive decay of unstable nuclei since the act of decay is a first order process. 

Exponential decay has several important implications including the fact that concentration of reactant is predicted never to quite reach zero and secondly the half life of the species is constant (not the case for other orders of reaction). 

The plot below shows the concentration profile for a first order reactant with a half life of ~1.5 s. The dashed red lines show visually that the half life is constant. 

![alt text](https://github.com/Oxbridge-Science-Academy/Figures/blob/master/Chemical_Kinetics/first%20order%20plot.png)

## 2nd Order Reactions

Consider the reaction <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X %2B\ X \rightarrow Y"> 
which is 2nd order with respect to X and has second order rate constant  <img src="https://render.githubusercontent.com/render/math?math=\displaystyle k_{2nd}">. We can relate the power law and differential forms:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle rate = -\frac{d[X]}{dt} = k_{2nd}[X]^2">

Consider the differential equation - again, we can solve this using the method of separation of variables. (See Integration course if you have not encountered this method before) 

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{1}{[X]^2}d[X] = -2 k_{2nd}dt">

Integrating both sides indefinitely:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \int \frac{1}{[X]^2}d[X] = -2 k_{2nd} \int dt">

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle -\frac{1}{[X]} = -2 k_{2nd}t %2B\ c ">

Again, to assign a value to the constant of integration, we consider the boundary conditions. At the start of the reaction <img src="https://render.githubusercontent.com/render/math?math=\displaystyle t=0"> and <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X] = [X]_0">.
Substituting these values into the equation directly above, we arrive at:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle -\frac{1}{[X]} = -2 k_{2nd}t - \frac{1}{[X]_0}">

This can be rearranged to give:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X] = \frac{[X]_0}{kt[X]_0 %2B\ 1}">

It is helpful to consider whether this final expression makes sense. At the start when <img src="https://render.githubusercontent.com/render/math?math=\displaystyle t=0">, the expression predicts <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X] = [X]_0"> as required and as <img src="https://render.githubusercontent.com/render/math?math=\displaystyle t \rightarrow \infinity">, the denominator also <img src="https://render.githubusercontent.com/render/math?math=\displaystyle \rightarrow \infinity"> and <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X]_0 \rightarrow 0"> as required. 

### Zero Order Reactions

Consider a reaction <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X %2B\ Y \rightarrow Z">. While this may look first order in both <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X"> and <img src="https://render.githubusercontent.com/render/math?math=\displaystyle Y">, in this particular let's say that there are two steps involved. The first involves <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X"> decaying into another product, <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X^*"> before <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X^*"> reacts with <img src="https://render.githubusercontent.com/render/math?math=\displaystyle Y">:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle 1. \\ X \rightarrow X^*">

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle 2. \\ X^* %2B\ Y \rightarrow Z">

In this case, the first step is the RDS so the reaction is zero order with respect to <img src="https://render.githubusercontent.com/render/math?math=\displaystyle Y">; in other words the concentration of <img src="https://render.githubusercontent.com/render/math?math=\displaystyle Y"> has no bearing on the rate of reaction. 

We can therefore write <img src="https://render.githubusercontent.com/render/math?math=\displaystyle -\frac{d[Y]}{dt} = k"> where k is the rate constant from step 2. In the exercises the student is asked to show that the cocnetartion of Y decreases linearly .

Below is shown concentration profiles for zero, 1st and 2nd order reactions. 

![alt text](https://github.com/Oxbridge-Science-Academy/Figures/blob/master/Chemical_Kinetics/Reactant%20Profiles.png)
