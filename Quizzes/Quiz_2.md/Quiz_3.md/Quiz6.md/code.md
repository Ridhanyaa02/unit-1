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
end_code = "\033[00m"
red = "\33[0;31m"

if x == "yes":
    for i in choice_2:
        choice_1.append(i)
elif x == "no":
    pass
for _ in range(l):
    g = str((random.choice(choice_1)))
    print(f'{red}{g}{end_code}', end="")
``
