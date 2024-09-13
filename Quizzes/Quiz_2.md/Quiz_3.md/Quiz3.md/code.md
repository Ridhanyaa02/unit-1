## Quiz 3 code 

## SL 
``` .py
#step 1 - protien chains

chain_1 = ("A","G","T","C")
chain_2 = ("T","C","A","G")

#step 2 - user input
x = input("Protien: ")
if x in chain_1:
#Step 3 - find protien in chain 1 and store as an integer
    y = int(chain_1.index(x))

#Step 4 - use integer to find the corresponding protien in Chain 2 and print
    print(chain_2[y])
else:
    print("input not valid")
```

## HL 
``` .py
#user input for protien and store the string as a list with each letter being a different element
Protien = input("Protien chain:")
Pchain = list(Protien)

#step 1 - protien chains

chain_1 = ("A","G","T","C")
chain_2 = ("T","C","A","G")

#find each protien in chain_1 and store the value as an integer
for i in Pchain:
    if i in chain_1:
        z = int(chain_1.index(i))
#find each integer(index value) in chain_2 and print
        print(chain_2[z],end="")
```
