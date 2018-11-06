# OOP
## 1. 
Realizati o aplicatie consola in care sa modelati regnul animal tinand cont de urmatoarele afirmatii:
- orice vietate este un animal
- orice animal are un nume
- exista mai multe categorii de animale: mamifere, pasari, reptile, pesti, insecte
- indiferent de categoria din care fac parte, animalele se deplaseaza: zboara, merg, inoata, se tarasc.
- in functie de modul in care se deplaseaza au o viteza maxima de deplasare
- exista animale care pot sa inoate si sa mearga (Ornitoric) sau care pot sa inoate, sa zboara si sa mearga (Rata salbatica)
- nu orice animal care zboara e o pasare - liliacul este un mamifer care zboara. Si nu orice pasare zboara - strutul este o pasare dar nu zboara

## 2.
Model the Rabbit class knowing that:
- a rabbit can have Blue, Red or Black eyes
- a rabbit's fur can be white, brown, black or grey
- it has a gender
- has a birth date, and based on that you should be able to see how old the rabbit is
- we also know that a rabbit is a mammal that moves, sleeps and eats certain foods

## 3 
Model the Product class knowing that:
- a product has a weight
- has a name
- a production date
- an expiration date
- it has a producer
- and it can be in one of categories : Dairy, Fruit, Beverages, Bread
- we also knoow that it expires differently based on the category it belongs to:
   1. fruits expire in 2 days
   2. beverages expire in 3 years
   3. dairy expire in 1 week
   4. bread expires in 4 days
   
   
   ## Alergies
   
Given a person's allergy score, determine whether or not they're allergic to a given item, and their full list of allergies.

An allergy test produces a single numeric score which contains the information about all the allergies the person has (that they were tested for).

The list of items (and their value) that were tested are:

eggs (1)

peanuts (2)

shellfish (4)

strawberries (8)

tomatoes (16)

chocolate (32)

pollen (64)

cats (128)

So if Tom is allergic to peanuts and chocolate, he gets a score of 34 (2 - from peanuts + 32 from chocholate)

Now, given just that score of 34, your program should be able to say:

Whether Tom is allergic to any one of those allergens listed above.
All the allergens Tom is allergic to.
Note: a given score may include allergens not listed above (i.e. allergens that score 256, 512, 1024, etc.). 
Your program should ignore those components of the score. 
For example, if the allergy score is 257, your program should only report the eggs (1) allergy.

 #
