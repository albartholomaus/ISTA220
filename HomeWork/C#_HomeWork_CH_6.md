# **Turn in:** **C#_HomeWork_CH_6**
### **Name:** *Anthony Bartholomaus*
### Professor: *Mr. Carter*

1.  ##### What is an exception?
- *Error Handling.*
---
2.  ##### What happens in a try block if the program executes without errors?
- *The code attempts to handle to execute all the statements.*
---
3.  ##### How does the catch mechanism work for unhandled exceptions?
- *The try block will attempt to locate the handler, if none then the calling method will immediately exit, then return to the caller.*
---
4.  ##### What happens in a program if an exception block fails to handle a particular error?
- *•	The program will terminate with an unhandled exception.*
---
5.  ##### What is the parent class for all exceptions? How does this work?
- *Exception, it is broken down into inheritance hierarchies p.137*
---
6.  ##### How do you determine the type of an error?
- *It can be determined in the catch (parentheses).*
---
7.  ##### What is the purpose of integer checking?
- *It is to ensure program integrity, to have better performance.*
---
8.  ##### What is the range of values than a signed Int32 type can contain? State the lowest value and the highest value.
- *-2,147,483,648 to 2,147,483,647*
---
9.  ##### What is the range of values than an unsigned Int32 type can contain? State the lowest value and the highest value. What is the difference between a signed integer and an unsigned integer? Can signed integers and unsigned integers represent the same amount of numbers
- *0 to 4,294,967,295, the represent the same amount of numbers and occupy the same byte space.*
---
10. ##### What does the finally block do?
- *It is to ensure every line of code is run.*
---
11. ##### (Thought question) When would you not use a finally block in a try/catch construction?
- *•	It is for resource management. When running an exception, the line that threw the exception is skip and that could a local resource needed for a particular function or method. The final block would ensure that it is ran so the rest of the program could run effectively.*
---
