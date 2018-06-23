---
author: Alistair Knight
title: Passwords suck
subtitle: So how do we deal with that?
date: 23 June 2018
---
##  
**Brackets** are magic force fields that hold bits of mathematics together.


##  
They ensure that everything inside the brackets is treated like it is one thing.

##  
Let's do an example.


##  
By convention, we do multiplication/division before addition/subtraction.


##  
So, if we were given this expression to simplify:
$$1+2\times3$$


##  
we would do the multiplication first
$$1+2\times3$$


##  
we would do the multiplication first
$$1+\bbox[yellow]{2\times3}$$


##  
we would do the multiplication first
$$1+\bbox[yellow]{6}$$


##  
and then the addition
$$1+6$$


##  
and then the addition
$$\bbox[yellow]{1+6}$$


##  
and then the addition
$$\bbox[yellow]{7}$$


##  
and then the addition
$$7$$


##  
If we put brackets around the $1+2$, they act as a shield that stops us from
multiplying until we’ve sorted out the addition. Like this:


##  
Same expression, but now with brackets
$$\bbox[lime]{(1+2)}\times3$$


##  
Like a force field, the brackets protect the expression inside from the $\times$ sign.
$$\bbox[lime]{(1+2)}\times3$$


##  
So we have to simplify the expression in the brackets first.
$$\bbox[lime]{(1+2)}\times3$$


##  
So we have to simplify the expression in the brackets first.
$$\bbox[lime]{(\bbox[yellow]{1+2})}\times3$$


##  
So we have to simplify the expression in the brackets first.
$$\bbox[lime]{(\bbox[yellow]{3})}\times3$$


##  
So we have to simplify the expression in the brackets first.
$$\bbox[lime]{(3)}\times3$$


##  
And now we can turn off the brackets, since there is only one term inside.
$$\bbox[lime]{(3)}\times3$$


##  
And now we can turn off the brackets, since there is only one term inside.
$$3\times3$$


##  
And now we can multiply:
$$3\times3$$


##  
And now we can multiply:
$$\bbox[yellow]{3\times3}$$


##  
And now we can multiply:
$$\bbox[yellow]{9}$$


##  
We got a different answer, $9$, because we did things in a different order.
The other way we got $7$.


##  
So we can see that
$$1+2\times3=7$$ but
$$(1+2)\times3=9$$

##  
So brackets are useful when we want to treat an expression as one thing, and
they force us to evaluate the contents of the brackets first.
