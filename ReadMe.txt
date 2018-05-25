This is a library files with certain functions:

Made during Project Works

void fullscreen(void); // Make Screen full with the simulation of key Press Alt + Enter

void gotoxy(int,int); // Help to navigate through the coordinate System in the interface

void get(char ch[]); // Takes the String and let the String stored in the Address with whitespace and no buffer Problem.

int is_leap_year(int); // Helps to detect Leap year taking the year

int len(char*); // Gives out the length of a string

void strreverse(char*); // Reverse the given string

int htc_menumaker(char* list[],int,int,int); // Takes array of Strings with Title and followed by the menu names, number of Strings in the array, x-initial position and y-initial position

void htc_password_maker(char inputpass[]); // Takes String and let String stored from user but as Password with *****

int htc_datecheck(char inputdate[]); // Checks if the given date (string) is valid or not. (format : DD.MM.YYYY)

void htc_fieldclr(int,int,int,int); // Clear the given field of interface (initial x, final x, initial y, final y)

int htc_option(char* options[],int,int,int); // Sets the options to select. Takes a Array of Strings, number of options, x-initial position and y-initial position

int htc_emailvalidator(char id[]); // Validate the given email String.

void htc_dayadder(int*,int*,int*,int); // Add the date to given Date (curr_day,curr_month,curr_year,days_to_add)

int htc_daycalculator(int,int,int,int,int,int); // Calculate the number of days gone from a date. (past_day,past_month,past_year,current_day,current_month,current_year)