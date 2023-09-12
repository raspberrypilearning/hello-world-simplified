## Use an emoji for the number rolled

Your function can use the 🔥 emoji variable. The code `print(fire * 3)` outputs three fire emojis '🔥🔥🔥'. You need to output the correct number of emojis to match the random number rolled by the dice.

--- task ---

Change your code to save the value returned by `randint()` in a variable called `roll`. Use that variable to print out the number rolled with the matching number of 🔥 emojis.
 
--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 15
line_highlights: 17-18
---

# Function definitions
def roll_dice():
    roll = randint(1, 6)  # Generate a random number between 1 and 6 and store it in the variable 'roll'
    print('You rolled a', roll, fire * roll)  # Repeat the fire emoji to match the random dice roll

--- /code ---

--- /task ---

--- task ---

**Test:** Test your project a few times. Make sure you understand how the code works. 

--- /task ---

### Choose the number of sides on the dice

Upgrade your dice so that the user can choose the maximum number. 

--- task ---

The `input()` function asks the user a question and then returns their answer.

**Add** code to ask the user for the biggest number on their dice and then save the result in a variable called `max` and `print` the number chosen into the output area: 

Change your `roll` variable code to use `max` as the maximum value for `randint` when it generates a random number. 

When you get input from the user, Python treats it as text. But, `randint` needs an 'integer' (a positive whole number). The `int` function turns the user input into an integer.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 15
line_highlights: 18-20
---

# Function definitions

def roll_dice():   
    max = input('How many sides?:')  # Wait for input from the user    
    print('That\'s a D', max)  # Use the number the user entered    
    roll = randint(1, int(max))  # Use max to determine the number of sides the dice has
    print('You rolled a', roll, fire * roll)   

--- /code ---

To print an apostrophe `'` in a word like `That's`, put a backslash `\` before it so Python knows it's part of the text.

--- /task ---
  
--- task ---

**Test:** Run your project. When the program reaches the `input` line, it will wait for you to enter a response before continuing. Type your response and then press <kbd>Enter</kbd>, this will allow the program to collect your response. Try it again with a different `input` number. 

--- /task ---

--- save ---
