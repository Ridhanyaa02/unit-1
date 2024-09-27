# Project Unit 1 

# Criteria A: Planning 

## Problem Definition 

My client, the Guvo polytechnic Institute (GPT), is one of the top engineering and STEM schools in the country. Currently, their community uses a school management system to organise everything from classes, to exams and outside events. In their school management system they have individual unique passwords for both staff and students. The unique password is set by the user themselves and is used for a variety of purposes including submitting assignments, checking grades, assigning assignments, staff accessing and storing test files and answers etc. Recently there have been various problems because of the system, this includes: the lack of password strength, staff of the older generation forgetting their passwords, etc. This has led to issues such as the leakage of test papers, changed scoring, accessing multiple accounts at the same time and more. Recent events regarding the school are deeply affecting the public image of the university and my client, the headmaster, is looking for the most efficient method to prevent the issue. 

## Proposed solution 

In order to solve this issue, we have decided to propose a password management system that is hidden from the public eye. The password manager would be used by key staff in the school such as department leaders, coordinators and the headmaster to manage the log in details of their team members. After conducting a mass survey throughout the school, we discovered a calculator would be the most appropriate front end for this project. As the school is a polytechnic institute, different kinds of calculators are used by the body. This allows for us to integrate our application into the school ecosystem without much suspicion. Furthermore, a calculator is both simple to use and versatile enough for us to build in a password management system. Ultimately, this ensures the safeguarding of sensitive information in the individual accounts and helps preserve the integrity of the school overall. 

### Design description

In order to create the calculator we will be using python along with the IDE pycharm. This simple to use interface is familiar to most of the staff as most work with it on a daily basis. When first opening the program, it will be a simple calculator. However, upon entering the masterkey, the calculator is transformed into a password manager that consists of 3 main functions.

- adding passwords
- deleting passwords
- viewing saved passwords.

Furthermore, once the passwords are saved they will be encrypted with shift 13 for letters and shift 5 for numbers, after which they will be transferred into an external csv file. This ensures maximum security against anyone that might breach the program. 

The entire program can be run on the IDE terminal and will take approximately 2 weeks to create. More elaboration on system specifics is shown in the system diagram below. 

### Rationale 

There have been various aspects that have led to us making the design choices that we have specified in the above paragraph. Starting with the software, python and pycharm are the ideal program to build this project as the staff and student body are already familiar with the software. Furthermore, the simplicity of the pycharm IDE is ideal for our terminal operated program. Pycharm is also a light software that does not take much storage or RAM to operate. This will ensure that 
Most people, regardless of their computer hardware, have access to the application if needed. The calculator program keeps the password manager hidden from the public eye. It's an inconspicuous software that most people would not suspect. Furthermore, the versatility of a calculator allows us to easily create a password manager within it as it provides many opportunities to take in user input. Finally, the encryption used to hide the passwords in an external csv file is shift 13 for letters and shift 5 for numbers. This creates an added layer of security in addition to the hidden functionality, allowing for maximum efficiency and safety. 

### Success Criteria 

1. The calculator should accept user input to perform basic operations (addition, subtraction, multiplication and division)
3. The calculator can handle simple errors (e.g ., division by zero) and give appropriate feedback
4. When the master key is entered the calculator will act as a password manager. The master key is unique for each of the staff and can only be altered with a special code available only to the headmaster. 
5. The password manager should allow the user to add, delete and view stored passwords 
6. Staff should be able to view and access stored password efficiently
7. Users should be able to save password safely and securely in an encrypted csv file
8. The software should have visual cues and aesthetics that allow the user to easily navigate around the terminal 
9. Password manager should work on terminal

# Criteria B: Design
 
### Flow diagrams for algorithms 

#### Delete function

