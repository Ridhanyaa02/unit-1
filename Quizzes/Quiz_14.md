# Quiz 14
### Paper solutions 
![image](https://github.com/user-attachments/assets/68209565-c608-42b9-8dfe-c6b91f756bb4)

### Code
```.py
def doors(students:int):
    num_doors = []

    for i in range(students):
        num_doors.append(0)

    for i in range(students):
        increment = i + 1
        for j in range(1,len(num_doors),increment):
            if num_doors[j] == 1:
                num_doors[j] = 0
            else:
                num_doors[j] = 1

    output = sum(num_doors)
    print(output)

doors(10)
```

### Proof of work 
#### Testcase #1 (n = 200)
![test case 1](https://github.com/user-attachments/assets/0ec4189a-b04f-4144-acb1-2b50aab11b88)

#### Testcase #2 (n = 200)
![test case 2](https://github.com/user-attachments/assets/5be12b86-e123-4b79-ac70-cec56f65ba26)

#### Testcase #3 (n = 200)
![image](https://github.com/user-attachments/assets/3d4f957c-e7f4-407b-93e3-ff0ef53fd0b9)

#### Testcase #4 (n = 5676)
![image](https://github.com/user-attachments/assets/9d2e6051-ca00-4503-8290-5d26842b5cdc)

### Flowchart
![Quiz 14](https://github.com/user-attachments/assets/2ac480a6-0010-4e94-9e16-b62032750997)
