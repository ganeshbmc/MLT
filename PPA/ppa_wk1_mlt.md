# PPA1  

> Write a function named vec_addition(u,v) which takes two vectors u and v as input and returns their vector addition.
> 1. Inputs: u and v are two numerical numpy arrays. 
> 2. Output: a vector representing sum of u and v, if they have consistent shapes, None otherwise.
<br>


    import numpy as np
    file = open("test.py",'w')
    def vec_addition(u,v):
        if u.shape == v.shape:
            return u+v
        return None

<br>
<br>

# PPA2  

> write a function named scalar_multiply(u,k) which takes a vector u and a scalar k as input and returns k times u as output
> 1. Inputs: A vector u and a scalar k
> 2. Output: Returns a vector which is k times u
<br>

    import numpy as np
    def scalar_multiply(u,k):  
        return k*u

<br>
<br>

# PPA3  

> Write a function hadamard(u,v) which takes two vectors u and v as input and returns hadamard product of u and v.
Hdamard product is obtained via multiplying two matrices/vectors elementwise.  
> 1. Inputs: Two vectors u and v
> 2. Output: Hadamard product of u and v if the dimensions of u and v are consistent, otherwise None
<br>  

    import numpy as np
    def hadamard(u,v):  
        if u.shape == v.shape:
            return u*v
        return None

<br>
<br>