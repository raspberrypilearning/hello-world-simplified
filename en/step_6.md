## Roll a dice 🎲

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

In Python you **call** a **function()** to perfom an action. You have already used the `print()` function to output text.

</div>
<div>

![The text output area with additional lines to ask the user to input the biggest number for their dice and the response with the random number.](images/roll_dice.png){:width="300px"} 

</div>
</div>


### Define your function

--- task ---

Functions need to be defined before you can call them. Look for the comment in the **main.py** file that says `# Function definitions`.

Define a new function called `roll_dice()` that uses the `randint()` function from the `random` library, to generate a random 'integer' (whole number) from 1 to 6 and output it to the screen.

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 15
line_highlights: 16-17
---

# Function definitions
def roll_dice():  # Don't forget the colon at the end of this line   
    print('You rolled a', randint(1, 6))  # randint(1, 6) is used to give a number between 1 and 6.

--- /code ---

--- /task ---

--- collapse ---

---
title: Tips on using functions
---

The line under `def roll_dice():` is **indented**. To do this, use the <kbd>Tab</kbd> character on your keyboard (usually above <kbd>CAPSLOCK</kbd> on the keyboard). Indenting code tells Python that the indented lines are part of the function.

In Python:
  - **functions**, defined with `def`, are like 'my blocks' in Scratch,
  - `randint` is like 'random' in Scratch, and
  - `input` is like 'ask' in Scratch.

**Tip:** The underscore `_` is used between words in variable and function names in Python to make them easier to read. You can't use a space. 

--- /collapse ---

--- task ---

**Test:** If you ‘Run’ your code now, it won't roll a dice. That’s because you have defined the `roll_dice()` function, but not called it yet.

**Debug:** 

--- collapse ---
---
title: I have a syntax error 
---

- Make sure you have an underscore `_` between roll and dice to make the function name. 

- Make sure you have a colon `:` at the end of the line.

- Check that the line under `def roll_dice()` is indented. It's really common to get this wrong in Python, so make sure to check.

![The code editor showing the line of code inside the `roll_dice` function has not been indented. The line of code with the error is highlighted. The code has been run, with the error 'SyntaxError: bad input on line 17 in main.py'.](images/indent_error.png)

--- /collapse ---

--- /task ---

### Call your function

--- task ---

To use a function, you need to **call** it in the code. Go to the end of your code and add a new line to call the `roll_dice()` function:

--- code ---
---
language: python
filename: main.py
line_numbers: true
line_number_start: 25
line_highlights: 27
--- 

print('The date and time is', datetime.now())

roll_dice()  # Call the roll dice function

--- /code ---

--- /task ---

--- task ---

**Test:** Run your project several times to see the random dice roll each time. 

--- /task ---
