# project Unit 1 

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
![Delete function (1)](https://github.com/user-attachments/assets/e4d800b5-fece-4506-971b-504148826456)

#### Encryption function 
![Blank diagram (6)](https://github.com/user-attachments/assets/670509ae-d597-4553-a0cf-96e6112a5acd)

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

