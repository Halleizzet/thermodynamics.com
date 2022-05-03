import numpy as np
import matplotlib.pyplot as plt 

N = 20

def getuv_in(i): 
    
    for i in range(N):
        i = 1
        Q = ((5/sqrt(i)+(1.5))*(sin(2*pi*((i-N)/2)/2)))
        theta = atan(((i-N)/2.5)/3*N)
        A = 1.5*(pi*(0.1+(4*sin((pi*i)/N+1)/sqrt(i)))**2)
        print(Q)
        print(theta)
        print(A)
        

    
    return u,v
getuv_in(i)
