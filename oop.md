# OOP
### Descriptions
these problems have as a goal to model the requested functionality, but also to provide the simplest and cleanest implementations.
Keep an eye on naming and data types

## 1. 
Make an application where to model a animals keeping in mind that:
- any kind you model is an animal
- any animal has a name
- there are multiple animal categories like : mammals, fish, birds, reptile, insects
- no matter the category, animal are : flying, walking, swim or crawl.
- depending on the way they move, they have a maximum speed.
- there are animals that can swim and walk (Platypus)
- there are animals that can swim, fly and walk (Wild Duck)
- Not any animal that can fly is a bird, the bat is a mammal that flys, and not evey bird flys - the ostrich is a bird but doesn't fly 

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

- eggs (1)

- peanuts (2)

- shellfish (4)

- strawberries (8)

- tomatoes (16)

- chocolate (32)

- pollen (64)

- cats (128)

So if Tom is allergic to peanuts and chocolate, he gets a score of 34 (2 - from peanuts + 32 from chocholate)

Now, given just that score of 34, your program should be able to say:

Whether Tom is allergic to any one of those allergens listed above.

All the allergens Tom is allergic to.

Note: a given score may include allergens not listed above (i.e. allergens that score 256, 512, 1024, etc.). 
Your program should ignore those components of the score. 

For example, if the allergy score is 257, your program should only report the eggs (1) allergy.

 ## Acronym
Write a class with all the logic needed to convert a phrase to its acronym.

Techies love their TLA (Three Letter Acronyms)!

Help generate some jargon by writing a program that converts a long name like Portable Network Graphics to its acronym (PNG).

## BankAccount
Simulate a bank account supporting opening/closing, withdrawals, and deposits of money.

It should be possible to close an account; operations against a closed account must fail.

Remember you are working with money so you should use an appropriate data type for it.

## Pig Latin
Implement a program that translates from English to Pig Latin.

Pig Latin is a made-up children's language that's intended to be confusing. It obeys a few simple rules (below), but when it's spoken quickly it's really difficult for non-children (and non-native speakers) to understand.

   - Rule 1: If a word begins with a vowel sound, add an "ay" sound to the end of the word.
   - Rule 2: If a word begins with a consonant sound, move it to the end of the word, and then add an "ay" sound to the end of the word.
There are a few more rules for edge cases, and there are regional variants too.

See http://en.wikipedia.org/wiki/Pig_latin for more details.

## RainDrops

Convert a number to a string, the contents of which depend on the number's factors.

- If the number has 3 as a factor, output 'Pling'.
- If the number has 5 as a factor, output 'Plang'.
- If the number has 7 as a factor, output 'Plong'.
- If the number does not have 3, 5, or 7 as a factor, just pass the number's digits straight through.

Examples

28's factors are 1, 2, 4, 7, 14, 28.

In raindrop-speak, this would be a simple "Plong".

30's factors are 1, 2, 3, 5, 6, 10, 15, 30.

In raindrop-speak, this would be a "PlingPlang".

34 has four factors: 1, 2, 17, and 34.

In raindrop-speak, this would be "34".

## Zoo
Model a ZOO keeping in mind that:
-	A zoo has a name and a list of animals
-	At a zoo they can bring new animals and transfer animals to new zoos
-	At a zoo the animals are daily fed with their favorite food, and each animal eats what it loves to eat. 
-	Each animal knows to eat by itself, and not all animals of the same type prefer the same type of food. Eg; a horse prefers carrots, and another horse prefers apples
