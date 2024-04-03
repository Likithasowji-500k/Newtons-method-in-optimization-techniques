
# Newton's Method in Optimization Techniques

## Introduction
This Python script implements Newton's Method for finding the minimum of a given function. Newton's Method is an optimization technique used to iteratively find the roots of a function, which can be applied to optimization problems by finding the critical points of the function.

## First Derivative
The first derivative of the function (f'(x)) is defined as follows:
```bash
def f1(x):
    return 2 * x - (54 / x**2)
```

## Second Derivative
The second derivative of the function (f''(x)) is defined as follows:
```bash
def f2(x):
    return 2 + (108 / x**3)
```

## Usage
- Run the script newtons_method.py.
- Enter the initial guess a for the minimum.
- The script will perform Newton's Method iteratively until convergence, or until a maximum number of iterations is reached.

## Input
The input parameter required by the script is:
- a: The initial guess for the minimum.

  ## Output
The script will output the iteration number, the current value of x, the first derivative f1(x), and the second derivative f2(x) at each iteration. It will also display the final value of x where the minimum is found.

![newtons_method output](https://github.com/Likithasowji-500k/Newtons-method-in-optimization-techniques/assets/121708442/41ae1a75-fcfe-4b33-adef-1ecd9b4717fa)

