# python
My captain assignment
Q1 

r= float(input('Enter the radius of circle:'))
Area= math.pi*r**2
    print(Area)

Q2

N= input("Enter the file name:")
if ".py" in N:
    print("Python extension")
else
    print("No Python extension")

Q3

N = int(input("Number of elements in Fibonacci Series, N, (N>=2) : "))
fibonacciSeries = [0,1]

if N>2:
	for i in range(2, N):
nextElement = fibonacciSeries[i-1] + fibonacciSeries[i-2]
fibonacciSeries.append(nextElement)

print(fibonacciSeries)

Q4

X= int(input("Enter the number :"))
for X in range (0,n):
if (X>0):
print("Number is positive")
else:
print("Number is negative")
