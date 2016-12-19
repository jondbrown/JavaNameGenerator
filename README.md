# JavaNameGenerator

This is a simple Java Swing name generator that generates an output based on the input of a first and last name.
Output is based on the first letter of the first and last name. 
The first letter from each name is given an interger value which is used as the index of a corresponding 
circular array that holds out puts.

##Current Output
Currently, the generator outputs "the event that cause you to go crazy during 2016." 
The first name results is a popular person or meme from 2016 and the last name determines an event, disaster, or viral trend of 2016. 

##Implementation
You can change the possible outputs of the first and last name by changing the contents of the member arrays 
firstNames and lastNames, respectively.
Make sure to also change the denomenator of the indecies to the length of each array. (this will be fixed in next commit)
in the resultLabel.setText() of the generateButtonActionPerformed() method.

##Is this stupid?
Yes.
