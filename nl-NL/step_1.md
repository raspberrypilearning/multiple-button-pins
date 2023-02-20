Importeer Button uit de picozero-bibliotheek en stel vervolgens de pinnen voor meerdere knoppen in, gebruik de volgende code:

--- code ---
---
language: python filename: line_numbers: false line_number_start: 1
line_highlights:
---
from picozero import Button

button_1 = Button(18) button_2 = Button(22) button_3 = Button(28) --- /code ---

**Tip**: Misschien wil je je variabelen voor je knoppen namen geven die betrekking hebben op wat ze doen. Bijvoorbeeld `rode_knop` om een rood licht aan te doen. 
