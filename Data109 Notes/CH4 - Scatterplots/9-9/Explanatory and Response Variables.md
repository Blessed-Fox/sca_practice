Explanatory Variables are the x-axis.
Response variables are the y-axis. They are a response to the explanatory variable. 

Both kinds of these variables must be quantitative

Explanatory => X-value
Response => y-value

individual data points => (x,y)

in R, you can do this with:
```
class_data => read.csv(class_data)
x <- class_data$number_of_suitemates
y <- class_data#number_years_college
plot(x, y)
```
You can generate the line of Best Fit (Least Squares Regression Line) with
```
 abline (y ~ x)
```