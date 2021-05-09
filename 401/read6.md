# Random :

we have various random functions in python , to use them we should


***import random***
- Random integer :
```
import random
print random.randint(0, 5) //random integer between 0-100

random.random() * 100  #random integer between 0-100

```
 ***choice***

```
import random
myList = [2, 109, False, 10, "Lorem", 482, "Ipsum"]
random.choice(myList
```


***Shuffle***
```
from random import shuffle
x = [[i] for i in range(10)]
shuffle(x)
Output:
# print x  gives  [[9], [2], [7], [0], [4], [5], [3], [1], [8], [6]]
# of course your results will vary

```



# Risk Analysis in Software Testing and how to perform it?


>Why use Risk Analysis?
In any software, using risk analysis at the beginning of a project highlights the potential problem areas. After knowing about the risk areas, it helps the developers and managers to mitigate the risks. When a test plan has been created, risks involved in testing the product are to be taken into consideration along with the possibility of the damage they may cause to your software along with solutions.



## Common Risks :

- Use of new hardware
- Use of new technology
- Use of new automation tool
- The sequence of code
- Availability of test resources for the application


## what are these risk magnitude indicators?


- High: means the effect of the risk would be very high and non-tolerable. The company might face loss.

- Medium: it is tolerable but not desirable. The company may suffer financially but there is a limited risk.

- Low: it is tolerable. There lies little or no external exposure or no financial loss.



# three steps to perform risk analysis:

- Searching the risk

- Analyzing the impact of each individual risk

- Measures for the risk identified



# Big O

what is Big O ?
is a concept in cs used to descibe the performance or complexity of an algorithm .
usually it also describes th required time or the space used in disk or memory.

## O(N)
a linear growth algorithm.

 if you can create an algorithm to solve the problem in O(1), you are probably at your best
## O(N²)
square propotional slgorithm

## O(2^N)

exponential growth algorithm

For example, O(n⁵) is more complex than O(n⁴). Due to the simplicity of it, we actually went over quite many examples of polynomials in the previous sections.
