Import Button from the picozero library then set the pins for multiple buttons, use the following code:

--- code ---
---
language: python
filename: 
line_numbers: false
line_number_start: 1
line_highlights: 
---
from picozero import Button

button_1 = Button(18)
button_2 = Button(22)
button_3 = Button(28)
--- /code ---

**Tip**: You might want to give your buttons variable names that relate to what they are doing. For example, `red_button` to turn on a red light. 
