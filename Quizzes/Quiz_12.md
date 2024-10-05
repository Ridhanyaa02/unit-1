# Quiz 12
### Paper solutions
![image](https://github.com/user-attachments/assets/8a6fa8a9-e08b-4e2f-91b2-4f279344eef7)

### Code
```.py
import random

def process(a:int,b:int):
    product = a * b

    if b == a:
        difference = 0
        result = product

    elif b > a:
        difference = b - a
        result = product - difference

    elif a > b:
        difference = a - b
        result = product + difference

    print(result)

process()
```

### Proof of work 
#### Testcase #1 (2,6)
![image](https://github.com/user-attachments/assets/2960c230-3889-4c83-8725-44901ca2161c)
#### Testcase #2 (4,10)
![image](https://github.com/user-attachments/assets/0ba95569-dfb1-424e-b05b-2e79dd83637b)
#### Testcase #3 (10,10)
![image](https://github.com/user-attachments/assets/127ffab3-3de9-48b4-8328-34152b1c2268)
#### Testcase #4 (70,50)
![image](https://github.com/user-attachments/assets/461b3489-417a-4638-8e5b-89e620bdec81)

### Flowchart
![Blank diagram (9)](https://github.com/user-attachments/assets/889a6c58-2926-414c-8e74-5a393a8dd5fa)
