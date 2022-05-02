# Sequential Reactions

We are now in a position to consider more complicated chemical systems. Few reactions consist of a single step with the vast majority proceeding via many steps with intermediates which are produced and then destroyed. The best way to describe these mathematically is using the differential equation form.

### Chapman Cycle
Consider the following set of reactions called the Chapman Cycle. This occurs in the high atmosphere (~30 - 50 km in altitude) with associated rate coefficients in parentheses. (M stands for any molecule which can remove the excess energy of the collision, typically N<sub>2</sub> or O<sub>2</sub>.) Ozone, O<sub>3</sub>, plays an important role in absorbing high energy UV radiation which would otherwise cause damage to living tissue should it reach the Earth's surface. The reaction scheme is as follows:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle O_2 \rightarrow O %2B\ O   (k_1)">

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle O_3 \rightarrow O %2B\ O_2  (k_2)">

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle O %2B\ O_2 %2B\ M \rightarrow O_3 %2B\ M   (k_3)">

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle  O %2B\ O_3 \rightarrow O_2 %2B\ O_2 (k_4)">


A key progression from high school is writing differential equations describing the rate of change of different species. 
Let's consider all the reactions producing or destroying O<sub>2</sub> - each will contribute to the overall rate of change of O<sub>2</sub> and, as each of the reactions above is a single step, it is straightforward to write the rate of each:

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[O_2]}{dt} = -k_1[O_2] %2B\ k_2[O_3] - k_3[O][O_2][M] %2B\ 2k_4[O][O_3] ">


Note that a factor of 2 is included for the final reaction as it produces 2 molecules of O<sub>2</sub>. The same approach is taken for O<sub>3</sub> below: 

<img src="https://render.githubusercontent.com/render/math?math=\displaystyle \frac{d[O_3]}{dt} = - k_2[O_3] %2B\ k_3[O][O_2][M] - k_4[O][O_3] ">

