# Optimizing Regression Models with Coordinate Descent

This folder contains two files: an R file with the code and a PDF report detailing the methodology and results. The report and the R file can be viewed above in the repository or by clicking here: [PDF report](https://github.com/StephenACodes/myportfolio.github.io/blob/main/Project4/Coordinate%20Descent%20Algorithm.pdf) , [R file](https://github.com/StephenACodes/myportfolio.github.io/blob/main/Project4/Coordinate%20Descent%20Algorithm.R). 

**Summary**: This project implements and evaluates the coordinate descent algorithm for solving Lasso and Elastic Net penalized regression problems. Using simulated datasets, we compare their performance in terms of predictive accuracy (mean-squared error) and variable selection (non-zero coefficients) across various scenarios: n>p (more observations than predictors), p>n (high-dimensional data), and settings with uncorrelated/correlated predictors and varying noise levels (𝜎). The algorithms are tuned via 12-fold cross-validation, and results are analyzed over 50 simulations with default parameters. The code provides a practical demonstration of these techniques, making it a useful resource for learning about regularization methods in regression.

### Tools Used
- **R Programming Language** for executing R codes and creating visualisations.

# Conclusion 

Our findings show that Elastic Net consistently outperforms Lasso in predictive accuracy and variable selection across most scenarios. In the n>p case, Elastic Net achieves lower mean MSE and selects more non-zero coefficients, indicating better feature retention. In high-dimensional p>n settings, Elastic Net remains superior, especially with limited data, while converging toward Lasso when predictor counts are low. Additional simulations reveal that Elastic Net’s advantage grows with higher noise (σ) and correlated predictors, highlighting its robustness. This project underscores Elastic Net’s versatility for regression tasks, offering a balance between sparsity and stability.

## Feedback is welcome. Connect with me:

- Linkedin: https://www.linkedin.com/in/ayush-stephen-toppo-aa29b8201
- Email: ayushstephen2002@gmail.com
