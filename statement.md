# How to Program Compound Interest in Python

Compound interest is the interest that is calculated on the initial principal & contains all of the accumulated interest from previous interval on a deposit or loan.
Here is the python programming for calculating Compound Interest.

```python runnable
#Given Values
def compound_interest(principle, rate, time):
    #Code to calculate compound interest
    CIn = principle *(pow((1+rate/100), time))
    print("Compound interest is",CIn)
# Code for Drive
compound_interest(1000,10.25,6)
```

