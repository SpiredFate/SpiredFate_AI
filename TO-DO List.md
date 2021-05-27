# SpiredFate_AI

*Start with the basics. Economy first, try to use constants that are defined by the era/goals instead of numbers for your work.
 
 ie.
 (defrule
 (current-age = Dark-Age)
 =>
 (defconst Villigers 25)
 (disable-self)
 )
 
 (defrule
 (current-age = Feudal-Age)
 =>
 (defconst Villigers 50)
 (disable-self)
 )
 
 (defrule
 (unit-type-total-count Villiger < Villigers)
 (can-train villiger)
 =>
 (train villiger)
 )
