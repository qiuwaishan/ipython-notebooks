
## Non-Recursive Permutation Algorithm

Contained in this repo is an implentation of a method for generating permutations of 
the elements of a list of length N. 

## Usage

Usage for the algorithm is extremely simple, as it is just a single function. 

Import the package, choose N, and run the function:

```python
from permutation import permutation

N = 3
permutation.permutation(N)
```

        [[0, 1, 2],
         [0, 2, 1],
         [1, 0, 2], 
         [1, 2, 0], 
         [2, 0, 1], 
         [2, 1, 0]]


Here is a visualization of the algorithm permutating a list of 3 (each color represents a digit):

<img src="https://github.com/joelcarlson/ipython-notebooks/blob/master/Permutation_Implementation/figs/perms_three.gif" />

A list of 4:

<img src="https://github.com/joelcarlson/ipython-notebooks/blob/master/Permutation_Implementation/figs/perms_four.gif" />

Finally, a very cluttered list of 5:

<img src="https://github.com/joelcarlson/ipython-notebooks/blob/master/Permutation_Implementation/figs/perms_five.gif" />