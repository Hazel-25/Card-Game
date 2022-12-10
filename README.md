# Card Game Overview
 Class Cards
 The Card class, which has two class variables, suits and values, is the first class in our card game written in Python. Spades, hearts, diamonds, and clubs are just a few of the possible suits represented by the tuple of strings known as "suits." value is a tuple of strings that represents the range of possible card values, from 2 to 10, as well as Jack, Queen, King, and Ace.
 
## Instructions/
 1. Each player draws a card from the deck.
 2. after drawing the cars the program will process the card that was drawn.
 3. After processing the player with the highest card will win.
 
 ### UML Diagram

```mermaid
journey
	title Card Game
	section User open the Program
		User run the program: 5: User
		Proagram replies introduction: 5: Bot
		Bot asks for an action: 5: Bot
		User chooses Change UTC: 5: User
    Bot changes timezone: 5: Bot
    Bot asks for another action: 5: Bot
    User chooses Add Reminder: 5: User
    Bot asks for Reminder Title, Reminder Date, Reminder Time and Reminder info: 5: Bot
    User answers all questions: 5: User
	section Other Options
		All Reminders: 5: Bot
		Delete History: 5: Bot
	section Result Declared
		Reminder Succesfully Added: 5: Bot
		Reminder Deleted Succesfully: 5: Bot
    Wrong time format! We're sorry, you'll have to restart the process...: 1: Bot
    Wrong date format! We're sorry, you'll have to restart the process...: 1: Bot    
```
