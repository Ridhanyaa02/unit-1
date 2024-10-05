# Quiz 15 
### Paper solutions 
![image](https://github.com/user-attachments/assets/abb61410-39ad-4041-a546-e90b591d9ebb)

### Code
```.py
import random
def average(input:list):
    list_length = len(input)
    word_length2 = 0

    for item in input:
        item = list(item)
        for i in item:
            if i == " ":
                pass
            elif i != " ":
                word_length2 +=1


    output = float(word_length2/list_length)
    print(output)

testcases = (["hello","main"],["Peru","France","Nepal"],["Computer Science","Art"],["one","two"])
input = random.choice(testcases)
print(input)
average(input)
```

### Proof of work 
#### Testcase #1 
![image](https://github.com/user-attachments/assets/93217b09-82f8-489d-904d-ef8335f201b3)
#### Testcase #2 
![image](https://github.com/user-attachments/assets/a8c0d06a-7c68-40b6-9a11-945ad15f4100)
#### Testcase #3 
![image](https://github.com/user-attachments/assets/675369b6-55ef-46a4-b283-9b198f6a307e)
#### Testcase #4
![image](https://github.com/user-attachments/assets/2c1cd4c5-c88e-4684-8cab-eea45b89ab9c)


### Flowchart 
![Quiz 15](https://github.com/user-attachments/assets/8b6ecd8f-286e-4d6c-af2e-e111643cad0f)