![Delete function (2)](https://github.com/user-attachments/assets/17077d7d-8484-49d0-b84b-390c23e4628c)


#### Encryption function 

![Blank diagram (8)](https://github.com/user-attachments/assets/7cce8037-1872-4fa6-937a-6e8322611f43)

#### Resetting masterkey 

![Blank diagram (7)](https://github.com/user-attachments/assets/c094d21f-c966-48b3-95ea-2c86f2832912)


### Record of tasks 

| **Task number** | **Planned Action**                                               | **Planned Outcome**                                                                                                                                                                                        | **Time Estimated** | **Target completion date** | Criterion |
|-----------------|------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------|----------------------------|-----------|
|        1        | Problem definition Proposed solution                             | Defining the problem will help me better plan out  a solution. This is when I will write my proposed  solution as well including the rationale.                                                            | 30 minutes         | September 11 2024          | A         |
|        2        | Success Criteria                                                 | The Success criteria will act as project goals for me throughout creating the password manager. They  will be the milestones I will have to check up on.                                                   | 20 minutes         | September 12 2024          | A         |
|        3        | Paper solutions for project                                      | Paper solutions for the project helps me brainstorm ideas for the code and how to better execute the  project.                                                                                             | 30 minutes         | 12 - 13 September 2024     | B         |
|        4        | System Diagram                                                   | The system diagram gives me an idea of what the user interface will look like.                                                                                                                             | 20 minutes         | 13 September 2024          | B         |
|        5        | test plan                                                        | Outlining how all the different elements will be tested  along with the input and output for each test. This will  be useful later when I will be testing my product                                       | 45 minutes         | 14 September 2024          |           |
|        6        | creating calculator  (addition and multiplication)               | This is the first step in my project and is the  front end for my password manager. I will start with  addition and multiplication as they are easier.                                                     | 1 hour             | 14 September 2024          |           |
|        7        | creating calculator (Multiplication and division)                | These are the other 2 functions that are required for  my calculator to be fully functional                                                                                                                | 1 hour             | 16 September 2024          |           |
|        8        | Testing calculator functions                                     | To understand if the application and its functions  works fully                                                                                                                                            | 20 minutes         | 17 September 2024          |           |
|        9        | Error checks                                                     | Ensuring that calculator can handle basic errors eg. dividing by 0 and making sure that no system errors occur within the calculator                                                                       | 1.5 hours          | 18 September 2024          |           |
|        10       | Creating password manager  (creating menu and adding passwords)  | The menu is the first step to making the password  manager, after this the next essential step is creating the algorythym for adding passwords                                                             | 2 hours            | 19 September 2024          |           |
|        11       | Creating delete functions                                        | This is the second step of my password manager, which is  being able to delete passwords.                                                                                                                  | 2 hours            | 20 September 2024          |           |
|        12       | Creating view functions                                          | Creating the view password function is the final essential function in my calculator                                                                                                                       | 1 hour             | 21 September 2024          |           |
|        13       | resetting master-key function                                    | Creating the function to reset master-key was an  essential need for the product as my client specifically  requires it to be done.                                                                        | 30 minutes         | 22 September 2024          |           |
|        14       | Encryption                                                       | Encryption is what hides the password from plain view  when stored in the csv file.                                                                                                                        | 2 hours            | 23 September 2024          |           |
|        15       | Testing all password manager functions                           | This is when testing occured, ensuring that there are no  large errors                                                                                                                                     | 20 minutes         | 24 September 2024          |           |
|        16       | Creating visuals cues                                            | This is when the asethetics and visual cues were made to  help the user navigate the password manager and calculator  easier. This is especially relevant in the menu and is  one of my success criteria.  | 1 hour             | 25 September 2024          |           |
|        17       | Creating flow diagrams                                           | flow diagrams for the main areas of my program help visualize the code and functions.                                                                                                                      | 1.5 hours          | 26 September 2024          |           |
|        18       | Product explanation                                              | This step requires explaining the different tools and computing skills that I have used in order to build my project for my  clients needs.                                                                | 2 hours            | 26 September 2024          |           |




### System diagram 

![AMD Ryzen 5 7535HS](https://github.com/user-attachments/assets/9f9bd557-bcba-4311-bc6d-76557b499fac)



## Test plan 



| Test case type | about                                                                       | Input                                                                                    | Expected output                                                                                                                                                 | Actual Output                                                            | Status |
|----------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|--------|
| Functionality  | testing calculator functions                                                | all different operations single, double, triple etc.  digit integers  decimal variables  | Correct calculated answer based on function and values given                                                                                                    | decimal places did not work  as variables  were set to int and not float | Fail   |
| Error checks   | Checking the calculator for any errors. Ensuring it can handle basic errors | Diving by 0                                                                              | "INVALID INPUT"                                                                                                                                                 | "INVALID INPUT"                                                          | pass   |
| Functionality  | testing CRUD operations on  password manager                                | Passwords with different lengths containing different charecters.                        | Add functions appends  user and password to csv file   delete function removes user and password from csv file   view function displays passwords from csv file | as expected                                                              | pass   |
| Security       | testing encryption                                                          | Encrypting passwords with capital  and small letters as well as numbers                  | letters in password are encrypted into  csv file with shift 13.   Numbers in password are encrypted into  csv file with shift 5.                                | as expected                                                              | pass   |
| Functionality  | Resetting masterkey                                                         | entering masterkey and eventually  changing the mastercode                               | mastercode changed                                                                                                                                              | mastercode changed                                                       | pass   |


# Criteria C: Development 

## Tools used 
 
  1. For/while loops 
  2. Functions 
  3. Input validation 
  4. Encryption
  5. If statements

# For loops 

For loops were the backbone of many of my algorithms for this project. Some major areas in which for loops were used include the adding passwords segment and the deleting passwords function. 

In the adding passwords segment, I used a series of if statements to check what the character of the password is so that it could be sorted into the correct encryption program. This was based on if the letter was capital or lowercase or a number. Through iterating through 2 lists at the same time, I was able to index the same item and use that to sort and consequently execute the encryption program. 

### Adding passwords code

```.py
 ## Adding passwords

        if action == "1":

            new_domain = input("Name of User: ")
            new_pass1 = list(input("Enter password: "))
            new_pass2 = list(input("Re-confirm password: "))
            password = new_pass2
            epassword = ""
            if new_pass1 == new_pass2:

                for i in password:
                    for j in Bletters:
                        if i in j:
                            y = cypher2(i)
                            epassword += y
                    for j in Sletters:
                        if i in j:
                            y = cypher(i)
                            epassword += y
                    for j in numbers:
                        if i in j:
                            y = cypher3(i)
                            epassword += y
                    for j in symbols:
                        if i in j:
                            pass

                name_pass = f'{new_domain}, {epassword}'
                with open('password.csv', mode='a') as f:
                    f.writelines(f'\n{name_pass}')
                    print(f'{green}"password successfully added"{end_code}')

            else:
                print(f'{red}PASSWORDS DO NOT MATCH{end_code}')
```

### Deleting passwords code


```.py
            def delete():
                with open("password.csv",mode='a') as f:
                    data = list(passw)
                    output = []
                    output2 = []
                    a = True
                    for row in data:
                        if deletion not in row:
                            output.append(row)
                        elif deletion in row:
                            output2.append(row)
                            a = False
                    if a == True:
                        print(f'{red}USER NOT FOUND{end_code}')
                    elif a == False:
                        with open('password.csv',mode='w') as f:
                            pass
                        with open('Password.csv',mode='a') as f:
                            f.writelines(output)
```

In the deleting passwords function similarly I used a for loop to sort through the rows. The ones that were not meant to be deleted were appended into a new list, meanwhile the rest of the file was cleared. This allowed me to delete certain users based on user input. 


# While loops 

I mainly used while loops in my function in combination with boolean values. An example of this is the transition between my calculator and my password manager functions. During the time the calculator is being used, the variable “activation” remains to be true. When the activation function is false the calculator does not run anymore. This makes it easy to switch between the password manager and the calculator as through using the while loop and boolean values I am able to switch between the 2. 

### Start of the calculator code 

```.py
#Input for operation
while calculator == True:
    while a == True:

        opinput = input("enter operation (+-*/):")

        if opinput == ("+"):
            a = False
        elif opinput == ("-"):
            a = False
        elif opinput == ("*"):
            a = False
        elif opinput == ("/"):
            a = False
        else:
            print(f'{red}INVALID INPUT{end_code}')
            a = True
```

### When password manager is activated 

```.py
   #Getting input from user and converting input from string to float (oassword manager can be unlocked here)

    ninput = (input("enter numbers:"))
    if ninput == "password123":
        calculator == False
        from Password_manager import *
        password_m()
```

### When password manager is being deactivated and program returns to calculator mode 

```.py

  elif action == "5":
            print(f'{blue}Goodbye{end_code}')
            Activation == False
            return(None)
```


# Functions 

The main functions in my program include the encryption function and the password manager itself being a function. 

The encryption function is called cypher and has one parameter which is the string that it is ale to encrypt. The function uses a for loop to convert all letters from a string to have shift 13. 

### Encryption functions 

```.py
## Function for encrypting small letters

def cypher(word:str):
    alphabet = "abcdefghijklmnopqrstuvwxyz"
    alphabet = list(alphabet)
    for i in word:
        final = ""
        for j in alphabet:
            if i == j:
                x = alphabet.index(j)
                if x < 13:
                    x += 13
                elif x > 13:
                    for i in range(0,13):
                        x+=1
                        if x > 26:
                            x = 1
                y = alphabet[x]
                final += y
    return final

## Function for encrypting capital letters

def cypher2(word:str):
    alphabet = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    alphabet = list(alphabet)
    final = ""

    for i in word:
        for j in alphabet:
            if i == j:
                x = alphabet.index(j)
                if x < 13:
                    x += 13
                elif x > 13:
                    for i in range(0,13):
                        x+=1
                        if x > 26:
                            x = 1
                y = alphabet[x]
                final += y
        return final
```
The password manager function on the other hand is much more complex as it contains a lot more detail. It holds all the different components of the password manager. Having the password manager as a function in a separate python file, helps keep my code a lot more organised. Overall its more easy to call as well. 

### Password manager functions 

```.py
def password_m():
    Activation = True

    while Activation == True:

        with open ('Password.csv',mode='r') as f:
            passw = f.readlines()

        ## creating the menu
        print(f'{cyanHI}Welcome to password manager {end_code}')
        print("What would you like to do? ")
        print(f'{purple}[SELECT 1]{end_code}'" Add password ")
        print(f'{purple}[SELECT 2]{end_code}'" Delete password ")
        print(f'{purple}[SELECT 3]{end_code}'" View stored passwords ")
        print(f'{purple}[Select 4]{end_code}'" Change master-key" )
        print(f'{purple}[SELECT 5]{end_code}'" EXIT ")
        action = input(f'{Boldb}Type course of action: {end_code}')

        ## Adding passwords

        if action == "1":

            new_domain = input("Name of User: ")
            new_pass1 = list(input("Enter password: "))
            new_pass2 = list(input("Re-confirm password: "))
            password = new_pass2
            epassword = ""
            if new_pass1 == new_pass2:

                for i in password:
                    for j in Bletters:
                        if i in j:
                            y = cypher2(i)
                            epassword += y
                    for j in Sletters:
                        if i in j:
                            y = cypher(i)
                            epassword += y
                    for j in numbers:
                        if i in j:
                            y = cypher3(i)
                            epassword += y

                name_pass = f'{new_domain}, {epassword}'
                with open('password.csv', mode='a') as f:
                    f.writelines(f'\n{name_pass}')
                    print(f'{green}"password successfully added"{end_code}')

            else:
                print(f'{red}PASSWORDS DO NOT MATCH{end_code}')


        ##Viewing stores passwords

        elif action == "3":
            verification = input(f'{yellow}enter masterkey: {end_code}')
            masterkey = "password123"

            if verification == masterkey:
                print("to view last stored password"f'{purple} [select W]: {end_code}')
                print("to view all saved password"f'{purple} [select Z]: {end_code}')
                action2 = input("enter action: ")

                if action2 == "W":
                    rows = list(passw)
                    last_row = rows[-1]
                    for p in last_row:
                        name,ps = p.split(',')
                        ups = (uncypher(ps))
                        print(name,ups)

                elif action2 == "Z":
                    for p in passw:
                        name, ps = p.split(',')
                        ups = (uncypher(ps))
                        print(name,ups)

                else:
                    print(f'{red}INVALID INPUT{end_code}')

            else:
                print(f'{red}UNAUTHORIZED SECTOR{end_code}')

        ##deleting passwords

        elif action == "2":
        ## Delete Function

            def delete():
                with open("password.csv",mode='a') as f:
                    data = list(passw)
                    output = []
                    output2 = []
                    a = True
                    for row in data:
                        if deletion not in row:
                            output.append(row)
                        elif deletion in row:
                            output2.append(row)
                            a = False
                    if a == True:
                        print(f'{red}USER NOT FOUND{end_code}')
                    elif a == False:
                        with open('password.csv',mode='w') as f:
                            pass
                        with open('Password.csv',mode='a') as f:
                            f.writelines(output)

        ## Asking for input from user

            deletion = input("What is the user you would like to delete?: ")
            c = input(f'{yellow}"Are you sure?[y/n]: {end_code}')
            if c == "y":
                verification = input(f'{yellow}re-enter masterkey: {end_code}')
                if verification == masterkey:
                    delete()
            else:
                pass

        ## Changeing the masterkey

        elif action == "4":
            w = input("what would you like the new masterkey to be?: ")
            if w == mastercode:
                print(f'{cyanHI}WELCOME TO MASTERKEY CHANGING{end_code}')
                verf1 = input("When was the school founded? ")
                if verf1 == verf1ans:
                    verf2 = input("How old is the current headmaster? ")
                    if verf2 == verf2ans:
                        verf3 = input("How old was the current headmaster when his childhood dog died? ")
                        if verf3 == verf3ans:
                            s = input("input new masterkey: ")
                            r = input(f'{yellow}confirm masterkey{end_code}')
                            if s == r:
                                masterkey = r
                                print(f'{cyanHI}MASTERKEY SUCCESSFULLY CHANGED{end_code}')
                            else:
                                print(f'{red}INVALID INPUT{end_code}')
                else:
                    print(f'{red}UNAUTHORIZED SECTOR{end_code}')
            else:
                print("masterkey changed")


        elif action == "5":
            print(f'{cyanHI}Goodbye{end_code}')
            Activation == False
            return(None)

        else:
            print(f'{red}INVALID INPUT{end_code}')
```

Encryption 

The encryption that I used in my project was mainly shift 13 for letters and shift 10 for numbers. I used 2 different shifts as I thought that would be more appropriate than just having one. Furthermore, I also had to consider the range of the different components. My encryption function uses a simple for loop and if statements to execute the encryption on any string. 

### Encryption Functions for numbers (encryption for letters shown above)

```.py
def cypher3(word:str):
    numbers = "0123456789"
    numbers = list(numbers)
    final = ""

    for i in word:
        for j in numbers:
            if i == j:
                x = numbers.index(j)
                if x < 5:
                    x += 5
                elif x > 5:
                    for i in range(0,10):
                        x+=1
                        if x > 10:
                            x = 1
                y = numbers[x]
                final += y
        return final
```


In combination with the encryption function I also created a function that is able to decrypt the password for when the user wants to view passwords in the terminal. This is as follows and is very similar to the encryption function. 

```.py
def uncypher(word:str):
    alphabet = "abcdefghijklmnopqrstuvwxyz"
    alphabet2 = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
    alphabet = list(alphabet)
    alphabet2 = list(alphabet2)
    final = ""
    for i in word:
        if i in alphabet:
            x = alphabet.index(i)
            if x < 13:
                x -= 13
            elif x > 13:
                for i in range(0,13):
                    x-=1
                    if x > 26:
                        x = 1
            y = alphabet[x]
            final += y

        for k in alphabet2:
            if i == k:
                s = alphabet2.index(k)
                if s < 13:
                    s -= 13
                elif s > 13:
                    for i in range(0, 13):
                        s -= 1
                        if s > 26:
                            s = 1
                r = alphabet2[s]
                final += r
    return final
```

If statements and input validation 

If statements played a major role in my project as it was used for a variety of purposes. Some of the main ones include creating the “resetting master key” segment and for the encryption function. 

When resetting the master key the majority of the program is built on if statements as it goes through different stages of verification. The next stage of verification is only accessible if the first one has the correct variable answer. This function also has a decoy at the start. masterkey and mastercode are 2 different variables. Masterkey is used throughout the password manager meanwhile, mastercode is something only my client, the headmaster is aware of. 

### Masterkey vs. Mastercode + verification question answers


```.py
##Master key
masterkey = "password123"

#Final verification
mastercode = "Molelover312"
verf1ans = "2000"
verf2ans = "39"
verf3ans = "14"
```


When "changing masterkey" function is executed a decoy simply asks for the change of password. however, it is only when the mastercode is entered in that area that the user is able to access the verification process to change the masterkey. This process consists of questions about the school that not many would know. If at any point the verification is failed, an else statement is used to print an error. This is also an example of how if statements were used to conduct input validation.


### resetting masterkey segment

```.py
## Changeing the masterkey

        elif action == "4":
            w = input("what would you like the new masterkey to be?: ")
            if w == mastercode:
                print(f'{cyanHI}WELCOME TO MASTERKEY CHANGING{end_code}')
                verf1 = input("When was the school founded? ")
                if verf1 == verf1ans:
                    verf2 = input("How old is the current headmaster? ")
                    if verf2 == verf2ans:
                        verf3 = input("How old was the current headmaster when his childhood dog died? ")
                        if verf3 == verf3ans:
                            s = input("input new masterkey: ")
                            r = input(f'{yellow}confirm masterkey{end_code}')
                            if s == r:
                                masterkey = r
                                print(f'{cyanHI}MASTERKEY SUCCESSFULLY CHANGED{end_code}')
                            else:
                                print(f'{red}INVALID INPUT{end_code}')
                else:
                    print(f'{red}UNAUTHORIZED SECTOR{end_code}')
            else:
                print("masterkey changed")
```


During the encryption process if statements are used very differently. In this case, an if statement is used to check if the variable x is above 13, in which case shift 13 would not be possible since it exceeds the range 26 used by the alphabet. For this reason, we can use if statements to create a structure that when the variable x is over 13, it resets it back to 1. 

### Encryption as an ecample for if statements with integers 

```.py
def cypher(word:str):
    alphabet = "abcdefghijklmnopqrstuvwxyz"
    alphabet = list(alphabet)
    for i in word:
        final = ""
        for j in alphabet:
            if i == j:
                x = alphabet.index(j)
                if x < 13:
                    x += 13
                elif x > 13:
                    for i in range(0,13):
                        x+=1
                        if x > 26:
                            x = 1
                y = alphabet[x]
                final += y
    return final
``` 

## Sources 

How to loop through a list using the index numbers in Python. (2015). Educative. https://www.educative.io/answers/how-to-loop-through-a-list-using-the-index-numbers-in-python

chris, kolade. (2022, March 16). Python Functions – How to Define and Call a Function. FreeCodeCamp.org. https://www.freecodecamp.org/news/python-functions-define-and-call-a-function/
