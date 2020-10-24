# CIS-3145-001-Python-Projects

Project CH6
Chapter 06 Monthly Sales
Create a program that displays 12 months of sales data, calculates the total yearly sales and average monthly sales, and allows the user to edit the sales for any month.
Specifications
•	Store the month sales in a list of lists at the beginning of the main method. 
monthlySales =    [['Jan', '616'], ['Feb', '466'], ['Mar', '796'], ['Apr', '238'], 
			  ['May', '310'], ['Jun', '726'], ['Jul', '987'], ['Aug', '604'], 
			  ['Sep', '951'], ['Oct', '958'], ['Nov', '238'], ['Dec', '610']]
•	Create functions for the monthly, yearly, and edit commands. The functions will take the sales list as an input parameter. Call each function from an if statement in the main method. 
•	The yearly function will calculate the average based on the total sales and the length of the list.
•	The edit function will ask the user for the three-letter month and sales value and make a list of the two values and replace the current single month list with the updated single month list.
•	For the edit function, display an error message if the user doesn’t enter a valid three-letter abbreviation for the month. Use the following list as the standard abbreviations. 
months = ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec']
•	Round the results of the monthly average to a maximum of 2 decimal digits.

Project CH7
Chapter 07 Monthly Sales
Create a program that reads the sales for 12 months from a file and displays 12 months of sales data, calculates the total yearly sales and average monthly sales, and allows the user to edit the sales for any month.
Specifications
•	Use the CSV file named monthly_sales.csv that contains the month and sales data shown above.
•	Write a function to open file and read the CSV file. This function will not have a parameter. Each row in the file will be turned into a list that holds the month and sales value for the month. Each row list will be added to a list that is returned by the function.  
•	Create a function that saves the monthly sales list to the CSV file. This function will take a list as a parameter. 
•	Create functions for the monthly, yearly, and edit commands. The functions will take the sales list as an input parameter. Call each function from an if statement in the main method. 
•	The main method will call the function that reads the file to store the list of lists in the monthly sales list.
•	The edit function will call the function that writes to the CSV file immediately after any change to the list are completed. 
•	The yearly function will calculate the average based on the total sales and the length of the list.
•	The edit function will ask the user for the three-letter month and sales value and make a list of the two values and replace the current single month list with the updated single month list.
•	For the edit function, display an error message if the user doesn’t enter a valid three-letter abbreviation for the month. Use the following list as the standard abbreviations. 
months = ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec']
•	Round the results of the monthly average to a maximum of 2 decimal digits.

Project CH8
Chapter 08 Monthly Sales
Add exception handling to the program that reads the sales for 12 months from a file and calculates the total yearly sales as well as the average monthly sales. Add the exception handling to the chapter 07 program. 
Specifications
•	If the program can’t find the CSV file when it starts, display an error message and exit the program.
•	If the CSV file doesn’t contain a valid integer for the sales amount for the month, use a value of 0 to calculate the total sales for the year.
•	Use the CSV file named monthly_sales.csv that contains the month and sales data shown above.
•	Write a function to open file and read the CSV file. This function will not have a parameter. Each row in the file will be turned into a list that holds the month and sales value for the month. Each row list will be added to a list that is returned by the function.  
•	Create a function that saves the monthly sales list to the CSV file. This function will take a list as a parameter. 
•	Create functions for the monthly, yearly, and edit commands. The functions will take the sales list as an input parameter. Call each function from an if statement in the main method. 
•	The main method will call the function that reads the file to store the list of lists in the monthly sales list.
•	The edit function will call the function that writes to the CSV file immediately after any change to the list are completed. 
•	The yearly function will calculate the average
•	The yearly function will calculate the average based on the total sales and the length of the list.
•	The edit function will ask the user for the three-letter month and sales value and make a list of the two values and replace the current single month list with the updated single month list.
•	For the edit function, display an error message if the user doesn’t enter a valid three-letter abbreviation for the month. Use the following list as the standard abbreviations. 
months = ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul', 'Aug', 'Sep', 'Oct', 'Nov', 'Dec']
•	Round the results of the monthly average to a maximum of 2 decimal digits.

Project CH9
Chapter 09 Sales Report
Create a program that displays a report of sales by quarter for a company with four sales regions (Region 1, Region 2, Region 3, and Region 4).
Specifications
•	The quarterly sales numbers for each region should be hard coded at the beginning of the program as a list of lists like this:
sales = [[1540.0, 2010.0, 2450.0, 1845.0],	# Region 1
[1130.0, 1168.0, 1847.0, 1491.0],		# Region 2
[1580.0, 2305.0, 2710.0, 1284.0],		# Region 3
[1105.0, 4102.0, 2391.0, 1576.0]]		# Region 4
•	Create output that follows the formatting shown in the display above.
•	Use a formatting that dynamically changes based on the computer’s locale setting.
•	Use for loops to calculate and display the totals by quarter and region, as well as the final total annual sales. 

Project CH11
Chapter 11 Arrival Time Estimator
Create a program that calculates the estimated duration of a trip in hours and minutes. This should include an estimated date/time of departure and an estimated date/time of arrival.
Specifications
•	For the date/time of departure and arrival, the program should use the YYYY-MM- DD format for dates and the HH:MM AM/PM format for times.
•	Create a single data/time string variable based on the two input variables. Use this combined string variable to create a departure date-time object that will be used to determine the estimated arrival date and time.
•	For the miles and miles per hour, the program should only accept integer entries like 200 and 65.
•	Calculate the hours travelled based on the integer division of miles divided by mph. The minutes are based on the remainder of miles divided by mph. The remainder must then be converted to minutes based on the mph.
•	Assume that the user will enter valid data.

Project CH12
Chapter 12 Monthly Sales
Create a program that allows you to view and edit the sales amounts for each month of the current year. Follow the formatting shown in the sample output.
Command: totals	
Yearly total:	7,535.00
Monthly average:	627.92
Specifications
•	Use the text file named monthly_sales.txt that consists of tab delimited rows, where the rows contain three-letter abbreviations for the month and the monthly sales. Create a module level constant to hold the name of the text file.
•	The program should contain a function that reads the file and store the sales data for each month in a dictionary with the month abbreviation as the key for each sales value item. For each line of text in the file remove the new line character and split the line into a list that is used to create the dictionary. The function will return the dictionary. 
•	The program should contain a function that writes the dictionary values to the file. The dictionary will be passed to the function as a parameter. For each month and sales amount key value pair in the dictionary write a tab separated line to the text file.
•	Whenever the sales data is edited, the program should write the changed data to the text file.
•	When viewing or editing a month, check if the input month is a valid key in the dictionary and display a message if the three-letter month is not valid. 

Project CH14
Chapter 14 Customer Viewer
Create an object-oriented program that reads a list of Customer objects from a CSV file and allows the user to display the data for a customer by specifying the customer’s ID using the format shown below.
Specifications
•	Use the CSV file named customers.csv that contains customer data.
•	Create a Customer class, in its own Python file, to create objects that will store customer data. This class should include these attributes: id, firstName, lastName, company, address, city, state, zip.
•	In addition, the Customer class will include a property or method that returns the full address as a string. This address should have three lines if the company attribute is empty or four lines if the company attribute is not empty. See the examples in the sample output.
•	The module with the main method will need to import the Customer class. 
•	In the module with the main method, create a function that reads the customer data from the CSV file, creates a list of Customer objects, and returns the list. A loop will read each row for the file, create a customer object, and append the object to a list before returning the list. 
•	Be sure to skip the first row of data in the file that has the header text for the file (“cust_id”, “first_name”, “last_name”, “company_name”, “address”, “city”, “state”, “zip”).  Remember that each row in the CSV reader is a list with one element for each of the 8 pieces of data. 
•	To find the customer with the specified ID, loop through each Customer object in the list of Customer objects and check whether the ID inputted from the user matches the ID stored in the Customer object.
•	If the specified ID isn’t found, display an appropriate message.

=====================================================================================================================================================================================================================

