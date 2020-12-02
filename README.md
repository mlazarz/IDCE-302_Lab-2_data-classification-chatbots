# Lab 2 - Data Classification & Chatbots

## Script 1 - Classifying Temperature Data

This script classifies a temperature in Fahrenheit that is inserted by the user into four categories, Hot, Warm, Cool, and Cold.  The following is the flow of this script:

1.  The user is asked the temperature in degrees Fahrenheit.  A variable called temp is assigned to a user input where the temperature is inserted.  The input value is converted to a float value.
2.  A function called feelTemp is defined with the temp value as the parameter.
3.  If the input temperature is greater than or equal to 100 degrees, the statement "It is hot." is printed. This indicates that the temperature is in the "Hot" class.
4.  If the input temperature is less than 100 and greater than or equal to 70 degrees, the statement "It is warm." is printed. This indicates that the temperature is in the "Warm" class.
5.  If the input temperature is less than 70 and greater than or equal to 32 degrees, the statement "It is cool." is printed. This indicates that the temperature is in the "Cool" class.
6.  If the input temperature is any other value, the statement "It is cold" is printed.  This indicates that the temperature is in the "Cold" class.  All other values at this point in the script are all values less than 32 degrees.
7.  The function feelTemp is called in the final line of this script which fills the temp parameter with the user input.

## Script 2 - Create your first chatbot!

A Chatbot is an interactive script that asks the user questions and answers based on their input.  In Script 2, the Chatbot is 30 years old, lives in Vermont, and is named Mitch.  The Chatbot asks the user their name, age, and location through a series of functions with if, elif, else statements.  The following is the flow of the script:

* The Chatbot first greets the user with "Hello there, what is your name?" which has the user input their name. This input is assigned to the name variable.
1. A function chat0 is defined with a parameter, name.
2. If the user responds with "Mitch", the statement "Hey, that is my name too!" is printed.
3. If the user responds with any other name, the statement "Nice to meet you, *name*" is printed with *name* being the user input.
4. The function chat0 is called with the user input, name, filling the parameter.

* The Chatbot then asks "How old are you?" which has the user input their age.  This input is assigned to the age variable.  This input is converted to an integer.
1. A function chat1 is defined with a parameter, age.
2. If the user responds with 30.  The Chatbot responds with "No way! Me too!".
3. If the user is older than 30.  The age difference between the user and 30 is calculated and the statement "You are *blank* years older than me" is printed.  *blank* is the output of the calculation *age*-30.
4. If the user is younger than 30.  The age difference between the user and 30 is calculated and the statement "You are *blank* years younger than me" is printed.  *blank* is the output of the calculation 30-*age*.
5. The function chat1 is called with the user input, age, filling the parameter.

* The Chatbot lastly asks the user "Where do you live?" which has the user input their location.  This input is assigned to the loc variable.
1. A function chat2 is defined with the parameter, loc.
2. If the user responds with "Vermont" and has responded with "Mitch" as their name and 30 as their age, the statement "Looks like I am talking to myself again" is printed.  This indicates that it is a test and the creator is running the script.
3. If the user responds with "Worcester", the Chatbot prints "Clark University is a great school!".
4. If the user responds with any other location, the statement "I hear it is beautiful this time of year in *loc*!".  *loc* is the user input for the loc variable.
5. The function chat2 is called with the user input, loc, filling the parameter.

## Script troubleshooting

I did not have any major issues with writing these scripts.  During the Chatbot exercise, in the final function, I initially used *or* instead of *and* in my first if statement and had to go back and correct my logic.

##### Creator:  Mitchell Lazarz
##### Date: September 11, 2020
##### IDCE 302
