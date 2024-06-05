# codealpha_tasks
task 1
explanation
tkinter is the standard Python library for creating graphical user interfaces.
ttk is a module in tkinter that provides access to the Tk themed widget set, which provides a more modern look.
googletrans is a Python library that interfaces with Google Translate API.
Translator is a class from googletrans used to perform translations.
LANGUAGES is a dictionary from googletrans that maps language codes to language names.
change function takes three parameters:
text: The text to translate (default is 'type').
src: The source language code (default is 'en' for English).
dest: The destination language code (default is 'hi' for Hindi).
It creates an instance of the Translator class.
Uses the translate method of the Translator class to perform the translation.
Returns the translated text
data function handles the user input and performs translation.
Retrieves the selected source and destination languages from the comboboxes.
Retrieves the text to be translated from the Text widget.
Maps the language names to their respective codes using LANGUAGES.
Calls the change function to translate the text.
Updates the finaltext Text widget with the translated text.
Now the task is to set up a GUI(graphical user interface).![Screenshot (321)](https://github.com/saga743k/codealpha_tasks/assets/150129375/88d62e53-3cba-41df-8610-e841ab394768)
![Screenshot (320)](https://github.com/saga743k/codealpha_tasks/assets/150129375/1f4224d2-2828-480e-bab3-6ce399df93de)
![Screenshot (319)](https://github.com/saga743k/codealpha_tasks/assets/150129375/9377f0e1-b85e-4790-afa7-f8e11f04211d)
