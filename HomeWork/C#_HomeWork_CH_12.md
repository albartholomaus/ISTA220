# **Turn in:** **C#_HomeWork_CH_12**
### **Name:** *Anthony Bartholomaus*
### Professor: *Mr. Carter*

1. #### How does inheritance promote the principle of don’t repeat yourself (DRY)?
- *helps with maintenance issues.*
---
2. #### What is the syntax of a derived class that inherits from a base class?
- *class horse: Mammal.*
---
3. #### Do all user defined types (classes and structs) inherit from some base class? If so, what is it?
- *yes, system.object.*
---
4. #### What happens if you do not have a default constructor in a base class when creating a derived class?
- *silently insert a call to the base class’s default constructor before executing the code in the
derived-class constructor.*
---
5. #### Can you assign a variable of a derived class to another variable of its base class? Why or why not?
- *.*
---
6. #### Can you assign a variable of a derived class to another variable of a derived class of its base class? Why or why not?
- *no, it is another type.*
---
7. #### Can you assign a variable of a base class to another variable of a derived class? Why or why not?
- *yes, as it is apart of the base class it can be assigned, use the as is or cast to check and see if it is apart of the class.*
---
8. #### Under what circumstances would you want to use the new keyword when defining a method in a derived class?
- *occurs. It just turns the warning off.*
---
9. #### What is a virtual method? Why would you want to define a virtual method?
- *is intended to be overridden. To define your own method of the same name but does different stuff.
public virtual string ToString()*
---
10. #### What does override do? Why does it do it?
- *derived class can use the override keyword to declare
another implementation of that method.  public override string ToString()*
---
11. #### HOW do you define an extension type?
- *this keyword.*
---
12. #### WHY do you define an extension type?
- *An added feature to an existing class that .*
---
13. #### (Not in book) Explain the Liskov substitution principle.
- *The object of the derived class should be able to replace an object of the base class without bringing any errors in the system or moding the behavior.*
---
