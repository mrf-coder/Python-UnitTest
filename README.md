# Python-UnitTest
- __[Python-Conditionals](https://github.com/mrf-coder/Python-Conditionals.git)__ - 
- __[Python-Loops](https://github.com/mrf-coder/Python-Loops.git)__ - 
- __[Python-Eceptions ](https://github.com/mrf-coder/Python-Eceptions.git)__ - 
- __[Python-Libraries ](https://github.com/mrf-coder/Python-Libraries.git)__ - 
- __[Python-UnitTest ](https://github.com/mrf-coder/Python-UnitTest.git)__ - 
- __[Python-I-o](https://github.com/mrf-coder/Python-I-o.git)__ - 
- __[Regular-Expressions ](https://github.com/mrf-coder/Regular-Expressions.git)__ - 
- __[Object-Oriented-Programming](https://github.com/mrf-coder/Object-Oriented-Programming.git)__ - 
- __[Et-Cetera](https://github.com/mrf-coder/Et-Cetera.git)__ - 



```js

------calculator.py
def main():
    
     x = int (input("What,s X?"))
     print("x  squared is ",  square(x))

def square(n):
      return n + n

if __name__=="__main__":
 main()
----------------------------------------
from calculator import square

def main():
    test_square()

def test_square():
    if square(4) != 16:
        print("4 square was not 16")

    if square(3) !=9:
        print("3 square not 9")

if __name__=="__main__":
        main()    
```
```js
------calculator.py
def main():
    
     x = int (input("What,s X?"))
     print("x  squared is ",  square(x))

def square(n):
      return n + n

if __name__=="__main__":
 main()
----------------------------------------
from calculator import square

def main():
    test_square()

def test_square():
    try:
         assert (4) == 16
    except AssertionError:     
        print("4 square was not 16")
    try:
        assert (3) == 9
    except AssertionError: 
        print("3 square not 9")

if __name__=="__main__":
        main()    


```

```js
----hello.py

def main():
    name = ("What,S your name?")
    print(hello(name))

def     hello(to="world"):
        return f"hello, {to} "

if __name__=="__main__":
     main()         

----------------------------------------------

-----test_hello.py

from hello import hello

def test_hello():
    hello("David") == "hello, David"

def test_hello2():
    hello() == "hello, David"

def test_hello3():
    for name in ["Ron ","Jon","poul"]:
            assert hello(name) == f"hello, {name}"



pytest test_hello.py  run

```
- __[Python-Conditionals](https://github.com/mrf-coder/Python-Conditionals.git)__ - 
- __[Python-Loops](https://github.com/mrf-coder/Python-Loops.git)__ - 
- __[Python-Eceptions ](https://github.com/mrf-coder/Python-Eceptions.git)__ - 
- __[Python-Libraries ](https://github.com/mrf-coder/Python-Libraries.git)__ - 
- __[Python-UnitTest ](https://github.com/mrf-coder/Python-UnitTest.git)__ - 
- __[Python-I-o](https://github.com/mrf-coder/Python-I-o.git)__ - 
- __[Regular-Expressions ](https://github.com/mrf-coder/Regular-Expressions.git)__ - 
- __[Object-Oriented-Programming](https://github.com/mrf-coder/Object-Oriented-Programming.git)__ - 
- __[Et-Cetera](https://github.com/mrf-coder/Et-Cetera.git)__ - 







