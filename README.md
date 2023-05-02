# Regression-Model
In this project a polynomial regression model (Y = a<sup> 0</sup> + a<sub> 1</sub>X + a<sub> 2</sub>X<sup> 2</sup> + . . . + a<sub> d</sub>X<sup> d</sup>) was implemented and the built model was evaluated based on following parameters: <br />
* model complexity: d ∈ {0, 1, 2, . . . , 20} 
* sample size: N ∈ {2, 5, 10, 20, 50, 100, 200}
* standard deviation: σ ∈ {0.01, 0.1, 1}
            
### getData function:
In this function, for a given value of N and σ<sup> 2</sup>, the dataset with a set of N (X, Y) (denoted as {(xi, yi) : i = 1, 2, . . . N}) pairs is generated based on the following formula: <br />
Y = cos(2πX) + Z <br />
Where X values are drawn uniformly at random from (0, 1) and Z is a zero mean Gaussian random variable with variance σ<sup> 2</sup>. <br />

### PolyReg function:
In this function, the input points are converted to a matrix with N × d that column i represents the X<sup> i</sup>.

### MSE function:
The mean square error (MSE) for a given dataset is calculated.<br />

In the GD, SGD, and Mini_BSGD functions, gradient descent, stochastic gradient descent, and mini-batch gradient, respectively are implemented manually. No packages was used in this implementation.