Project 1
A project to manage a baseball team’s information
(1)	Create a program that lets the manager of a baseball team track the data for each player and  display the lineup for a baseball game. 
(2)	Store the data in a text file that is loaded when the program starts. 
Sample Console Output
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
                Baseball Team Management Program
MENU OPTIONS
1 – Display lineup
2 – Add player
3 – Remove player
4 – Move player
5 – Edit player position
6 – Edit player stats
7 - Exit program

POSITIONS
C, 1B, 2B, 3B, SS, LF, CF, RF, P
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

Menu option: 2
Name: Mike
Position: c
At bats: 11
Hits: 4
Mike was added.

Menu option: 1
	Player		POS	AB	H	AVG
----------------------------------------------------------------
1	Trevor		SS	588	173	0.294
2	Garrett	2B	299	74	0.247
3	Tony		C	535	176	0.329
4	Hunter		RF	580	182	0.314
5	Ian		CF	443	113	0.255
6	Nolan		3B	588	185	0.315
7	Daniel		1B	430	129	0.3
8	David		LF	374	113	0.302
9	Phillip	P	102	12	0.118

Menu option: 3
Enter a lineup number to remove: 10
Mike was deleted.

Menu option: 4
Enter a current lineup number to move: 8
Jarrett was selected.
Enter a new lineup number: 2
Jarrett was moved.

Menu option: 5
Enter a lineup number to edit: 1
You selected Joe POS=2B
Enter a new Position: SS
Joe was updated.

Menu option: 7
Bye!

