### Quiz 6 

### Paper Solution 
![quiz 6 paper solution](https://github.com/user-attachments/assets/242c6ac2-0650-4242-b837-09f39bcb0f7c)

### Flow Chart
### Code
```.py
import random
choice_1 = list("abcdefghijklmnopqrstyvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ")
choice_2 = list("#¤%&/=!;:?-_^~,.|")
l = input("password length")
l = int(l)
x = input("would you like symbols?")

if x == "yes":
    for i in choice_2:
        choice_1.append(i)
else:
    pass

for _ in range(l):
    print(str((random.choice(choice_1))),end="")
```

### Proof of work 

![Quiz 6 input](https://github.com/user-attachments/assets/93d47edd-81b7-41f1-a9ca-e23f1aa11e96)
![Quiz 6 output](https://github.com/user-attachments/assets/4d99e941-3e0c-4f02-84d3-f3f4b3a3fa74)
