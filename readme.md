# Time Entry

A customer has come to us with a problem:

"We record working hours in the format ```HH:mm-HH:mm``` which is 24H format, for example ```19:00-05:00```."

"These are in a file which has one entry per line, as in the attached times.csv file."

"From 6:30 am to 10:30 pm we have regular working hours, and from 10:30 pm to 6:30 am the next day we have night hours."

"We need to know how many night hours and how many regular working hours are worked when given an input file."

"Please note, the minimum increment that can be recorded is 30m, the maximimum is 12, and shifts start or end on the hour or every half hour."

## Task

Create a program that reads the input file and returns the total regular working hours and the total night hours.

Your solution should include unit tests.