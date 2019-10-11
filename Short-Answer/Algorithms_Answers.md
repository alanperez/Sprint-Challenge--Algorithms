#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n)

b) n^2

c)O(n)

## Exercise II

```
Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.
```

start dropping the first egg on the first floor
if it doesn't break
move on to the next floor
else
return floor it broke on
