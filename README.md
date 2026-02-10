# Python-Program-to-Find-the-Nth-Term-of-Fibonacci-Series-Using-Recursion
def Fib(n):
    if n <= 0:
        print("Invalid input")
        return
    elif n == 1:
        return 0
    elif n == 2:
        return 1
    else:
        return Fib(n - 1) + Fib(n - 2)

print(Fib(7))

Output:
8
