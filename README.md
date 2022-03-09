# recursion
calculate the factorial of number by recursive way.
def fact (x):
    if x == 1 :
        return x
    else:
        return x * fact(x-1)

value = int (input("Enter the value: "))
result = fact(value)
print(result)
