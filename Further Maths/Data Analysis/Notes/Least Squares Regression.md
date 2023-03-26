# Least Squares Regression



• Least Squares Regression is a method of linear regression used to find the line of best fit for a given set of data points.

• The least squares regression line is the line that minimizes the sum of the squared differences between the observed values and the predicted values.

• The equation of the least squares regression line is given by:
$$ \hat{y} = \beta_0 + \beta_1x $$

• The parameters $\beta_0$ and $\beta_1$ are calculated by minimizing the sum of squared errors (SSE):
$$ SSE = \sum_{i=1}^n (y_i - \hat{y_i})^2 $$

• The parameters $\beta_0$ and $\beta_1$ can be calculated using the following formulas:
$$ \beta_1 = \frac{\sum_{i=1}^n (x_i - \overline{x})(y_i - \overline{y})}{\sum_{i=1}^n (x_i - \overline{x})^2} $$
$$ \beta_0 = \overline{y} - \beta_1 \overline{x} $$
