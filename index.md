
# 🫧 Huu Ngoc Minh Nguyen's Portfolio

    Hello everyone, welcome to my personal portfolio! 👋
    I'm currently a computer science major at CalState Fullerton and I plan to graduate in 2027.
    Over the past 16 weeks, I have learned problem solving and programming several lab exercieses that strengthened my
    coding skills and teamwork. 
    This portfolio is a showcase of my favorite projects from CPSC 120L Labs to reflect my dedication to learning.

## 💻 Computer Science Projects 

    Visit my all projects at http://github.com/nhnminh77

### 🌟 Favorite CPSC 120L Labs

* Lab 6 - part 2: Blackjack Score ♠️

    This is my favourite lab in this course. This lab taught me how to break down a large problem into smaller, well-defined functions and then combine these functions to produce a working program. The goal of the lab exercise is to calculate the value of a two-card blackjack combination according to specific rules, including the value of the cards, aces, allowed input, and whether a player busts. Even with a seemingly straightforward problem, one must be detailed and precise.
    
    The ace bonus in the TwoCardHandScore function is arguably the most interesting piece of code. Aces can be worth 11 points instead of 1, but adding the 11 would bust the player or house. Because we must calculate the hand's basic value, check for aces, and then decide whether to add the 10-point bonus without going over 21 points, this functionality required considerable thought. This piece of code showed me how an if statement can be used with logic deducted from the problem requirements.


* Lab 7 - part 1: Parking Rules 🚫🛑

    This lab is about how a large portion of this function is ensuring the inputs were good. I needed to make sure four arguments were passed and each one was valid for what I wanted it to be used for: a valid street address, a valid day, a value for an hour ranging from 0 - 23, and a value for the minutes ranging from 0 - 59. This function has shown me just how important defensive programming is. A function with flawed input handling is one thing, but one with invalid exit statuses can be disastrous if you do not handle those errors properly.
    
    There were rules specific to each street, so I coded a separate Boolean expression for each one. I began to look at each sign as if it were a specific mathematical expression. For example, on Ash Street, cars were prohibited from parking on only Wednesdays from 10:00 to 12:00. Cedar Street's restrictions cumulatively consisted of night restrictions every day and street washing in the mornings only on Tuesdays. What's special about the rules for Date Street is that the restricted no-parking times begin at 6:30 AM, so I really did have to use the minute value in my reasoning.

* Lab 9 - part 2: Guessing A Secret Number In A File 🔢

    This lab allowed me to understand and apply C++'s basic file I/O functionality for creating two different programs that can be paired with each other. In this lab, one program generates a secret number and saves it to a file, with a companion program able to read the value and initiate a simple guessing game. Even for a relatively simple activity such as a guessing game, understanding input checks and balances within file reads/writes can be a valuable learning experience.
    
    The first program, 'secret.cc', is concerned with handling an argument passed from the command line, doing some checks on it, and printing a value into a file named 'secret.dat'. This exercise has allowed me to appreciate the need for ensuring the right argument is passed and is within the right range even before carrying out any processing.
    
    The second part, 'game.cc' , is more related to the process of extracting data from a file by means of std::ifstream and considering what can actually go wrong with such an operation, lack of a file, a malformed file, an invalid number, and incorrect formatting. It is only then that I understood just how much greater is the care required when extracting information from a file rather than simply from a user's input.