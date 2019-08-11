# ThoughtWorks Home Test
# Problem
### Merchant's Guide to the Galaxy
 
You decided to give up on earth after the latest financial collapse left 99.99% of the earth's population with 0.01% of the wealth. Luckily, with the scant sum of money that is left in your account, you are able to afford to rent a spaceship, leave earth, and fly all over the galaxy to sell common metals and dirt (which apparently is worth a lot).

Buying and selling over the galaxy requires you to convert numbers and units, and you decided to write a program to help you.

The numbers used for intergalactic transactions follows similar convention to the roman numerals and you have painstakingly collected the appropriate translation between them.
# Project Structure Brief
* Credits: Processing credit data.
* Input: Convert input to command stream. Standard output and files are supported.
* Processor: Processing command parsing, execution. Can enable or disable a command processor by annotation.
* Roman: Encapsulate roman numerals related functions, such as roman numerals cover to arabic numerals.
* Units: Processing galaxy numerals parsing and cover it to roman numerals.
* Utility: Toolkit functions.
# How to Run
- Open Terminal or Console
- Unzip the zip package.
- Enter the zip folder directory: "/"
- Run "mvn package" to build the jar package. In the end, you will see the location of the jar package.
- Run "java -jar ${the jar package file path}" or "java -jar ${the jar package file path} -f ${intput file path}" to execution this program.The first way the program will interact through stdin; The other way the program will use the file you specified as input.
