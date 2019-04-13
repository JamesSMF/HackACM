# Todo Command Line App

##### ===========================================

##### Welcome to Todo App developed by James Li.
##### This app is a schedule management app which
##### helps you to make and manage daily schedules.
<br/>
##### Team members:
##### James Li

##### ===========================================




<br/>

How to run it
=================================================

Enter "python c.py" on command line

<br/>


Basic operations:
================================================
## 1. Enter "i" to insert a new event

-- After entering "i", you will be prompted to enter an event
   name and date. You can enter the date in any format you like
   (e.g. 20180114 or 2018/04/26 or 2018-06-15). But be
   careful that year should come first followed by month
   and date subsequently.

-- Then you will be prompted to enter a time. You can
   also enter the time in any format that you like.
   But hour should come before minute.

## 2. Enter "d" to delete an old event

-- Enter the name of the event which you want to
   delete to delete the event.

## 3. Enter "c" to check the date of a specific event

## 4. Enter "t" to get a list of things to do tomorrow

## 5. Enter "o" to get a list of things to do today

## 6. Enter "l" to get 16 deadline-in-the-ass events

-- In order not to make the screen seem messed. Only
   most recent 16 events will pop up. (enter "more"
   to show more)

## 7. Enter "r" to revise the date of a certain event
 
## 8. Press "q" to exit
 



Advanced Techniques
=============================================
## Three different ways to insert an event:

1. Use "i", as mentioned aboved.

2. Use "map". For example, "map go to gym tomorrow 14:00"
   will create the event "go to gym" and map it to tomorrow
	14:00

3. Use natural language. For example, "I will go to gym tomorrow
   at 14:00" will do the same thing as above.


<br/>

## Use natural language to get the list of event

for example, "What is my plan today" will be equavalent to "l"

<br/>

## Programmer-friendly input

1. "ls" = "l"

2. rm + \<event name\> can delete the event quickly



Features to mention
=================================================

1. This program automatically deletes events that has past
   its date, because I want to convey the idea of looking
	forward instead of looking back.

2. If you don't want to calculate the actual date of an event,
	don't worry! You can use words such as "today", "tomorrow",
	"Tuesday", etc. to insert events.

3. Don't want to mess the schedule up? Afraid of getting conflict
   schedule? No worry! If there is another event around the event
	you are going to insert, the program will throw a warning message.
	If you insist to insert that event, type "yes". Of course, if you
	want to be fancy, typing "hell yeah" will also do the work...

4. Will you do something at 2 am or 3 am? Well... probably not. So, when
   you use the map function and type "map go to Mike's house tomorrow 2:30",
	it will automatically be interpreted as 14:30 in the afternoon. What if
	you do want to do something at 2:30 am? Simplly adding a "0" will solve
	the problem. In other words, "map go to Mike's house tomorrow 02:30".





