---
title: Chain Rule Introduction
---
## Chain Rule Introduction

`Chain Rule is used to compute derivative of a composition of functions.`

Let _F_ be a real valued function which is a composite of two functions _f_ and _g_  i.e `F(x) = f(g(x))`.
Let the derivative D{F(x)} is denoted as F'(x).

By Chain Rule, 
#### _`F'(x) = f'(g(x)).g'(x)`_

Suppose, g(x)=t then F(x)=f(g(x)) can be rewritten as F(x)=f(t) and if both dt/dx and df/dt exist.
then in Leibniz's notation Chain Rule can be rewritten as : 
#### `d(F)/dx = df/dt . dt/dx`

### Examples :

#### Question 1.   To compute derivative of sin(ax+b)

Solution : The function can be visualized as a composite of two functions. F(x)= f(g(x))
t= g(x)= ax+b  and f(t)=sin(t)

f(t)=sin(t) => df/dt = cos(t)
t= g(x) = ax+b => dt/dx = a

Now by Chain Rule: 

d(F)/dx = df/dt . dt/dx
=> d(F)/dx = a . cost(t) = a.cos(ax+b)

#### Question 2.   To compute derivative of sin(5x)




For a function which is composition of more than two function, we can treat the outermost function as the function _f(t)_ where _t_ will again be composite of all the inner function and can apply chain Rule repeatedly till we are left with no inner layer.


