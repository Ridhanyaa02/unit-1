## Quiz 2 code 

## SL 

```.py
x = input("enter the first number:")
x = int(x)
y = input("enter the second number:")
y = int(y)

if x ==20:
    print("true")
elif  y ==20:
   print("true")
elif x + y == 20:
   print ("true")
else:
    print ("false")
```

## HL 

```.py
list_1 = [1,2,5,6,7]
list_2 = [20,5,4,6,2]
n = 20
output = False

if n in list_1 or n in list_2:
    output = True
elif sum(list_1) == n or sum(list_2) == n:
    output = True

print(output)

```
