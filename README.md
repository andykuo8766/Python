# Python 

## Module(模組)
https://docs.python.org/zh-tw/3/tutorial/modules.html


```python
# Fibonacci numbers module
def fib(n):    # write Fibonacci series up to n
    a, b = 0, 1
    while a < n:
        print(a, end=' ')
        a, b = b, a+b
    print()

def fib2(n):   # return Fibonacci series up to n
    result = []
    a, b = 0, 1
    while a < n:
        result.append(a)
        a, b = b, a+b
    return result
```



## 物件


## unittest

## coverage 

## https://github.com/PyCQA/pycodestyle