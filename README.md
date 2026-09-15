# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
<img width="495" height="52" alt="image" src="https://github.com/user-attachments/assets/09e82d42-e6ab-462a-9ff7-9906e7686216" />
Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="616" height="125" alt="image" src="https://github.com/user-attachments/assets/d0372768-a6de-4903-9d79-958afdd7adb8" />

Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="855" height="522" alt="image" src="https://github.com/user-attachments/assets/46028fad-dbbd-432e-8701-c486425fef54" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="617" height="197" alt="image" src="https://github.com/user-attachments/assets/d2870d90-0f50-4b0e-b0d9-ab7d9d8082d4" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="656" height="162" alt="image" src="https://github.com/user-attachments/assets/e1c93695-9787-4942-bfca-f351316a153a" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="572" height="292" alt="image" src="https://github.com/user-attachments/assets/f2bb771d-ee61-417a-b3be-e1adaf2cad98" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="693" height="297" alt="image" src="https://github.com/user-attachments/assets/dbbf201e-61aa-4b85-8163-580a6d50869e" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="825" height="736" alt="image" src="https://github.com/user-attachments/assets/d89e5eb9-ce0a-4262-a112-a983e22d5ca8" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="521" height="172" alt="image" src="https://github.com/user-attachments/assets/e1b039e5-8666-4426-807a-353a787f0264" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="755" height="292" alt="image" src="https://github.com/user-attachments/assets/b0534537-1e4f-4844-af34-8e952071c8d0" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="510" height="212" alt="image" src="https://github.com/user-attachments/assets/c5df3926-6695-4a11-b0d1-0b5bfe5f1d05" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="780" height="290" alt="image" src="https://github.com/user-attachments/assets/16a6c2ac-5170-417e-b6af-69af40e45a6f" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="620" height="515" alt="image" src="https://github.com/user-attachments/assets/7f176260-8ec2-4ffb-92a7-cc4aeda19f4c" />



# RESULT:
The commands/batch files are executed successfully.

