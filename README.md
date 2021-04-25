# Codekata
The CodeKata as given to me:

The code will process an input file. 
Each line in the input file will start with a command. There are two possible commands. 
The first command is Driver, which will register a new Driver in the app. Example: Driver 
Dan The second command is Trip, which will record a trip attributed to a driver. The line 
will be space delimited with the following fields: the command (Trip), driver name, start 
time, stop time, miles driven. Times will be given in the format of hours:minutes. We'll 
use a 24-hour clock and will assume that drivers never drive past midnight (the start 
time will always be before the end time). Example: Trip Dan 07:15 07:45 17.3 Discard any 
trips that average a speed of less than 5 mph or greater than 100 mph. Generate a 
report containing each driver with total miles driven and average speed. Sort the output 
by most miles driven to least. Round miles and miles per hour to the nearest integer. 
Example input: 
Driver Dan 
Driver Alex 
Driver Bob 
Trip Dan 07:15 07:45 17.3 
Trip Dan 06:12 06:32 21.8 
Trip Alex 12:01 13:16 42.0 
Expected output: 
Alex: 42 miles @ 34 mph 
Dan: 39 miles @ 47 mph 
Bob: 0 miles

This project could have taken many different forms, it could have easily been written in SQL using a stored procedure to do the sorting and the math. 
This projest could have bot C# and SQL.
This there was on nonstrant on how it was to be written I wrote it as a C# console application. 
I assumed that since the output in the kata does not match what is in the text I put in a constrant tha can be tured on or off to match the kata text. 
I also added some more data to give a better representation of what the progam can do. 
