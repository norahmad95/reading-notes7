# class 07

## Domain Modeling 

it's the process of crating a conceptual model in code for a specific problem 

* their attributes. 
* encapsulates behaviors. 
* constrain covering the problem domain.
* entity that stores data in property.
* encapsulates behaviors in method. 

**note:behaviors in method should refer to an object oriented.**

1- to define the same property between many object, using a function expression, 
in order to the variable is declared and assigned a function with parameter. 

2- when function called the data will stor in side (this.) 

3- after the constrictor function definition, the object are *instantiated* with *new* keyword properties.


### Generate a random number :

Math.random() function for just this stor of occasion.

* method can be add to constrictor function prototype.

* prototype is given *generateRandom* method which is assigned a function with tow parameter called *min*, *max* the function used both.

*Math.floor* & *Math.random* to calculate and return a random number integers between *min*, *max*.


#### briefly :


Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Here's some tips to follow when building your own domain models.

* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

* Model its attributes with a constructor function that defines and initializes properties.

* Model its behaviors with small methods that focus on doing one job well.

* Create instances using the new keyword followed by a call to a constructor function.

* Store the newly created object in a variable so you can access its properties and methods from outside.

* Use the this variable within methods so you can access the object's properties and methods from inside.


## Table 

There are several types of information that need to be displayed in a grid or table. For example: sports results, stock reports, train timetables.

#### What is the table?

A table represents information in a grid format. 

#### Basic Table Structure:

* (table) tag:
The (table) element is used to create a table. The contents of the table are written out row by row.

* (tr) tag:
The tr stands for table row. It is followed by one or more (td) elements (one for each cell in that row).

* (td) tag:
Each cell of a table is represented using a (td) element. (The td stands for table data.)

* (th) tag :
The (th) element is used just like the (td) element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.) 

#### Spanning Columns & Spanning Rows

The colspan attribute can be used on a (th) or (td) element and indicates how many columns that cell should run across.

#### Long Tables:

These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table (as you will see when you learn about CSS).

* (thead):
The headings of the table should sit inside the  element.

* (tbody):
The body should sit inside the element. 

* (tfoot):
The footer belongs inside the element. 


## creating an object:

the **new** key and the object constructor create blank object. you can then add properties and methods to the object.

## updating an object:
 
 to update the value of properties, use dot natation or square brackets. they work on objects created using literal or constructor notation to delete property, use the **delete** word.


 #### briefly:
 

 * Functions allow you to group a set of related statements together that represent a single task. 

 * Functions can take parameters information required to do their job) and may return a value. 

 * An object is a series of variables and functions that represent something from the world around you. 

 * In an object, variables are known as properties of the object; functions are known as methods of the object. 

 * Web browsers implement objects that represent both the browser window and the document loaded into the
browser window. 

* JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts. 

* Arrays and objects can be used to create complex data sets (and both can contain the other). 


