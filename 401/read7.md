# Scope 

Why we have to know the scope ?

>Several programming languages take advantage of scope for avoiding name collisions and unpredictable behaviors.




# LEGB: LOCAL , ENCLOSING ,GLOBAL, BUILTIN :

***Global scope:*** The names that you define in this scope are available to all your code.

***Local scope:*** The names that you define in this scope are only available or visible to the code within the scope.

***Enclosing (or nonlocal) scope*** is a special scope that only exists for nested functions. If the local scope is an inner or nested function, then the enclosing scope is the scope of the outer or enclosing function. 


***Built-in scope*** is a special Python scope that’s created or loaded whenever you run a script or open an interactive session. 

>Modifying global names is generally considered bad programming practice because it can lead to code that is:

Difficult to debug: Almost any statement in the program can change the value of a global name.
Hard to understand: You need to be aware of all the statements that access and modify global names.
Impossible to reuse: The code is dependent on global names that are specific to a concrete program.


Good tips when using global scope:

- Write functions that use local names rather than global ones.

- use unique objects names everywhere/
Avoid global name modifications throughout your programs.
- Don't call the module with reserved words 
- Use global names as constants that don’t change during your program’s execution.


### use global , nonlocal to change the varaible type 

### Becareful to not override built in functions for example :

```
max=max([1,2,5,8,7])

def max():
    print('hello)


max()
print (max)

```

it going to give an error ,because of overriding a built in function 






------------------------------------------------    
# Big O Notation 

classes : 
- constant running time O(1)
- Logarthmic running O(log n)
- Linear running time O(n)
- Log- linear running O(nlog n)


![](mypic.png)