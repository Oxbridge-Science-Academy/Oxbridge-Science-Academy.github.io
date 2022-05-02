# Order of Reaction

### Single Steps

You will probably have seen the rate of reactants written in terms of the concentrations of reactants rather than a differential equation. This is sometimes called the "power law" form because the rate is specified in terms of powers of reactant concentrations. For example, if molecules X and Y react in a single step to form Z via the equation:
 
 <img src="https://render.githubusercontent.com/render/math?math=\displaystyle X %2B\ Y \rightarrow Z">

the rate of reaction can be expressed as:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle rate=k[X][Y]">

where <img src="https://render.githubusercontent.com/render/math?math=\displaystyle k"> is the rate constant.
 
Indeed, for any single step of a reaction (also called an elementary step), the rate equation can be expressed as the product of the concentration of the reactants involved, each raised to the power equaling their stoichiometric coefficient. Furthermore, the order of a reaction with respect to a particular reactant is equal to the power in the rate equation. In the case above, the reaction is first order with respect to both X and Y. The overall order of the reaction is the sum of all the powers. 
 
However, this method must be treated with great caution and can only be used if it is known that the reactants react in a single step. For example, with the reaction:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle A %2B\ 2B %2B\ C \rightarrow D %2B\ E">

we cannot say for certain that the rate equation will be:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle rate=k[A][B]^2[C]">

as we do not know if the reaction happens in a single step. In fact, the probability of 3 or more molecules colliding at the same time with the correct orientation and sufficient energy is negligible and so very few single steps ever involve more than 2 reactants. 

### Multiple Steps

If a reaction consists of multiple elementary steps, we need to consider each elemntary step in turn and deduce the rate determining step (RDS). The RDS is the slowest step in the reaction. **Only species which appear in or before the RDS will affect the rate of reaction.** 

Consider the following single step reactions for which we can write individual rate equations:

Step 1: <img src="https://render.githubusercontent.com/render/math?math=\displaystyle 2A \rightarrow B %2B\ C \Rightarrow rate=k_1[A]^2">


Step 2: <img src="https://render.githubusercontent.com/render/math?math=\displaystyle B %2B\ D \rightarrow E \Rightarrow rate=k_2[B][D]">

Step 3: <img src="https://render.githubusercontent.com/render/math?math=\displaystyle E %2B\ F \rightarrow G \Rightarrow rate=k_3[E][F]">


Where <img src="https://render.githubusercontent.com/render/math?math=\displaystyle k_1, k_2, k_3"> are the rate coefficients for the respective steps. 

The overall reaction is: <img src="https://render.githubusercontent.com/render/math?math=\displaystyle 2A %2B\ D %2B\ F \rightarrow C %2B\ G">. Note that B and E are not featured since they are produced and then destroyed in adjacent steps. 
 
The key question that follows is "how can the RDS of this set of reactions be determined"? Without it we cannot determine the rate equation. 

### Determining the RDS 
One method is to run the reaction multiple times, varying the concentration of one species at a time to see how the rate of reaction is affected. This can be experimentally challenging (discussed later) and would be best done in this case by examining the rate of production of species G.

If step 1 is the RDS, only changes in <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [A]"> will affect the rate.

If step 2 is the RDS, changes to <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [A]"> and <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [D]"> will affect the rate of reaction. 

If step 3 is the RDS, changes to <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [A]">, <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [D]"> and <img src="https://render.githubusercontent.com/render/math?math=\displaystyle [F]"> will all affect the rate of reaction.


However, changing [X] may lead to Y being used up faster, in turn affecting the reaction and making it harder to attribute any change in the rate solely to the change in [X], posing a problem. There are two options to resolve this issue, both with their limitations.

### Measuring the Initial Rate
This method involves measuring  how the initial rate of reaction changes when [X] is varied. This works because in this very short period of time over which the initial rate is measured, the change in [Y] will be too small to affect the rate. The main limitation is the challenge in getting enough data points in a short space of time to be able to calculate an accurate value for the initial rate. 

### Excess Concentration 

This method involes keeping Y in excess, in other words [Y]<sub>initial</sub> >> [X]<sub>initial</sub> so that even when all of X has reacted, the change in [Y] will be negligible and have essentially no effect on the rate of reaction. For example, if we start with a concentration of Y 100 times that of X, then when all of X has reacted, [Y] will have decreased by only 1%.

One issue with this method is the large value of [Y] can make the reaction very fast, leading to [X] dropping very quickly and making measurement challenging. Fast reactions can also cause safety issues (a slow burn vs. an explosion). A further issue is the potential for competing reactions. For example, in addition to reacting with X, Y may also be able to react with itself (called a "self-reaction"). The possible reactions are therefore: 

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle X %2B\ Y \rightarrow Z">

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle Y %2B\ Y \rightarrow A">


Having large concentrations of Y would mean the reaction <img src="https://render.githubusercontent.com/render/math?math=Y %2B\ Y \rightarrow A"> would be fast and most of Y would be lost via self-reaction. The reaction of  <img src="https://render.githubusercontent.com/render/math?math=X %2B\ Y \rightarrow Z"> would be hard to observe and again determining the order would be hindered by the change in [Y]. 

### Pseudo First Order Kinetics 

Using the excess concentration method leads to the concept of pseduo first order kinetics. In the example above, as Y is in excess its concentration will change negigibly with time. Therefore we can rewrite the rate equation as:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle rate=k[X][Y] \approx k_{eff}[X]">

Where <img src="https://render.githubusercontent.com/render/math?math=k_{eff}"> is the "effective" or pseudo first order rate constant. <img src="https://render.githubusercontent.com/render/math?math=k_{eff}=k[Y]"> and we can only do this as [Y] doesn't change with time. 

Thus we have changed a second order reaction to a first order reaction. Now we can determine the order of the reaction with respct to X easily - if we double [X] and the rate doubles, it is first order; if the rate increases by a factor of 4, it is second order. 


