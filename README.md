# Transmax_Programming_Test
Requirements – Programming test for all levels
Must be completed in C++ or C# language

Write console app that:

 Takes as a parameter a string that represents a text file containing a list of names, and their

scores

 Orders the names by their score. If scores are the same, order by their last name followed by

first name

 Creates a new text file called <input-file-name>-graded.txt with the list of sorted score and

names.

For example, if the input file contains:

BUNDY, TERESSA, 88

SMITH, ALLAN, 70

KING, MADISON, 88

SMITH, FRANCIS, 85

Then the output file would be:

BUNDY, TERESSA, 88

KING, MADISON, 88

SMITH, FRANCIS, 85

SMITH, ALLAN, 70

2

Example of console execution

grade-scores c:\names.txt

BUNDY, TERESSA, 88

KING, MADISON, 88

SMITH, FRANCIS, 85

SMITH, ALLAN, 70

Finished: created names-graded.txt

Assessment

 Your solution should meet the above requirements.

 Unit tests should exist.

 The solution should be in github or bitbucket.

 Bonus points if tests are run automatically on checkin via a CI service like

http://www.appveyor.com/.
