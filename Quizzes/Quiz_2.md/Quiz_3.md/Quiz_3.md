##Quiz 3 

###Paper solution 

![Quiz 3 SL](https://github.com/user-attachments/assets/9851bb31-41aa-4267-8c1f-8ecbf0fddf4f)
![Quiz 3 HL](https://github.com/user-attachments/assets/72a9f818-b8a0-438d-b6ec-680547863341)

###Flow Chart
###Code

HL
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
SL
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
    
###Proof of work 
input
![image](https://github.com/user-attachments/assets/db4bb5d7-a6bc-4156-bffd-7ac9f96d841d)
output
![image](https://github.com/user-attachments/assets/e2a9f9e0-5d81-40d6-8874-218e910ff577)
