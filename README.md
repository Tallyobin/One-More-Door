PROGRAMMING QUESTIONS (2 QUESTIONS, 25 MARKS)
Instruction: Answer ALL questions.

Question 1
Write a C++ program to do the following:
A. Create a class named Movie.
B. The class Movie should have data members to contain basic information of a movie. The data members of the class will include title (string), year (integer), income_profit (double) and BoxOfficeStatus (string).
C. Include in the class definition a default constructor that will ask the user to enter the data for the first three data members.
D. The value of income_profit should determine the value for data member
BoxOfficeStatus. If income_profit is more than 50 million then the
movies is a Box Office, otherwise Flop. Your class should also include a
report() method to generate a report as shown in Figure 1 and 2.
E. Include getBoxOfficeStatus() method to complete your task in D.
F. Include main program that will instantiate an object of the class Movie.
Figure 1

Enter the Title Movie: The Northman
Enter the Year of Movie Launch: 2022
Enter the Profit of the Movie (USD): 59633110
Movie tittled The Northman produced in the year 2022 is a Box Office

Figure 2

Enter the Title Movie: Puss in Boots
Enter the Year of Movie Launch: 2012
Enter the Profit of the Movie (USD): 4009554
Movie tittled Puss in Boots produced in the year 2012 is a Flop

[15.5 marks]


Question 2
Write a C++ program to do the following:
A. Open and process an input file named NumData.txt that contains integer values
as shown in Figure 3.
B. Read each value in the file and for values that are equal or less than 100 you must
store in in an output file name BigData.txt as shown in Figure 4. You are
supposed to do this until an end of file is encounters.
C. You must also keep track of the largest number and count of how many values that
are below 100 at the end of process display the output in file name BigData.txt
as shown in Figure 4.

104
50
25
364
12
142
46
14
853
12

Figure 3

There are 6 values that are below 100 and DISCARDED.
The largest number read is : 853

Figure 4
[9.5 marks]


























SECTION C: PROGRAMMING QUESTIONS (2 QUESTIONS, 30 MARKS)
Instruction: Answer ALL questions. Please use software or online tool to answer
it. Submit your file codes (.cpp) for Question 1 and 2. You also need to submit all
the related text files (.txt) for Question 2.
Question 1
Write a program for Jane Austen’s book club to do the following:
1. Declare and store their member’s information including his/her name, age and
member’s id.
Structure Name: Person
Structure Members:
a) char name[20]
b) int age
c) int memberid
2. Get the inputs from user for the member’s information.
3. Print out the details of the entered information.
4. You may refer to the sample output in Figure 1 below:

++Welcome to Jane Austen's BookClub++
Please enter your full name: sarah
Please enter your age: 18
Please enter your member id: 1122
Displaying Information:
Hello, sarah and welcome to Jane Austen's bookclub!
You are 18 years old fan who loves to read Jane Austen's novel!
To double confirmed, your member id is:1122
Stay in touch for more updates on Jane Austen's classics!

Figure 1
[15 marks]


Question 2
Assume a text file called integer.txt as in Figure 2 has been created and has the
same path as our program. Your task is to read the values from the integer.txt
input file and count the number of odd numbers on each line of the file and the total of
summation of odd number. Do this for every line of data in the input file until EOF is
encountered. Save the content of the total count of odd numbers and also the summation
of odd numbers in output file named odd.txt as shown in Figure 3. Display the total
of all numbers on console as shown in Figure 4.

98
150
54
23
702
520
15

Figure 2

Total of odd number : 2
Summation of odd number: 38

Figure 3

The total of all numbers: 1562

Figure 4
[15 marks]

