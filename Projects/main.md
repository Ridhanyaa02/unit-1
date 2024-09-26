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


### Record of tasks 

# Criteria B: Design
 
### System diagram 
### Flow diagrams for algorithms 
