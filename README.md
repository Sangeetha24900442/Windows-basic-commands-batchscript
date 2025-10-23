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

<img width="825" height="114" alt="image" src="https://github.com/user-attachments/assets/75f2b6b3-e338-4ae4-bf7a-338724d6acb1" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="629" height="57" alt="image" src="https://github.com/user-attachments/assets/1cba0e76-2e72-477b-972a-bd155d2946ab" />



Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="680" height="101" alt="image" src="https://github.com/user-attachments/assets/c9f74fdd-81b1-4b2c-bf09-4675ffe7427e" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="690" height="67" alt="image" src="https://github.com/user-attachments/assets/857084b1-0eff-49f3-b794-dc7f14917df4" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="662" height="75" alt="image" src="https://github.com/user-attachments/assets/12e7dee0-95a9-4931-bb3f-710e2915ff45" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="649" height="59" alt="image" src="https://github.com/user-attachments/assets/b3cb0cb1-4613-40af-9963-e9faf080aef9" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="678" height="193" alt="image" src="https://github.com/user-attachments/assets/2a7e9386-b393-4dd2-92f7-e74f64c80fea" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="564" height="1072" alt="Screenshot 2025-10-23 033043" src="https://github.com/user-attachments/assets/50fa8e19-dd64-4d03-9654-0598afed0730" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="715" height="214" alt="image" src="https://github.com/user-attachments/assets/546a906a-f8fd-4359-89db-0a72a78125ea" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".




## OUTPUT

<img width="743" height="159" alt="Screenshot 2025-10-23 035503" src="https://github.com/user-attachments/assets/bec899ae-de73-4a69-aa13-879284978d96" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="726" height="221" alt="Screenshot 2025-10-23 035513" src="https://github.com/user-attachments/assets/6c4f8dea-3ec8-4906-84b9-8ddbf627c118" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="716" height="178" alt="Screenshot 2025-10-23 035520" src="https://github.com/user-attachments/assets/03214f28-cfef-4911-921f-2f9d4b31e4c8" />





Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="665" height="99" alt="Screenshot 2025-10-23 035526" src="https://github.com/user-attachments/assets/8275b9c0-6509-4f99-8976-1d418bfc22f7" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="907" height="689" alt="Screenshot 2025-10-23 035924" src="https://github.com/user-attachments/assets/9b9e2d46-6f2c-4b9c-b09c-11c928035f26" />




# RESULT:
The commands/batch files are executed successfully.

