# Regression-Model
In this project a polynomial regression model(Y = a<sup> 0</sup> + a1X + a2X<sup> 2</sup> + . . . + adX<sup> d</sup>) was implemented and the built model was evaluated based on following parameters: <br />
* model complexity:d ∈ {0, 1, 2, . . . , 20} 
* sample size: N ∈ {2, 5, 10, 20, 50, 100, 200}
* standard deviation: σ ∈ {0.01, 0.1, 1}
          

                  
          

### getData function:
In this function, for a given value of N and σ<sup> 2</sup>, the dataset with a set of N (X, Y) (denoted as {(xi, yi) : i = 1, 2, . . . N}) pairs was generated based on the following formula: <br />
Y = cos(2πX) + Z <br />
Where X values are drawn uniformly at random from (0, 1) and Z is a zero mean Gaussian random variable with variance σ<sup> 2</sup>. <br />

### PolyReg function:



