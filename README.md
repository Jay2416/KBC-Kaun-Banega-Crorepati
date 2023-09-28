
# K.B.C. - Kaun Banega Crorepati 💲

This software project is developed to automate the functionalities of a K.B.C. – Kaun Banega Crorepati (Game). 

It is design to promote a fun way to study and in the process help improve once general knowledge. It improves or expands once knowledge of things. It is to encourage players to look beyond their textual knowledge and establish a relationship between theory and application of the learnt concepts.







## Features ✨

- GUI is designed such that it look like the real quiz show.
- The lifelines works accordingly as per the quiz show.




## Modules Used 💻

- **tkinter** - to create GUI
- **random** - to get the random numbers and choices
- **ttk** - to create themed widgets
- **PIL** - to insert images of different abbreviation into a GUI, to install this library, use the following command on your command prompt

```bash
pip install pillow
```

- **pyttsx3** - to use the utility of Text-To-Speech

**Enigne Properties for different platform**

- *'sapi5'* - For Windows
- *'nsss'* - For MacOS
- *'espeak'* - For Linux or any other platform

Use the following command to install this module.
```bash
pip install pyttsx3
```

- **pygame** - (in this project) to setup different audios, use the following commanf to install this module

```bash
pip install pygame
```


## Event Bindings ⛓️

The most important part to make a better GUI is to learn the event binding process. The most used key bindings in tkinter with their uses are:

|Event Key | Key Binded |
|----------|------------|
|Button-1  |Single left click |
|Button-3  |Single right click |
|Return    |Enter key |
|ButtonRelease|Release mouse button |
|Enter     |Mouse cursor entering in the widget |
|Double-Button-1  |Double left click |
|Double-Button-3  |Double right click |
|Leave |Mouse cursor leaving the widget |


## Limitations 🚧 

- This software fails to fetch random questions from the internet and works only on the 40 questions stored in the dictionary.
- If the user does not enter his/her name at the beginning he/she would have to open the software again.
- If a audio questions comes, then we cannot hear the timer sound but the timer still goes on and after the audio question, the audio continues to play until it gets over.