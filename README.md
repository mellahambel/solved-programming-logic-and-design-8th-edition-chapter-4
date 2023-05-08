Download Link: https://assignmentchef.com/product/solved-programming-logic-and-design-8th-edition-chapter-4
<br>
Programming Logic and Design, 8th Edition

Chapter 4

Review Questions

1.       A _____ expression has one of two values: true or false.

a.        Georgian

b.       Boolean

c.        Barbarian

d.       Selective

2.        In a selection, the else clause executes _____.

a.       when the tested condition is true

b.    when the tested condition is false

c.     always

d.       only after the if clause executes

3.       The greater-than operator evaluates as true when _____.

a.        the left operand is greater than the right operand

b.       the right operand is greater than the left operand

c.        the right operand is equal to the left operand

d.       Both b and c are true.

4.        A trivial Boolean expression is one that _____.

a. is not important

b. is complicated

c. is always false

d. always has the same value

5. If x &lt;= y is true, then _____.

a. x = y is true

b. y &lt;= x is true

c. x &gt; y is false

d.  x &gt;= y is false

6. If j &lt;&gt; k is true, then _____.

a. j = k is true

b. j &gt; k might be true

c. j &lt; k might be true

d. Both b and c are true.

7. In an AND condition, the most efficient technique is to first ask the question that _____.

a. mixes constants and variables

b. uses a less-than or less-than-or-equal to operator

c. is least likely to be true

d. uses a named constant

8. If m is true and n is false, then _____.

a. m AND n is true

b. m AND n is false

c. m OR n is false

d. If m is true, then n must be true.

9. If p is true and q is false, then _____.

a. p OR q is true

b. p OR q is false

c. p AND q is true

d. p is greater than q

10. Which of the lettered choices is equivalent to the following decision?

if x &gt; 10 then

if y &gt; 10 then

output “X”

endif

endif

a.     if x &gt; 10 OR y &gt; 10 then output “X” endif

b.     if x &gt; 10 AND x &gt; y then output “X” endif

c.     if y &gt; x then output “X” endif

d.    if x &gt; 10 AND y &gt; 10 then output “X” endif

11. If conditionA is 30 percent likely to be true and conditionB is 10 percent likely to be true, then it is most efficient to test conditionA first _____.

a.     in an OR decision

b.     in an AND decision

c.     in any decision

d.     never

12. Which of the following is a poorly written, trivial Boolean expression?

a.     a &gt; b AND b &gt; c

b.     d = 10 OR d &gt; 20

c.     e &lt; f AND g &lt; 100 AND g &lt;&gt; 5

d.     h &lt; 10 AND h = 4

13. Which of the following is a trivial Boolean expression?

a.     k &lt; b AND k &gt; b

b.     m = 10 OR m = 20

c.     n &gt; 12 OR p &gt; 12

d.     q &gt; 10 AND q &lt; 19

14. Which of the following is a trivial Boolean expression?

a.     r &lt; b AND f &gt; b

b.     r = 10 OR r &lt; 0

c.     f &gt; 12 OR f &lt; 19

d.     r &gt; f AND f &lt; b

15. In the following pseudocode, what percentage raise will an employee in Department 8 receive?

if department &lt; 5 then

raise = SMALL_RAISE

else

if department &lt; 14 then

raise = MEDIUM_RAISE

else

if department &lt; 9 then

raise = BIG_RAISE

endif

endif

endif

a.     SMALL_RAISE

b.     MEDIUM_RAISE

c.     BIG_RAISE

d.     impossible to tell

16. In the following pseudocode, what percentage raise will an employee in Department 10 receive?

if department &lt; 2 then

raise = SMALL_RAISE

else

if department &lt; 6 then

raise = MEDIUM_RAISE

else

if department &lt; 10 then

raise = BIG_RAISE

endif

endif

endif

a.     SMALL_RAISE

b.     MEDIUM_RAISE

c.     BIG_RAISE

d.     impossible to tell

17. When you use a range check, you compare a variable to the _____ value in the range.

a.     lowest

b.     middle

c.     highest

d.     lowest or highest

18. If sales = 100, rate = 0.10, and expenses = 50, which of the following expressions is true?

a.     sales &gt;= expenses AND rate &lt; 1

b.     sales &lt; 200 OR expenses &lt; 100

c.     expenses = rate OR sales = rate

d.     two of the above

19. If a is true, b is true, and c is false, which of the following expressions is true?

a.     a OR b AND c

b.     a AND b AND c

c.     a AND b OR c

d.     two of the above

20. If d is true, e is false, and f is false, which of the following expressions is true?

a.     e OR f AND d

b.     f AND d OR e

c.     d OR e AND f

d.     two of the above

<strong>Programming Exercises</strong>

1.      Assume that the following variables contain the values shown:

numberBig = 300numberMedium = 100numberSmall = 5wordBig = “Elephant”wordMedium = “Horse”wordSmall = “Bug”

For each of the following Boolean expressions, decide whether the statement is true, false, or illegal.