Specifications
PART 1
•	Create a program that manages a team by storing data in a list of players. The list will be stored in the main method.
•	Use a list of lists to store each player in the lineup. The list for a single player includes their name, position, at bats, and hits. Example list with two players:
lineupList = [[Trevor, 'SS', '588', '173'], 
                                       [Garrett', '2B', '299', '74']]
•	For part 1 this list will be declared with a statement in the main method.

•	Use functions to organize the code making it reusable, easy to read, and easy to maintain. Each of the functions for the six main menu features should take the list of players as an input parameter. 

•	Use a tuple to store all valid positions (C, 1B, 2B, etc).
•	When entering/editing positions, the program should always require the user to enter a valid position.

•	The formula for calculating batting average is:
average = hits / at_bats
•	The program should round batting average to a maximum of three decimal places.

•	If the user enters an invalid menu option, display an error message, and display the menu again so the user can clearly see the valid menu options.
•	Make sure the user can’t enter data that doesn’t make sense (such as a negative number of hits or the player having more hits than at bats).
•	Handle the exceptions that occur if the user enters a string where an integer is expected.
•	Handle the exception that occurs if the user enters zero for the number of at bats.

PART 2
•	Use the BaseballPlayers.csv file that is on the assignment page as the source for the lineup.
•	Store the functions for writing to and reading from the file of players in a separate module named FileIO.py. Use the csv module for file I/O operations. The function that reads the file will return the list of players. The function that writes to the file will take a lineup list as the input parameter. 
•	For part 2 replace the statement in the main method that declares the lineup list with a statement that calls the read method in the FileIO module. Call the FileIO module in any function that modifies the lineup list.
•	Handle the exception that occurs if the program can’t find the data file.


Use a top-down development process. For example, start by writing a main method that calls a  function that prints the title. Test the program and fix any errors. Then add a function that prints the menu options, call the function from the main method, test it, and move on to the next feature. 
Get as much of the Part 1 functions completed before moving on to Part 2. 
Make sure that there is always a working version that can be turned in even if it is incomplete. 
Projects can require the use of material from any of the previous chapters covered in the textbook.
Create a Team Management Python program that satisfies the specifications above. 
Put General Comments at the beginning of the project that includes (1) your name, (2) the project name, (3) the date, and (4) a description of the project. 
Turn in a ZIP file of the final version of the program. Include a Word document which contains output of the testing done on the program. The Word document must be inside the ZIP file.
In the Comments section on the Assignment webpage, report (A) an estimate of the time it took to complete the project. Report a single value in minutes, and (B) a single rating of the project, on an ordinal scale, as either (1) Easy, (2) Moderate, (3) Hard, OR (4) Challenging. 

=============================================================================================================================================================================================================================================================================================================================

Project 2
Team Management Program: Version 2
Update the team tracking program used in project #1. This program will use a list of dictionary objects where each player is represented by a dictionary of the player’s ‘name’, ‘position’ (POS), ‘at_bats’ (AB),and ‘hits’ (H).  
The programs will consist of one Python file to hold the main method and supporting functions, and a second Python file (FileIO.py) with two functions which read from and write to a comma delimited csv file. The program will use a file named players.csv to store the data. Remember that each row in a CSV reader object is a list and each column in the row can be accessed with a list index. 
The data is loaded into a list in the main method before the user is asked for a menu option. The list will be used as an argument when calling a support function. 
The separator lines are 60 characters based on the multiplication operator. The format for the lineup display columns will use 3 spaces for the order number, 31 spaces for the player name, 6 spaces for the position, at bats, and hits, and 8 spaces for the batting average. The batting average must always have 3 decimals.
Use a tuple to represent the valid positions a player can have.

Sample Console Output
When the program starts the user has the option to enter a game date. The current date is printed by the program with the YYYY-MM-DD format. This format is used for all date input and output. 
================================================================
                   Baseball Team Manager

CURRENT DATE:    2020-07-12
GAME DATE:    


If no date is entered display the menu options.
================================================================
                   Baseball Team Manager

CURRENT DATE:    2020-07-12
GAME DATE:       

MENU OPTIONS
1 – Display lineup
2 – Add player
3 – Remove player
4 – Move player
5 – Edit player position
6 – Edit player stats
7 - Exit program

POSITIONS
C, 1B, 2B, 3B, SS, LF, CF, RF, P
================================================================
Menu option:  






If a date is entered display the number of days till the game and then the menu option. Do not display the number of games if the date entered is in the past. 

================================================================
                   Baseball Team Manager

CURRENT DATE:    2020-07-12
GAME DATE:       2020-07-19
DAYS UNTIL GAME: 7

MENU OPTIONS
1 – Display lineup
2 – Add player
3 – Remove player
4 – Move player
5 – Edit player position
6 – Edit player stats
7 - Exit program

POSITIONS
C, 1B, 2B, 3B, SS, LF, CF, RF, P
================================================================ 
Menu option:  1
   Player                                POS    AB     H     AVG
----------------------------------------------------------------
1  Dominick Gilbert                       1B   545   174   0.319
2  Craig Mitchell                         CF   533   127   0.238
3  Jack Quinn                             RF   535   176   0.329
4  Simon Harris                            C   485   174   0.359
5  Darryl Moss                            3B   532   125   0.235
6  Grady Guzman                           SS   477   122   0.256
7  Wallace Cruz                           LF   475   138   0.291
8  Cedric Cooper                          2B   215    58   0.270
9  Alberto Gomez                           P   103    21   0.204

Menu option:

Notes: 
The function that reads the CSV file can use the csv module and should loop through one row of the file at a time. For each row populate the dictionary for a player based on the 4 columns of data in the file and add that dictionary object to the list of players. The function will return the list of dictionary objects.

The function that writes to the CSV file should not use the csv module writerows method since this method does not work with a dictionary. Treat the CSV file as a text file when opening the CSV file. Using a loop for the players list, call the file write method to write the name, position, at bats, and hits values separated by commas. Make sure to include a new line escape sequence after the hits value.  

Submission details
Projects can require the use of material from any of the previous chapters covered in the textbook.
Create a Team Management Python program that satisfies the specifications above. 
Put General Comments at the beginning of the project that includes (1) your name, (2) the project name, (3) the date, and (4) a description of the project. 
Turn in a ZIP file of the final version of the program. Include a Word document which contains output of the testing done on the program. The Word document must be inside the ZIP file.
In the Comments section on the Assignment webpage, report (A) an estimate of the time it took to complete the project. Report a single value in minutes, and (B) a single rating of the project, on an ordinal scale, as either (1) Easy, (2) Moderate, (3) Hard, OR (4) Challenging. 
