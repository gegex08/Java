Notes For 03/28/2024

Definitions
Computer Gigahertz nano seconds
Increase processor
Difference between a database and spreadsheet
Database breaks large amount of data and sorts it
KeyWord Private can only be manipulated within the class
KeyWord this allows us to distinguish between object and local method
Every object for string needs toString()
If you create a new method to replace the default toSting it is called OverRIDE 
Security Feature JVM
Inhertence
Method Signature 
Overload - you have to use the same signature
Instantiating 
Set Method is called a mutator method tipically changes an objects state
Get Method
Multiple Classes
Enumeration using acronyms make a sort of your own constants
Java collects garbage collection
Static does not require an object and it is a class variable ex video game different players but in same course
Attributes ex hours min sec
Final last time you are using code

Code Quiz
Two dimensional array nested for loop to print array
Print Even or Odd Numbers
Call method that takes in 2 dim array print arrays then 
if number num %2 !=0 print “odd” print a 0

04/02/28
Java goes back to garbage and retrieves 
.this ----> attribute of an object
overload ----> method name but parameters are different
composition ----> objects can be used using different objects another class that supports to build that object
finalized-----> to be reclaimed
Command Line Input--->
Pass by Reference---->

gliffy.com/
Inheritance----> (to not have to repeat all methods/fields) (SECURITY) passed down Make more sub classes that extends the super class, programming to the specific, 
super class does not have access to sub class but sub class has access to super class
program to the specific 

least priveledge---->
polymorpsh--->1 method many forms  
Abstract Class---> interfaces
extended is a keyword to let us know that we are using inheretance
static- class controls it

keyword extend class before is sub the class after is super class
extends from blue print

super---->base plus commissionemployee
override means overrides method in super class
earnings method from super class

make yourself a baseplus commission employee on homework.
3 set of code

last one only turn PayrollSystemTest

Change  a value of a given index of an array after it is created

Inheretence allowing subclass object to only do its job.
Polymorphsm 1 method many forms(programming to the general)

Abstract method(super class)--->method without a body but it dictates the interface(can not create any object from it)
forces class to become abstract no implementation can not build methods

Concrete classes are not abstract which means you can build an object from it
extends---polymorphsm must have inherentence subclasses

ToString()
private attribute can only be acessed in class
protected a subclass can access from a superclass use a pound
subclass must have earnings method
extends

keeps the code;
Execption handling owner data
Concrete Abstract Polymorphism Extend Ingeretence

integrity trustworthy
inheretence writing to the specific
////////////////////////////////////
GUI
Nimbus look and field
event is clicking computer and it does something
userinteraction 

Operating system : usability
command prompt GUI

load, exchange in processor, how many applications you have going on.
Activity stack read out or dump
Operating system of saying it ended

Swing
Title bar, menu, 
interface
Nimbus Field

API Application Programming Interface
Class Hieararchy

Polygonf Gradients Texture
Pixels dots on screen
Printer only printed from the upper left corner because it is from the root the tree

Program to use mouse from 0 on the top

Lecture 01-30-2024
A compiler runs faster Ex JAVA
Interpreted runs slower Ex Python
Moore’s law computer is faster, combability is greater, cheaper
Data Hierarchy 1s and 0’s
Field names characters and words
Database
Operating systems user interface set of code is moved from hard drive to RAM
Task Manager CTRL+Alt+Del %processed Percentage ect.
Lynux Mac OS Windos Dos IOS Android(Chromebook)

Different Programming Languages
Fortran Formula translator
Cobol Common Business Oriented Language
Pascal structured programming
Ada based on Pascal
Objective C
Visual C#
PHP interface language website
Never get interface in database
Perl
Python
JA
Ruby on Rails Graphic unique mix
Java




Chapter 1.8
Java founded 1991
Libraries Classes faces packages
Scanner packages –> methods 
Abstraction level-hiding details
API Application Programming Interfaces

Chapter 1.9
Edit Phases -Text File .java file
Compile- turns   .java file ->.class file
		Javac file1.java
Loads
Verify - will not corrupt host computer
Execute- run file Java machine is invoked
			Java file1
Go to Command Prompt
Change directory – cd
Compile command javac filename.java
Executes java filename

