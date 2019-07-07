## People

You are asked to model an application for storing data about people. You should be able to have a person and a child. The child is derived of the person. Your task is to model the application. The only constraints are:
-	People should not be able to have negative age
-	Children should not be able to have age more than 15.

•	Person – represents the base class by which all others are implemented
•	Child - represents a class which is derived by the Person.
Validate each member by throwing an ArgumentException.

## Box
You are given a geometric figure box with parameters length, width and height. Model a class Box that that can be instantiated by the same three parameters, that are mandatory.
-	All three size need to be > 0
-	Add a method named GetSurfaceArea  that computes the surface area using the formula:
2 * length * width + 2 * length * height + 2 * width * height;
-	Add a method named GetLaterarSurfaceArea  that computes and displays the surface area using the formula:
-	2 * length * height + 2 * width * height;
-	Override ToString() method to display information about this class
-	Add a method named GetVolume that computes and displays the volume using the formula:
length * width * height;
Requirements:
Encapsulate end validate the members.

## Pizza calories

A Pizza is made of dough and different toppings. 
You should model a class Pizza, which should have a name, dough and toppings as fields.
 Every type of ingredient should have its own class.
 Every ingredient has different properties: the dough can be white or wholegrain and in addition, it can be crispy, chewy or homemade. 
The toppings can be of type meat, veggies, cheese or sauce. 
Every ingredient should have a weight in grams and a method for calculating its calories according to its type. 
Calories per gram are calculated through modifiers. 
Every ingredient has 2 calories per gram as a base and a modifier that gives the exact calories. For example, a white dough has a modifier of 100, a chewy dough has a modifier of 110, which means that a white chewy dough, weighting 100 grams will have 100 * 110 * 2 = 330.00 total calories.
Your job is to model the classes in such a way that they are properly encapsulated and to provide a public method for every pizza that calculates its calories according to the ingredients it has.
1.	Create the Dough class.
It has FlourType which can be white or wholegrain.
It has BakingType  which can be crispy, chewy or homemade

Modifiers:
•	White – 150;
•	Wholegrain – 100;
•	Crispy – 90;
•	Chewy – 110;
•	Homemade – 100;

Step 2. Validate Data for the Dough Class
Change the internal logic of the Dough class by adding a data validation in the setters.
Make sure that if invalid flour type or an invalid baking technique is given a proper exception is thrown with the message "Invalid type of dough.".
The allowed weight of a dough is in the range [1..200] grams. If it is outside of this range throw an exception with the message "Dough weight should be in the range [1..200].".
Exception Messages
"Invalid type of dough."
    "Dough weight should be in the range [1..200]."
Step 3. Create a Topping Class
Next, you need to create a Topping class. It can be of four different types – meat, veggies, cheese or a sauce. A topping has a weight in grams. The calories per gram of topping are calculated depending on its type. The base calories per gram are 2. Every different type of topping has a modifier. For example, meat has a modifier of 1.2, so a meat topping will have 1.2 calories per gram (1 * 1.2). Everything that the class should expose is a getter for calories per gram. You are given the modifiers below:
Modifiers:
•	Meat – 120;
•	Veggies – 80;
•	Cheese – 150;
•	Sauce – 90;
Your task is to create the class with a proper constructor, fields, getters and setters. Make sure you use the proper access modifiers.
Step 4. Validate Data for the Topping Class
Change the internal logic of the Topping class by adding a data validation in the setter.
Make sure the topping is one of the provided types, otherwise throw a proper exception with the message "Cannot place [name of invalid argument] on top of your pizza.".

The allowed weight of a topping is in the range [1..50] grams. If it is outside of this range throw an exception with the message "[Topping type name] weight should be in the range [1..50].".
Exception Messages
•	"Cannot place [name of invalid argument] on top of your pizza."
•	"[Topping type name] weight should be in the range [1..50]."
Instantiate the class a test in your main method that reads a single dough and a topping after that and prints their calories divided by 100.

 