2.      Design a flowchart or pseudocode for a program that accepts two numbers from a user and displays one of the following messages: First is larger, Second is larger, Numbers are equal.3      Design a flowchart or pseudocode for a program that accepts three numbers from a user and displays a message if the sum of any two numbers equals the third.4     Mortimer Life Insurance Company wants several lists of salesperson data. Design a flowchart or pseudocode for the following:

a. A program that accepts a salesperson’s ID number and number of polices sold in the last month, and displays the data only if the salesperson is a high performer—a person who sells more than 25 policies in the month.b. A program that accepts salesperson data continuously until a sentinel value is entered and displays a list of high performers.

c. A program that accepts salesperson data continuously until a sentinel value is entered and displays a list of salespeople who sold between 5 and 10 policies in the month.

5.       ShoppingBay is an online auction service that requires several reports. Data for each item up for auction includes ID number, item description, length of auction in days, and minimum required bid. Design a flowchart or pseudocode for the following:

a. A program that accepts data for one auctioned item. Display data for an auction only if the minimum required bid is over $100.00.b. A program that continuously accepts auction item data until a sentinel value is entered and displays all data for auctions in which the minimum required bid is over $100.00..c. A program that continuously accepts auction item data and displays data for every auction in which there are no bids yet (in other words, the minimum bid is $0.00) and the length of the auction is one day or less.d. A program that continuously accepts auction data and displays data for every auction in which the length is between 7 and 30 days inclusive.

e. A program that prompts the user for a maximum required bid, and then continuously accepts auction data and displays data for every auction in which the minimum bid is less than or equal to the amount entered by the user.

6.    The Dash Cell Phone Company charges customers a basic rate of $5 per month to send text messages. Additional rates are as follows:

·         The first 60 messages per month, regardless of message length, are included in the basic bill.

·         An additional five cents is charged for each text message after the 60th message, up to 180 messages.

·         An additional 10 cents is charged for each text message after the 180th message.

·         Federal, state, and local taxes add a total of 12 percent to each bill.

Design a flowchart or pseudocode for the following:

a. A program that accepts the following data about one customer’s messages: area code (three digits), phone number (seven digits), and number of text messages sent. Display all the data, including the month-end bill both before and after taxes are added.

b. A program that continuously accepts data about text messages until a sentinel value is entered, and displays all the details.

c. A program that continuously accepts data about text messages until a sentinel value is entered, and displays details only about customers who send more than 100 text messages.

d. A program that continuously accepts data about text messages until a sentinel value is entered, and displays details only about customers whose total bill with taxes is over $20.e. A program that prompts the user for a three-digit area code from which to select bills. Then the program continuously accepts text message data until a sentinel value is entered, and displays data only for messages sent from the specified area code.

7. The Drive-Rite Insurance Company provides automobile insurance policies for drivers. Design a flowchart or pseudocode for following:

a. A program that accepts insurance policy data, including a policy number, customer last name, customer first name, age, premium due date (month, day, and year), and number of driver accidents in the last three years. If an entered policy number is not between 1000 and 9999 inclusive, set the policy number to 0. If the month is not between 1 and 12 inclusive, or the day is not correct for the month (for example, not between 1 and 31 for January or 1 and 29 for February), set the month, day, and year to 0. Display the policy data after any revisions have been made.

b. A program that continuously accepts policy holders’ data until a sentinel value has been entered, and displays the data for any policy holder over 35 years old.

c. A program that continuously accepts policy holders’ data until a sentinel value has been entered, and displays the data for any policy holder who is at least 21 years old.

d. A program that continuously accepts policy holders’ data and displays the data for any policy holder no more than 30 years old.

e. A program that continuously accepts policy holders’ data and displays the data for any policy holder whose premium is due no later than March 15 any year.

f. A program that continuously accepts policy holders’ data and displays the data for any policy holder whose premium is due up to and including January 1, 2016.

g. A program that continuously accepts policy holders’ data and displays the data for any policy holder whose premium is due by April 27, 2015.h. A program that continuously accepts policy holders’ data and displays the data for anyone who has a policy number between 1000 and 4000 inclusive, whose policy comes due in April or May of any year, and who has had fewer than three accidents

8.      The Barking Lot is a dog day care center. Design a flowchart or pseudocode for following:

a. A program that accepts data for an ID number of a dog’s owner, and the name, breed, age, and weight of the dog. Display a bill containing all the input data as well as the weekly day care fee, which is $55 for dogs under 15 pounds, $75 for dogs from 15 to 30 pounds inclusive, $105 for dogs from 31 to 80 pounds inclusive, and $125 for dogs over 80 pounds.

b. A program that continuously accepts dogs’ data until a sentinel value is entered, and displays billing data for each dog.c. A program that continuously accepts dogs’ data until a sentinel value is entered, and displays billing data for dog owners who owe more than $100.

d. A program that continuously accepts dogs’ data until a sentinel value is entered, and displays billing data for dogs who weigh less than 20 pounds or more than 100 pounds.

9.   <strong>   Mark Daniels is a carpenter who creates personalized house signs. He wants an application to compute the price of any sign a customer orders, based on the following factors:</strong>

