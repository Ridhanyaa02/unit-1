## Quiz 6 code

## SL
```.py
import random
choice_1 = list("abcdefghijklmnopqrstyvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ#¤%&/=!;:?-_^~,.|")

for _ in range(20):
    print(str((random.choice(choice_1))),end="")
```

## HL
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
elif x == "no":
    pass
for _ in range(l):
    print(str((random.choice(choice_1))),end="")
``
