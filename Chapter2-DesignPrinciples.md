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