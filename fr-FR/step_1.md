Importe Button de la bibliothèque picozero puis définis les broches pour plusieurs boutons, utilise le code suivant :

--- code ---
---
language: python filename: line_numbers: false line_number_start: 1
line_highlights:
---
from picozero import Button

button_1 = Button(18) button_2 = Button(22) button_3 = Button(28) --- /code ---

**Astuce**: Tu voudras peut-être donner à tes boutons des noms de variables qui se rapportent à ce qu'ils font. Par exemple, `bouton_rouge` pour allumer une lumière rouge. 
