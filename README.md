[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=18372025)
# practical task Nr.1

**you should submit your program in result.py file**

Write a program that reads information from the file "test1.xlsx" located in the "tests" folder and calculates the number of people whose salary is higher than 3000 EUR per month.

The existing file contains three columns:

|     id     |     hours     |     rate     |
|------------|---------------|--------------|

To determine the monthly salary, you need to multiply the hourly rate by the specified hours. Be careful - some rows may have incorrect data (text instead of numbers). We recommend checking the data type of the obtained values before performing the calculation.

To complete the task, you need to use a **for** loop and **if** conditional statement.

The program should output a numerical value.

To enable the software to perform autotest of your submission, it is necessary to add the library name to the setup.txt file.
To do this, first find out which python version of the library you are using. Type the command pip freeze in the terminal of your IDE.
Find the required python library from the list. (In this example, it is the library openpyxl==3.1.2).
Update the setup.txt file by adding the found library name and version.

Finally, you can resubmit the program.
