# Pain vs. Suffering

in this article ther
e is a good psychological prep so we can hold on and
endure the pain we gonna have in out way to success and building our new career !


Hightled Points :

>You’ll be pushed mentally, having to think your way through problems that you had only even heard about a few hours beforehand.

>You’ll Constantly be having to figure out how to collaborate with new people and deal with their (and your own) emotional quirks.

>You’ll be pushed physically, and while sitting in a chair and staring at your screen isn’t the most strenuous exercise in the world, the consecutive hours of it will take its toll.

![No pain no gain](https://i.pinimg.com/originals/c6/0b/36/c60b36384bf60eff3cabaa09e88315b7.png)


# A beginner's guide to Big O Notation

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


# Logarithms
 Logarithm

 This type of algorithm is described as O(log N).

As complexity is often related to divide and conquer algorithms, O(log(n)) is generally a good complexity you can reach for sorting algorithms. O(log(n)) is less complex than O(√n), because the square root function can be considered a polynomial, where the exponent is 0.

# Names & Values in Python

Rules for Python variables:

A variable name must start with a letter or the underscore character
A variable name cannot start with a number
A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
Variable names are case-sensitive



The behavior of names and values in Python can be confusing. Like many parts of Python, it has an underlying simplicity that can be hard to discern, especially if you are used to other programming languages.

As in many programming languages, a Python assignment statement associates a symbolic name on the left-hand side with a value on the right-hand side. In Python, we say that names refer to values, or a name is a reference to a value

x = 23

An important fact about assignment:

Fact: Assignment never copies data. When values have more than one name, it’s easy to get confused and think of it as two names and two values:

x = 23
y = x

Assigning a value to a name never copies the data, it never makes a new value. Assignment just makes the name on the left refer to the value on the right.

### Python is dynamically typed, which means that names have no type.

Just as names have no type, values have no scope. When we say that a function has a local variable, we mean that the name is scoped to the function: you can’t use the name outside the function, and when the function returns, the name is destroyed. But as we’ve seen, if the name’s value has other references, it will live on beyond the function call. It is a local name, not a local value.

