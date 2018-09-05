- Make observations and then generalize from specific observations to a more general concept. 
- After accumulate enough related general concepts -> then derive principles.
- Once understand the principles, we are prepared to apply the principles in novel ways. 

# Cohesion
- Conhesion - how focused a software module is
- A module is a clump of software (ex: a block of code, a method, a class or a package)
- Focus - means how well does each subcomponent of the module relate to the overall purpose of the module
    * High cohesion (all pieces of the module contribute to the overall prpose)
    * Low cohesion (few of the subcomponents of the module contribute to the module's purpose)

- Larry Constantine - identified cohesion as a software design principle in 1975 - incldue 7 variations of cohension ordered from low (less desirable) to high cohesion (more desirable):
    * Coincidental cohesion
    * Logical cohesion
    * Temporal cohesion
    * Procedural cohesion
    * Communicational cohesion
    * Sequential cohesion
    * Functional cohesion

## Coincidental cohesion
- occurs when the subcomponents of a module have virtually nothing in common
- Ex: a junk drawer in a kitchen might have a screwdriver, miscellaneous keys, a stick of chewing gum, tape, coupon, etc. => they have nothing in common except that they all reside in the junk drawer - because the owner didn't know what else to do with them. 
- Ex in code: a "Main" class that contains the main method of a program as well as all other static methods the program may use. 
- Inexperienced programmers often create these classes more by accident than on purpose. They give little thought to the organization => so the coincidental cohesive module just sort of emerges from the lack of organized thinking. 

## Logical Cohesion
- are those modules that have subcomponents that the developer grouped together because of the subcomponents have the same categorizaiton. 
- Ex: a pantry - 1st shelve for drinks, 2nd shelve for ethnic foods, 3rd shelve for canned vegetables.
- Logical cohesion may help one find an item or subcomponent, the items or subcomponents do not work together for a single purpose. 

## Temporal Cohesion
- Temporal (time-related) - are those modules whose subcomponents reflect usage at about the same time. 
- Ex: a person grabs all the things at the same time and the person chosen to keep them together so that in the event of going somewhere, it is easily convenient to access the items. Other than that, the items really have distant relationships. 
- In software, temporal relationship often occur near the beginning or ending or programs. 
- If a programmer were to move these functions into a single method, the method would be temporally cohesive. Like logical cohesion, this organization has little to do with the function of the method and more to do with an easy way to categorize the functions. 

## Procedural Cohesion
- appears to be very similar to temporal cohesion. 
- combine elements that the program uses to perform some process. 
- The different between procedural and temporal cohesion: 
    * procedural - based on steps of a process 
    * temporal - based on when these happen
- In software, procedural cohesion might result from a process that requires checking authorization before allowing access to a resource such as a database. 
- If a developer combines the steps of checking authorization followed by accessing a database into a module - such as a method -> then the method would have procedural cohesion. 