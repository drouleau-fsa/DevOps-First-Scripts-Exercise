# DevOps-First-Scripts-Exercise

## Welcome to the DevOps First Class Scripting Exercise!

#### In this exercise we will create our very first scripts, one in Bash and one in Python!
 You might be wondering what's a script, what is Bash, what is Python? And that is quite alright, 
 we will dive into the details of these things as we progress through the course. But for now, here is a high level explanation:
 - a script is a way to automate an action(s) or process(es) that is usually done manually, saving DevOps engineers lots of time
 - Bash is a command line language, most commonly seen in Linux/Unix Operating Systems (OS), used to interact with the OS.
 - Python is a common programming language, used to create lightwieght scripts to full-fledge applications and programs.
 
 ### Let's Get Started!
 
 1. Navigate to the [JSLinux](https://bellard.org/jslinux/) webpage in your browser of choice (Chrome is highly recommended).
 You should then see a screen that looks like this:
 
<img src="https://user-images.githubusercontent.com/87505099/203101423-439f3724-a5f4-4473-bc05-e60791b1f88d.png" width=700>


2. Notice the red outline in the screenshot, we want to select that Linux OS. To do that click on `Click Here`
You should now see a screen that looks like this:

<img src="https://user-images.githubusercontent.com/87505099/203105276-3d8856ec-e3b9-4591-8c2e-acd016dea99f.png" width=600>![Screenshot 2022-11-21 at 12 19 37 PM](https://user-images.githubusercontent.com/87505099/203119593-64cd3e90-204d-4103-8321-ad27149ed476.png)


This is a Linux OS terminal, which is just a command line way of interacting with your OS. All OS today have a command line way of interaction.
In this terminal we can type commands and do things (create/move/update/delete files and folders, launch applications, user administration, etc.).
For this exercise, we will create two scripts that display "Hello World, my name is <Insert Your Name Here>."

### Creating the Bash Script
We will do this two different ways!
 
1. In your new Linux Terminal, type:  
  ```echo "echo \"Hello World, my name is David."\" > hello.sh```
2. Now type:   
  ```chmod 755 hello.sh```
3. Now run it!   
  ```./hello.sh```

![Screenshot 2022-11-21 at 11 42 34 AM](https://user-images.githubusercontent.com/87505099/203111351-8a8a13b8-00c0-47f2-af35-19168abc30b9.png)

If you see the desired output of "Hello World, my name is <Your Name>." as shown in the above screenshot, congrats! You have successfully created your first Bash Script!
 
 ### Bash Script x2
 Now let's do it another way, using a text editor!
 1. In your Linux terminal, type:  
 ```clear```  
 This is a very common and useful command to clear your terminal screen
 2. Now type:   
 ```vim hello2.sh```  
 A new window will display with a green blinking cursor at the top
 3. Now press `i`
 4. Now type:  
 ```echo "Hello World x2, my name is <Insert Your Name Here>"```
 5. Now press `esc` (top left hand corner of your keyboard)
 6. Now type:  
 ```:wq!```  
 If successful, your terminal screen should now display the message ```"hello2.sh" [New] 1L, 41B written```
 7. Now type:  
 ```chmod 755 hello2.sh```
 8. Now run it!  
 ```./hello2.sh```  
 Your output should look similar to the below screenshot:  

 <img src="https://user-images.githubusercontent.com/87505099/203114678-6a3eec81-d27e-4dfc-98e8-71b8286108e4.png" width=600>

 
### Now in Python!
1. In your terminal type:   
```echo -e "#!/bin/python3\n\nprint(\"Hello Python World, my name is <Insert Your Name Here>.\")" > hello.py```   
2. Now type:   
```cat hello.py```     
We can use the `cat` command in Linux to print files to the terminal output
3. Now type:   
```chmod 755 hello.py```   
4. Now run it!   
```./hello.py```
Your output should look similar to the below screenshot:
 
![Screenshot 2022-11-21 at 12 19 58 PM](https://user-images.githubusercontent.com/87505099/203119666-d73b2875-480f-49f4-8b8d-ffa1c76e5bd4.png)

 
 
 ### Congratulations!! You have now created your first Hello World Scripts, in two different programming languages!!
