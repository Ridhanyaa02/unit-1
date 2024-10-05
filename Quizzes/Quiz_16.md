# Quiz 16
### Paper solutions
![image](https://github.com/user-attachments/assets/72fd5935-ddc4-42d3-b023-47564ab03a82)

### code 

```.py
import random

def code(msg:str):
    letters = {"a":"4","e":"3","i":"1","o":"0"," ":"_"}

    for i in msg:
            for key in letters:
                if i == key:
                    new = letters[key]
                    msg = msg.replace(i,new)

    print(msg)
testcases = ["Hello World","Why did I choose CS","Remember the Figure Caption"]

code(random.choice(testcases))
``
### Proof of work

#### testcase #1 (Hello World)
![image](https://github.com/user-attachments/assets/0ea58e8f-e878-4a2d-855e-a205dd208592)

#### Testcase #2 (Remember The Figure Caption)
![image](https://github.com/user-attachments/assets/565ce593-35ac-43e7-9834-4153c9313fb9)

#### Testcase #3 (Why Did I Choode CS)
![image](https://github.com/user-attachments/assets/99939336-99e4-42f0-9582-e3d4d6eaa803)


### Flowchart
![Quiz 16](https://github.com/user-attachments/assets/7cea4e6e-7f0e-4366-877f-a264e2ae4cb5)
