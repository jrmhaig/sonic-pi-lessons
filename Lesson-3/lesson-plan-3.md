## Lesson 3 - Conditionals & Randomisation

###Introduction

If we want to make some meaningful and interesting musical structures we need to learn some meaningful and interesting programming structures.

### Learning Objectives
- Know that computer programs can make decisions, a simple form a decision is called a conditional.
- Understand that computer programs can contain random acts
- Be able to use comments to explain interesting parts of a program.

### Learning Outcomes

**All students will be able to:**

- Play a random note.




###Lesson Summary

-  Simple use of randomisation
-  Using conditionals to make decisions.
-  Combining randomisation and conditionals. 
-  Comments as a programming tool.

###Starter
Pupils are first invited to set up and connect their Raspberry Pi hardware. They may then load the Sonic Pi application and find their work from the previous lesson. Through questioning, select students to explain what they did in the previous lesson. 

###Main Development

1. Pupils should be should be shown how to add some randomisation to their code. This can be achieved by using the statement `rand(10)` which returns a random value between `0` and `10` (from 0 up to but not including the number you specify). You can specify other numbers for larger ranges i.e. `rand(20)` will return values from `0` to `20`. Let’s use this in our program by adding our random number to a note with the `+` operator:
	  play 60 + rand(10)
	```


	if rand < 0.5
	else
	```
	






# Toss a virtual coin 
if rand(1) < 0.5


Students may research electronic sounding music and think about how they could improve the sound of their own composition. 