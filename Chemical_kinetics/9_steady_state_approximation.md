# Steady State Approximation

We can extend the idea of sequential reactions and the analysis discussed in the previous section to a very common example - the steady state approximation.

Consider a reaction consisting of two steps:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle A \rightarrow B \rightarrow C ">

Where the first step has rate constant <img src="https://render.githubusercontent.com/render/math?math=\displaystyle k_1"> and the second step rate constant <img src="https://render.githubusercontent.com/render/math?math=\displaystyle k_2">. 

While this may appear strange, such a situation is common in chemistry. A could represent an unstable species which undergoes a unimolecular reaction to form an intermediate B which then decays into stable product C.
We can write differential equations for the three species:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[A]}{dt} = -k_1[A] ">

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[B]}{dt} = k_1[A] - k_2[B] ">


<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[C]}{dt} =  k_2[B] ">

You should ensure you understand how these differential equation have been reached - see Sequential Reactions if you are not sure. 


Solving this system is not impossible but if we included further reactions such as reverse reactions (<img src="https://render.githubusercontent.com/render/math?math=\displaystyle B \rightarrow A"> and <img src="https://render.githubusercontent.com/render/math?math=\displaystyle C \rightarrow B">), matters swiftly become very complicated. 

However, some simplifications can be made in a particular circumstance, specifically when: 

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle k_2 \gg k_1"> 
 
In this case, species B is produced much more slowly than it is destroyed. In other words, as soon as it is produced it reacts further and so its concentration will never build up. Furthermore, the rate of change of B is also negligible as it never exceeds miniscule concentrations. This means we can write:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[B]}{dt} = 0"> 

Equating this to the expression we derived earlier:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[B]}{dt} = 0 = k_1[A] - k_2[B]"> 

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \Rightarrow k_1[A] = k_2[B]"> 

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \Rightarrow [B]_{ss} = \frac{k_1[A]}{k_2}"> 

Where we have used the subscript "ss" to indicate this the "steady state" concentration of B

Deriving explicit expressions for [A], [B] & [C]is left for the student in the questions. 

Using the steady state concentraion of B, we can derive an alternative expression for the rate of production of species C:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[C]}{dt} =  k_2[B] = k_1[A]">

Therefore we see that the production of C mirrors the loss of initial reactant A.

This is known as the Steady State Approximation and is used to simplify the kinetics of complex schemes. It is only valid when the rate of loss of a species (in this case B) is much faster than its production. The energy plot below shows a situation where steady state is applicable. A corresponds to "reactants", B the "intermediate" and C the "products". This plot is also more rigorous and includes the reverse reaction <img src="https://render.githubusercontent.com/render/math?math=\displaystyle B \rightarrow A "> with rate coefficient<img src="https://render.githubusercontent.com/render/math?math=\displaystyle k_{-1}">. 

![alt text] (https://github.com/Oxbridge-Science-Academy/Figures/blob/master/Chemical_Kinetics/Steady%20State%20Energy%20Plot.png)

### Non-steady state cases
It is also worth considering the situation where steady state is not applicable. Here, these would the cases where: 
<img src="https://render.githubusercontent.com/render/math?math=\displaystyle k_1 ~ k_2"> or <img src="https://render.githubusercontent.com/render/math?math=\displaystyle k_1 > k_2">

Note that "~" means "comparable to" and in the physical sciences is typically taken to be within a factor of 5 or 10.

In these cases, B is formed at least as quickly as it is destroyed and potentially more quickly. Therefore, [B] will be non-negligible and, more importantly,:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[B]}{dt} \neq 0">

A situation where steady state is not applicable is shown below. The large activation barrier the intermediate must overcome to produce the final product means it will not decay away rapidly. 
 
 ![alt text](https://github.com/Oxbridge-Science-Academy/Figures/blob/master/Chemical_Kinetics/Non-steady%20State%20Energy%20Plot.png) 


### Validity of Steady State 

The steady state approximation fails to reproduce the actual concentration of at [B] at the start of the reaction as it predicts a non-zero value whereas in reality it will be zero because A has not reacted yet. 
Shown below are the actual (upper) and steady state (lower) concentration profiles for the <img src="https://render.githubusercontent.com/render/math?math=\displaystyle A \rightarrow B \rightarrow C"> system when
<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{k_2}{k_1} = 10">.

The "actual concentration" profile are calculated by solving the differential equations stated at the top of the page. 

![alt text](https://github.com/Oxbridge-Science-Academy/Figures/blob/master/Chemical_Kinetics/Actual%20Concentrations.png)

![alt text](https://github.com/Oxbridge-Science-Academy/Figures/blob/master/Chemical_Kinetics/Steady%20State%20Concentrations.png)
 
 
We see that the steady state approximation does not affect [A]. The profile of [C] increases slightly more slowly in the "actual" case, reflecting the lag which is caused by the initial formation of [B]. However, for the most part [C] is unchanged.

The profile of [B] shows the biggest difference; it is non-zero in the steady state case but in the more realistic "actual" case it rises briefly as its production dominates before its destruction dominates and it declines. It is a valid point that [B] does change with time in both but the speed of change is small relative to changes in [A] and [C], justifying the approximation that:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[B]}{dt} = 0">
 
We can use graphical means to investigate how the ratio of <img src="https://render.githubusercontent.com/render/math?math=\displaystyle k_2"> to <img src="https://render.githubusercontent.com/render/math?math=\displaystyle k_1">
 affects the validity of the steady state approximation. Shown below are the concentration profiles of B using the actual and steady calculations. When the ratio is small, the two profiles compare poorly but as it increases, the match becomes much better, indicating that the steady state approximation is more acceptable.  

![alt text](https://github.com/Oxbridge-Science-Academy/Figures/blob/master/Chemical_Kinetics/Steady%20state%20varying%20ratio.png)
