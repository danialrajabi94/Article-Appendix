# Appendix A. Augmented epsilon constraint 

The linear form of a multi-objective problem converted to a single objective one using augmented epsilon constraint is as follows:

<p align="center">
  <img src="https://github.com/danialrajabi94/Article-Appendix/blob/main/images/equation_A1.PNG">
</p>

Where dir in maximization and minimization problems considers +1 and -1, respectively. The following steps describe the proposed approach [1], [2]:
1.Constructing payoff table: in this step the range of each objective function is determined with the Lexicographic method. In this method, all objective functions are ranked according to their priority and optimization starts with the most important objective function. After optimizing the first objective function, if the solution is an optimal unique solution then the optimization process is finished otherwise, the next objective function should be optimized. The process will continue until the problem completely solves.

2.Calculation the lower and upper bound of objective function: in this step the lower and upper bound and the range of each of objective functions are determined according to (A.2)-(A.4).

<p align="center">
  <img src="https://github.com/danialrajabi94/Article-Appendix/blob/main/images/equation_A2_4.PNG">
</p>

3.Dividing the objective function range: In this step the range of each objective function is divided into the q_n number of intervals to calculate the ![equation](https://latex.codecogs.com/svg.latex?e_%7B%28n%2C%20k_%7Bn%7D%29%7D%20) as follows:

<p align="center">
  <img src="https://github.com/danialrajabi94/Article-Appendix/blob/main/images/equation_A5.PNG">
</p>

4.Solve the problem for different iterations: finally the problem is solve for different ![equation](https://latex.codecogs.com/svg.latex?e_%7B%28n%2C%20k_%7Bn%7D%29%7D%20) and ![equation](https://latex.codecogs.com/svg.latex?k_%7Bn%7D) according to Fig. A.

<p align="center">
  <img src="https://github.com/danialrajabi94/Article-Appendix/blob/main/images/Fig_A1.png" width="80%" height="1000px">
</p>
<p align="center">
  Fig. A.1. The proposed augmented epsilon constraint algorithm
</p>


# Appendix B. Test case

MG test system data are presented as Tables B.1-B.4 and Figs B.1-B.2 as follows.


<p align="center">
  Table B.1. Micro turbines data  
</p>
<p align="center">
  <img src="https://github.com/danialrajabi94/Article-Appendix/blob/main/images/Table_B1.png">
</p>

<p align="center">
  Table B.2. Wind turbine data
</p>
<p align="center">
  <img src="https://github.com/danialrajabi94/Article-Appendix/blob/main/images/Table_B2.png">
</p>


<p align="center">
  Table B.3. Forecasted wind velocity
</p>
<p align="center">
  <img src="https://github.com/danialrajabi94/Article-Appendix/blob/main/images/Table_B3.png">
</p>


<p align="center">
  Table B.4. Energy storage system data 
</p>
<p align="center">
  <img src="https://github.com/danialrajabi94/Article-Appendix/blob/main/images/Table_B4.png">
</p>


<p align="center">
  <img src="https://github.com/danialrajabi94/Article-Appendix/blob/main/images/Fig_B1.png">
</p>
<p align="center">
  Fig. B.1. Forecasted local loads for a  24 hours horizon
</p>

<p align="center">
  <img src="https://github.com/danialrajabi94/Article-Appendix/blob/main/images/Fig_B2.png">
</p>
<p align="center">
  Fig. B.2. Forecasted retail power marker clearing price for a 24 hours horizon
</p>


# Refrences
[1] G. Mavrotas, "Effective implementation of the ε-constraint method in multi-objective mathematical programming problems," Applied mathematics and computation, vol. 213, pp. 455-465, 2009.
[2] A. Soroudi, R. Caire, N. Hadjsaid, and M. Ehsan, "Probabilistic dynamic multi-objective model for renewable and non-renewable distributed generation planning," IET generation, transmission & distribution, vol. 5, pp. 1173-1182, 2011.
