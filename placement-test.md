1. Given the code below:
    ```python
    a = 10
    b = 4
    a = 2 * a
    b = b + a - (a / b)
    ```
    What is the value of variable `a` at the end of the program? (Just enter numbers)

    > 20

1. Given the code below:
    ```python
    a = 10
    b = 4
    a = 2 * a
    b = b + a - (a / b)
    ```
    What is the value of variable `b` at the end of the program? (Just enter numbers)

    > 19

1. Given the code below:
    ```python
    x = int(input())
    y = int(input())
    print(x, y, x % y)
    ```

    and the input below:
    ```
    10
    3
    ```
    What is the program output? (Enter the right output)

    > ```
    > 10 3 1
    > ```

1. Which are the invalid variable name? Python variable naming rule is similar to C++. (You may choose more than one)
    
    [] `_myvar`

    [] `Myvar`
    
    [X] `1var`
    
    [] `my_var1`
    
    [X] `myVar!`

1.  Given the code below:
    ```python
    if a != b:
        print("Aho!")
    else:
        print("Go!")
    ```
    If we want to have output "Go!", what is the possible value for `a` and `b`

    [] a = 10, b = 5

    [] a = 3, b = 7
    
    [] a = -1, b = 1

    [] a = 8, b = 4

    [X] a = 4, b = 4

1. Given the code below:
    ```python
    for i in range(1, 30):
        if i % 3 == 0:
            print(i)
    ```

    Here is the C++ equivalent code.
    ```cpp
    for (int i = 1; i < 30; i++) {
        if (i % 3 == 0) {
            cout << i << endl;
        }
    }
    ```
    What is the fifth line of the output?

    [] 5
    
    [] 6
    
    [X] 15
    
    [] 18

    [] 24

1. Given the code below:
    ```python
    k = input()
    l = input()
    print(l + k)
    ```
    and the input below:
    ```
    10
    3
    ```
    What is the program output?
    
    [] 103

    [X] 310
    
    [] 3 10
    
    [] 10 3
    
    [] 13

1. Given the code below:
    ```python
    if c < a and b > c:
        if a - b >= 0:
            print(a)
        else:
            print(b)
    elif a >= b:
        if c >= a:
            print(c)
        else:
            print(a)
    else:
        if c <= b:
            print(b)
        else:
            print(c)
    ```
    (Note: `elif` equivalent to `else if` in C++)

    What is the purpose of the program above?
    
    [X] Program will print the maximum value between three numbers

    [] Program will print the minimum value between three numbers
    
    
    [] Program will print the middle value between three numbers
    
    [] Program will choose one between three numbers randomly
    
    [] Program will choose the most frequent value between three numbers

1. Given the code below:
    ```python
    for i in range(1, 5):
        for j in range(X, Y, Z):
            print("*", end="")
        print()
    ```

    C++ equivalent code:
    ```cpp
    for(int i = 1; i < 5; i++){
        for (int j = X; j < Y; j = j + Z) {
            cout << "*";
        }
        cout << endl;
    }
    ```
    What is the right value for (X, Y, Z) if we want program to give output like below?
    ```
    *****
    ****
    ***
    **
    *
    ```

    [] X = 6, Y = i, Z = 1

    [] X = -6, Y = i, Z = -1

    [] X = 6, Y = -i, Z = 2

    [] X = -i, Y = -6, Z = 1

    [X] X = -i, Y = -6, Z = -1

1. Given the code below:
    ```python
    total = 0
    for i in range(10):
        for j in range(0, i, 2):
            total = total + j
    ```

    C++ equivalent:
    ```cpp
    int total = 0;
    for (int i = 0; i < 10; i++) {
        for (int j = 0; j < i; j++) {
            total = total + j;
        }
    }
    ```
    What is the value of variable `total` at the end of the program? (Just enter numbers)

    > 60

1. Given the code below:
    ```python
    if c < a and b > c:
        if a - b >= 0:
            print(a)
        else:
            print(b)
    elif a >= b:
        if c >= a:
            print(c)
        else:
            print(a)
    else:
        if c <= b:
            print(b)
        else:
            print(c)
    ```
    (Note: `elif` equivalent to `else if` in C++)

    Given `a = 5`, `b = 10`, and `c = 7`, what is the output? (Just enter the output)

    > 10

1. Given the code below:
    ```python
    def siap(a, b):
        result = a // b
        if a % b > 0:
            result = result + 1
        return result
    
    b = siap(10, 2)
    c = siap(23, 3)
    ```
    
    C++ equivalent:
    ```cpp
    int siap(int a, int b) {
        int result = a / b;
        if (a % b > 0) {
            result = result + 1;
        }
        return result;
    }

    int main () {
        int b = siap(10, 2);
        int c = siap(23, 3);
    }
    ```
    At the end of the program, the value of `b` is... (Just enter numbers)

    > 5

1. Given the code below:
    ```python
    def siap(a, b):
        result = a // b
        if a % b > 0:
            result = result + 1
        return result
    
    b = siap(10, 2)
    c = siap(23, 3)
    ```
    
    C++ equivalent:
    ```cpp
    int siap(int a, int b) {
        int result = a / b;
        if (a % b > 0) {
            result = result + 1;
        }
        return result;
    }

    int main () {
        int b = siap(10, 2);
        int c = siap(23, 3);
    }
    ```
    At the end of the program, the value of `c` is... (Just enter numbers)

    > 8

1. Given the code below:
    ```
    s = "Semangat Coding~"
    print(s[3] + s[8] + s[2] + s[6] + s[13])
    ```
    What is the program output? (Just enter the output)