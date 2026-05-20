# Dessert in the Desert 

A browser game where you have to click the right word. Buttons saying "Dessert" 
and "Desert" are scattered across the screen, click Dessert to gain a point, 
click Desert to lose one. Every click moves all the buttons to new random 
positions so you can't just memorize where they are.

## How to Play
1. Download or clone the repo
2. Open `dessertGame.html` in your browser
3. Click Dessert, not Desert
4. Don't lose points

## How it works
The buttons are positioned with CSS `absolute` and every click calls a function 
that reassigns random `left` and `top` values to each one. Score is tracked in 
a variable and updates the DOM on every click.

## Built with
- HTML
- CSS
- JavaScript

## What I learned
Mostly how JavaScript actually talks to the page — updating text, moving elements 
around, handling clicks. Simple project but it made the DOM feel a lot less 
abstract.
