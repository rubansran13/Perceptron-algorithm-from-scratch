# Perceptron-algorithm-from-scratch

Perceptron algorithm is developed from scratch (here it is employed on linearly separable data points in two dimension but could be extended making appropriate dimension extensions). First N (here 100) number of points were generated from a uniform distribution over [-1,1] and mapped onto {-1,1} using target function which is generated using the same uniform distribution to generate two points.

Estimation of number of iterations required for convergence of perceptron estimator is also done. For 100 points, perceptron took 105 iterations averaged over 100 runs.

Preview of Perceptron working:

![Alt Text](Target_Function-1.png?raw=true "Perceptron estimation of Target Function(1)")

![Alt Text](Comaprison_between_target_function_and_perceptron_estimator-1.png?raw=true "Perceptron estimation of Target Function(1)")

![Alt Text](Target_Function-2.png?raw=true "Target Function(2)")

![Alt Text](Comaprison_between_target_function_and_perceptron_estimator-2.png?raw=true "Perceptron estimation of Target Function(2)")

Libraries Used"
NumPy- Version(1.14.5)
MatPlotLib- Version(2.2.2)