-Compile Error crashes
-Syntax
-Logic
-Runtime crashes



Polymorphisms
Inheritance super class subclass
Exception handling
Concrete class
Abstract class or method
Big Oh time complexity (efficiency) how long does it take to run application number of processes number of loops how long it takes to run algorithm amount of work vs amount of data
Recursion function calling itself method that feeds itself another form of iteration best for sorting apps
Sort Data to make it easier to find things
All go together 
Introduction to Data Structure
Step linear algorithm Log 2 Base function cutting number in half
-64
-32
-16
-8
-4
-2
Log264=6
Log2100=6.7
-100
-50
-25
-13
-6
-3
-1
Hash table log base of 1----Takes in a piece of data and takes it to the given address


Homework 10
Part1
________________________________________________________________________________

Check if input string is palindrome
Take in a string 
Save
Reverse
Store it in another string
And output
If first character from array == last character from the array
Reversing decrementing using 4loop
Output Original String, reverse string, 
 

Part 2
Use Try and catch block from previous code
Encryption
plainText->Key=>CipherText
cipherText->Key=> plaintext
take an array input an array of characters
ascii values American standard code for information interchange 256 in Unicode 128 in ascii
toString() to char=’’
change int add key value and change back to char
Capital letters to lower case are 32 numbers of difference
Simple cipher 
Registry (try not to use it)
Rot13 
Logic if indx is greater than 25 
Mod 26
Shift to wrap around
When you get to 90
If you get an array of characters
A	B	C	.	.	.	.	.	Y	Z
0		1	2								24	25
A			z	A	.	.	.	Y	Z
0				25		26						50
Mod key you will never in next block= wrap around
 
Part 3 _____________________________________________________________________________________
Use the 3 files
Open File
Load File
Read A line at a time
Split Method takes in string and give you a number of words divide number 3
If it gives you a number of words
Split by period exclamation and question marks
Read it in one line
Input number of words number of syllables
Create my own my file to test that it works


 
Tokenizing
Reference type must point to same location and memory
S1 Hello

S2 GoodBye

Gives you difference in the ASCII value 
Gello
Goodbye
0
Gollo
Goobye
11
.equals ----boolean
.CompareTO-------- gives you difference

  _ _____________________________________________________________________________________
Array string is immutable by length
Array of characters cannot be changed
Objects to use true or false
Compare to primitive types Booleans, byte,
Reference to check if its in same memory location







SI= “Hi there”;
S2= ”hi there”;
S1.compareTo(S2);----32
S2.compareTo(S1);---32

SI= “hi there”;
S2= ”hi there”;
S1.compareTo(S2);---0
S2.compareTo(S1);---0

SI= “hi there”;
S2= ”Hi There”;
S1.compareTo(S2);---32
S2.compareTo(S1);----32
The first time there is a difference it will give you an output.

File you are getting from harddrive, printwriter
open using file reader
buffer to manipulate
filewriter

Applications look in to local directory first


Coding Questions multiple choice questions bug Coding q Gradebook and tokenizing variation of these two problems a 2 dim array of grades not 2 classes but multiple methods

Recursion calls itself
1 termination condiition
2 call clone
3 Move towards Condition

while loop
identify
increment
Stack is an array but with rules first in is last one out last one in is the first one out

Big OH---------RElationship amount of work for the amount of data (efficiency )

Actions
Time measure of work vs amount of Data

Big Oh N Square(worst case)
Insertion:Example 1698 compare 1628 swaps
Bubble:5328 campares vs 1516 swaps O(N^2)
quick: 523 compares vs 117 swaps nlogn

That is why we use:
relational database instead of spread sheets

ologN linear search
ON 
![image](https://github.com/gegex08/Java/assets/16494040/0e77de54-7cbc-4c91-a601-2eae441cf049)

 
	
	
	
Main()	isPal(“ZEROREZ”)

Method Boolean inPal(String s)
Terminating Conditions if(s.lenght =0||s.lenght()==1)true, if(s.lenght =0||s.lenght()-11)true
![image](https://github.com/gegex08/Java/assets/16494040/d9eae37d-7e92-45bb-894c-696292de5068)

