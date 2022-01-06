
# Cost Sensitive Logistic Regression

A Python program that loads numerical data from the unbalanced dataset provided, and gives us the Saving's score(which is defined as the cost of the optimized algorithm versus the cost of the naive algorithm)

#### Saving's score = 1 - (cost loss using optimized function / cost loss using naive function)

### Cost Function Used:

![Output Screenshot](https://github.com/AyanPahari/Cost-Sensitive-Logistic-Regression/blob/master/cost_function.JPG)

- Since the cost function used here is non-convex we will be using genetic algorithms to get the optimal parameters.

#### Image taken from "Alejandro CORREA BAHNSEN" Research Paper
## Output

#### Using Naive Logistic Regression we are getting a Saving's Score between 0.48-0.49

#### Using the cost-sensitive cost function we are getting a Saving's Score between 0.82-0.85 which is a huge improvement

![Output Screenshot](https://github.com/AyanPahari/Cost-Sensitive-Logistic-Regression/blob/master/output.JPG)

