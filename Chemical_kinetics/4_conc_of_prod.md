# Concentrations of Products

The previous section looked at how we can derive expressions for the variation of a reactant with time for first and second order reactions. However, we are often interested in the time-dependence of product formation a well. For example, many drugs are delivered to the body not in their active form but as a precursor which will react in the body, sometimes multiple times, to eventually form the molecule which is biologically active and performs the specific therapeutic task. 
It is relatively straightforward to express the concentration of product as a function of time in a reaction of simple stoichiometry. The key step is to remember that mass is conserved. 
 
### First Order Reactions
Consider again the reaction <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X \rightarrow Y">. The change in denoted  <img src="https://render.githubusercontent.com/render/math?math=[X]">(denoted  <img src="https://render.githubusercontent.com/render/math?math=\Delta [X]">) will be equal to the (negative) change in denoted  <img src="https://render.githubusercontent.com/render/math?math=\displaystyle \Delta [Y]">. This can be expressed as:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \Delta [X] = - \Delta [Y]">

The mass balance equation can as be expressed as:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X]_0 = [X] %2B\ [Y]">

Where <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X]_0"> is the initial reactant concentration. 

The reaction <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X \rightarrow Y"> is first order in <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X"> and so the <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X]"> can be written as: 

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X] = [X]_0e^{-kt}">

Substituting this into the mass balance equation yields an equation for the product concentration <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [Y]"> as a function of time:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X]_0=[X]_0e^{-kt} %2B\ Y ">

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \Rightarrow Y = [X]_0 \left(1-e^{-kt} \right) ">

Again it is  worth considering if an equation makes sense under certain conditions (a so-called "sanity check") - this is good practice in all areas of the science. 

At the start of the reaction <img src="https://render.githubusercontent.com/render/math?math=\displaystyle t=0">, there will be no product, i.e. <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [Y]=0 ">.

Substituting <img src="https://render.githubusercontent.com/render/math?math=\displaystyle t=0"> into the expression:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle Y = [X]_0 \left(1-e^{0} \right) = [X]_0(1-1) = 0 ">

As the reaction time tends <img src="https://render.githubusercontent.com/render/math?math=\displaystyle \rightarrow \infinity">, there will be only product and no reactant. The product concentration will be equal to the initial reactant concentration,  <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [X]_0">.
Substituting <img src="https://render.githubusercontent.com/render/math?math=\displaystyle t=\infinity ">into the expression for <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [Y]">:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle [Y]=[X]_0\left(1-e^{-\infinity}\right) = [X]_0">

Thus, the equation of product concentration as a function of time meets these two conditions. It is important to note that performing such sanity checks does not mean the expression is definitely correct; rather is a quick way of spotting if is wrong.

The expression for <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [Y]"> is plotted below. We can see how the product concentration increases rapidly at first, coinciding with the region of most rapidly reactant loss, before plateauing and tending to the concentration of the initial reactant concentration.
Incidentally, the same mathematics is observed during the charging of a capacitor and will familiar to those of you who studied A Level (or equivalent) Physics. 

![alt text](https://github.com/Oxbridge-Science-Academy/Figures/blob/master/Chemical_Kinetics/Product%201st%20order.png)

Questions x and y focus on calculating the concentration of products. 

### Other Order Reactions

Below are the shown the product concentration profiles for zero, 1st and 2nd order reactions. Note that the product concentartions mirror the reactant concentartion profile shown earlier. 

![alt text](https://github.com/Oxbridge-Science-Academy/Figures/blob/master/Chemical_Kinetics/Product%20Profiles.png)
