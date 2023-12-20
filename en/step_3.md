## Print variables

A **variable** is used to store values such as text or numbers. Choosing a sensible name for a variable makes it easier to remember what it is for.

We have included some variables that store emoji characters.

--- task ---

In the Code Editor, scroll to the line with the variable `world`, which stores the text '🌍🌎🌏'.

--- /task --- 

--- task ---
 
Change your code to also `print()` the contents of the `world` variable:

--- code ---
---
language: python
line_numbers: true
line_number_start: 18
line_highlights: 19
---

# Put code to run under here
print('Hello', world) 

--- /code ---

--- /task ---

--- collapse ---

---
title: Tip for using print
---

`'Hello'` is a text string because it has single quotes around it, while `world` is a variable, so the value stored in it will be printed. 

--- /collapse ---

--- task ---

**Test:** Run your code to see the result:

![The Text Output area showing the word "Hello" followed by three world emojis.](images/run_hello_world.png)

--- /task ---

--- collapse ---

---
title: Is there an error?
---

Make sure you have added a comma between the items in `print()` and you have spelled `world` correctly.

This example is missing the comma `,`. It is small but very important!

![In the Code Editor, the code area contains the line print('Hello' world) with no comma, and the error "SyntaxError: bad input on line 19 of main.py" is shown in the output area.](images/comma_error.png)


--- /collapse ---

--- task ---

**Add** another line to your code to `print()` more text and emojis:

--- code ---
---
language: python
line_numbers: true
line_number_start: 19
line_highlights: 20
---

print('Hello', world)    
print('Welcome to', python) 

--- /code ---

--- /task ---

--- task ---

Make sure you check carefully for brackets, quotes, commas, and correct spelling.

**Test:** Click on **Run**.

![The Text Output area showing the word "Hello" followed by three world emojis, then the words "Welcome to Python" followed by a snake emoji.](images/run_multiple.png)

--- /task ---

--- collapse ---
---
title: Tip for writing programs
---

It is a good idea to run your code after every change so you can fix problems quickly.

--- /collapse ---

If you have a Raspberry Pi account, in the Code Editor you can click the **Save** button to save a copy of your project to your **Projects**.

--- save ---
