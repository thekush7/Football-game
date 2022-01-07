# Football-game
A fun c++ project in which you can make and manage a football team and play a probability football match.

HEADER FILES

1) #INCLUDE&lt;FSTREAM.H&gt;
2) #INCLUDE&lt;CONIO.H&gt;
3) #INCLUDE&lt;STDIO.H&gt;
4) #INCLUDE&lt;STDLIB.H&gt;
5) #INCLUDE&lt;PROCESS.H&gt;
6) #INCLUDE&lt;IOMANIP.H&gt;
7) #INCLUDE&lt;STRING.H&gt;
8) #INCLUDE&lt;DOS.H&gt;

METHODOLOGY

This project includes class players.
Class players has the following functions:

➢ void getdata()- This function inputs the
details of a player like his jersey
number, name, age, position of playing,
former club and rating. This function
also calls the function calculate() to
calculate the total salary of a player.

➢ void putdata()- This function displays
the details of the player like his jersey
number, name, age, position of playing,
former club, rating and wage details like
bonus, total salary.

➢ void modify()- This function inputs the
jersey number of a particular player and
modifies his data.

➢ int retjno()- This function returns the
jersey number of a particular player.

➢ void calculate()- This function
calculates the salary of a player by using
his rating and playing position.

This project includes following functions
as well:

➢ void welcome()- This function displays the
welcome screen of the program ALL STARS
FOOTBALL CLUB MANAGEMENT.

➢ void menu()- This function displays the
main menu of the program ALL STARS
FOOTBALL CLUB MANAGEMENT.

➢ void buy()- This function opens the binary
file PLAYERS.DAT and calls the function
getdata() to input details of a player.

➢ void sell()- This function takes the jersey
number of an already bought player and
delete the player’s details from the binary file
PLAYERS.DAT.

➢ void show()- This function displays the
details of all the player stored in the binary
file PLAYERS.DAT.

➢ void search()- This function takes the jersey
number of an already bought player and
displays the player’s details from the binary
file PLAYERS.DAT.

➢ void playgame()- This function generates
random scoreline, ball possession, shots
taken, fouls committed, tackles committed
and saves made against either chosen
opponent team or randomly chosen opponent
team. This function also generates match
result depending on the scoreline.
