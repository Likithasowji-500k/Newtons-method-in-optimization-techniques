# Newtons-method-in-optimization-techniques
import math
x=[]
a=int(input())
x.append(a)
k=1
e=10**(-3)
def f(x):
  return x**2+(54/x)
def f1(x):
  return (2*x-(54/x**2))
def f2(x):
  return 2+(108/x**3)
i=0
print("finding the minimum for newtons method upto 3 iterations")
while(i<3):
  b= x[i]-(f1(x[i])/f2(x[i]))
  x.append(b)
  print("x[0]:",x[i]," | f1(x[i]):: ",f1(x[i]), " | f2(x[i])::",f2(x[i]), " |x[i+1] ::", x[i+1])
  i=i+1
print("the minimum lies in ", x[-1])
