# EmailAccountGenerator

Email Generator Project

Create a program that asks a user’s to select options .Option 1 allows the user to create a new email account it takes the first two initials of the firstname and combines it with the last name. It also adds on “@google.com”to the end. Option 2 creates a for loop that loops however many times the users input equals.

Top Level design

1.	Welcome user to the program <br />
1.1	Ask the user to enter their name <br />
1.2	Ask the user to select option 1 or option 2 <br />

Detailed Design 

2.1	Create a variable to hold users name <br />
2.2	Create function  to get the users name <br />
2.3	Create a method to select options1 or option 2 <br />
2.4	Menu method 
2.4.1	Pass in users name <br />
2.4.2	Create a scanner <br />
2.4.3	Create a Boolean variable set it to false <br />
2.4.4	Print Welcome to menu name please select option1,option2 or done <br />
2.4.5	Start do loop <br />
2.4.5.1	Print Enter number <br />
2.4.5.2	Case 1 : select option 1 <br />
2.4.5.3	Case 2: select option 2<br />
2.4.5.4	Case 3: done = true <br />
2.4.5.5	End while not done<br />

3.1	Option 1 
3.2	Pass in username <br />
3.3	Print you have chosen option 1 <br />
3.4	Ask them to enter their first and last name <br />
3.5	Create a scanner <br />
3.6	Pass the first and last name to a method called createEmail(string name)<br />

4.1 createEmail (string name)<br />
4.2 create a substring of name taking the first two initials <br />
4.3 create two variables one to hold the first string and the other to hold the last name.<br />
4.4 use the indexof method to separate the strings by the space in the word.<br />
4.5 create a variable to hold the combined strings. <br />
4.6 print out the new string with the users name and email @google.com.<br />
