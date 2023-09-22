## Say hello

<div style="display: flex; flex-wrap: wrap">

<div>

![The code editor output area showing the two printed lines of text and emojis.](images/say_hello.png){:width="200px"}

</div>
</div>

--- task ---

Open the [Hello 🌍🌎🌏 starter project](https://editor.raspberrypi.org/en/projects/hello-world-starter){:target="_blank"}. The code editor will open in another browser tab.

![The code editor with project starter code on the left in the code area. On the right is the blank output area.](images/starter_project.png)

If you have a Raspberry Pi account, click on the **Save** button to save a copy to your **Projects**.

--- /task ---


### Print Hello

In Python, `print()` outputs text (words or numbers) to the screen.

--- task ---

Find the `# Put code to run below here` line.

The flashing `|` is the cursor. It shows where you will type.

--- /task ---

--- task ---

Type the code to `print()` Hello to the screen:

--- code ---
---
language: python
line_numbers: true
line_number_start: 17
line_highlights: 18
---

# Put code to run under here    
print('Hello')

--- /code ---

--- /task ---

--- collapse ---
---
title: Tip for using print
---

When you type an opening bracket `(` the code editor will automatically add a closing bracket `)` 
This also happens when you type an opening apostrophe `'`.

--- /collapse ---

--- collapse ---
---
title: Typing special characters on a UK or US keyboard
---

On a UK or US keyboard, the left `(` and right `)` round brackets are on the <kbd>9</kbd> and <kbd>0</kbd> keys. To type a left round bracket, hold down the <kbd>Shift</kbd> key (next to <kbd>Z</kbd>) and then tap <kbd>9</kbd>.
The single quote `'` is on the same row as the <kbd>L</kbd> key.
The comma `,` is next to the <kbd>M</kbd>.

--- /collapse ---

--- task ---

**Test:** Click on the **Run** button. Your code which will output in the Text output area.
![The Run icon highlighted with 'Hello' showing in the output area. ](images/run_hello.png) 

--- /task ---

--- collapse ---

---
title: Debug
---

If you get an error then check your code really carefully. Check there are single quotes around `Hello` so Python knows it is meant to be text.

![The Code Editor with missing single quotes and error 'NameError: name 'Hello' is not defined on line 18 in main.py.](images/hello_error.png)

--- /collapse ---

