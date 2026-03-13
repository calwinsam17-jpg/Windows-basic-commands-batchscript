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
<img width="587" height="66" alt="image" src="https://github.com/user-attachments/assets/981d25f4-cdae-42d1-811d-d87081affd79" />
Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="614" height="55" alt="image" src="https://github.com/user-attachments/assets/17ddd278-e48f-4af4-b377-05961ed7a20e" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="648" height="112" alt="image" src="https://github.com/user-attachments/assets/e25e8497-9afe-4e90-b855-f5a3587a4218" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="786" height="60" alt="image" src="https://github.com/user-attachments/assets/85c8aab1-6305-4744-9783-33c8811748db" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

Remove the file hello1.txt

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

List out all the associated file extensions 

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
<img width="733" height="532" alt="image" src="https://github.com/user-attachments/assets/18a9d8e6-898d-4cb9-883d-ce7ce9465acf" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

<img width="653" height="256" alt="image" src="https://github.com/user-attachments/assets/7dcd3003-b825-4d15-a1ce-eda9eaad26d5" />




## OUTPUT
<img width="503" height="81" alt="image" src="https://github.com/user-attachments/assets/f536a8c4-1906-41a8-914d-4dc5582139f1" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.


<img width="674" height="124" alt="image" src="https://github.com/user-attachments/assets/da376592-4358-4397-ace7-7321ab5150a5" />


## OUTPUT

<img width="511" height="90" alt="image" src="https://github.com/user-attachments/assets/f6678b5f-25b9-4432-a059-bc4f07972e06" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="554" height="224" alt="image" src="https://github.com/user-attachments/assets/719fcd04-0df5-46ac-8ce9-14eb3075c909" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

<img width="510" height="106" alt="image" src="https://github.com/user-attachments/assets/ff1cceb2-a380-430e-b52a-457f76620a01" />

## OUTPUT

<img width="663" height="566" alt="image" src="https://github.com/user-attachments/assets/b6ac5521-98d2-4b4c-bb39-c2a26bea3617" />


# RESULT:
The commands/batch files are executed successfully.