·         The minimum charge for all signs is $30.

·         If the sign is made of oak, add $15. No charge is added for pine.

·         The first six letters or numbers are included in the minimum charge; there is a $3 charge for each additional character.

·         Black or white characters are included in the minimum charge; there is an additional $12 charge for gold-leaf lettering.

Design a flowchart or pseudocode for following:

a. A program that accepts data for an order number, customer name, wood type, number of characters, and color of characters. Display all the entered data and the final price for the sign.

b. A program that continuously accepts sign order data and displays all the relevant information for oak signs with five white letters.

c. A program that continuously accepts sign order data and displays all the relevant information for pine signs with gold-leaf lettering and more than 10 characters.

10.       Black Dot Printing is attempting to organize carpools to save energy. Each input record contains an employee’s name and town of residence. Ten percent of the company’s employees live in Wonder Lake; 30 percent live in the adjacent town of Woodstock. Black Dot wants to encourage employees who live in either town to drive to work together. Design a flowchart or pseudocode for the following:

a. A program that accepts an employee’s data and displays it with a message that indicates whether the employee is a candidate for the carpool (because he lives in one of the two cities).

b. A program that continuously accepts employee data until a sentinel value is entered, and displays a list of all employees who are carpool candidates. Make sure the decision-making process is as efficient as possible.

c. A program that continuously accepts employee data until a sentinel value is entered, and displays a list of all employees who are ineligible to carpool because they do not live in either Wonder Lake or Woodstock. Make sure the decision-making process is as efficient as possible.

11.  Amanda Cho, a supervisor in a retail clothing store, wants to acknowledge high-achieving salespeople. Design a flowchart or pseudocode for the following:

a. A program that continuously accepts each salesperson’s first and last names, the number of shifts worked in a month, number of transactions completed this month, and the dollar value of those transactions. Display each salesperson’s name with a productivity score, which is computed by first dividing dollars by transactions and dividing the result by shifts worked. Display three asterisks after the productivity score if it is 50 or higher.

b. A program that accepts each salesperson’s data and displays the name and a bonus amount. The bonuses will be distributed as follows:

·         If the productivity score is 30 or less, the bonus is $25.

·         If the productivity score is 31 or more and less than 80, the bonus is $50.

·         If the productivity score is 80 or more and less than 200, the bonus is $100.

·         If the productivity score is 200 or higher, the bonus is $200.

c. Modify Exercise 11b to reflect the following new fact, and have the program execute as efficiently as possible:

·         Sixty percent of employees have a productivity score greater than 200.

<strong>Performing Maintenance</strong>

A file named MAINTENANCE04-01.jpg is included with your downloadable student files. Assume that this program is a working program in your organization and that it needs modifications as described in the comments (lines that begin with two slashes) at the beginning of the file. Your job is to alter the program to meet the new specifications

<strong>Find the Bugs</strong>

1.      Your downloadable files for Chapter 4 include DEBUG04-01.txt, DEBUG04-02.txt, and DEBUG04-03.txt. Each file starts with some comments that describe the problem. Comments are lines that begin with two slashes (//). Following the comments, each file contains pseudocode that has one or more bugs you must find and correct.2    Your downloadable files for Chapter 4 include a file named DEBUG04-04.jpg that contains a flowchart with syntax and/or logical errors. Examine the flowchart and then find and correct all the bugs.

<strong>Game Zone</strong>

1.      In Chapter 2, you learned that many programming languages allow you to generate a random number between 1 and a limiting value named limit by using a statement similar to randomNumber = random(limit). Create the logic for a guessing game in which the application generates a random number and the player tries to guess it. Display a message indicating whether the player’s guess was correct, too high, or too low. (After you finish Chapter 5, you will be able to modify the application so that the user can continue to guess until the correct answer is entered.)

2      Create a lottery game application. Generate three random numbers, each between 0 and 9. Allow the user to guess three numbers. Compare each of the user’s guesses to the three random numbers and display a message that includes the user’s guess, the randomly determined three digits, and the amount of money the user has won, as shown in Figure 4-24.

Matching NumbersAward ($)Any one matching10Two matching100Three matching, not in order1000Three matching in exact order1,000,000No matches0

Make certain that your application accommodates repeating digits. For example, if a user guesses 1, 2, and 3, and the randomly generated digits are 1, 1, and 1, do not give the user credit for three correct guesses—just one.

<strong>Up for Discussion</strong>

1.      Computer programs can be used to make decisions about your insurability as well as the rates you will be charged for health and life insurance policies. For example, certain preexisting conditions may raise your insurance premiums considerably. Is it ethical for insurance companies to access your health records and then make insurance decisions about you? Explain your answer.2.      Job applications are sometimes screened by software that makes decisions about a candidate’s suitability based on keywords in the applications. Is such screening fair to applicants? Explain your answer.3.      Medical facilities often have more patients waiting for organ transplants than there are available organs. Suppose you have been asked to write a computer program that selects which of several candidates should receive an available organ. What data would you want on file to be able to use in your program, and what decisions would you make based on the data? What data do you think others might use that you would choose not to use?