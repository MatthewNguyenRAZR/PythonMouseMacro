# MouseMacro
A macro program written in Python that records and runs mouse macros, click and drag.  

## Goals
- Run Macro, Macro Settings, Record, End Recording
  - Only coordinates for mouse press and release are saved.
  - Algorithm for human like mouse movements will be used to move from start to end 

- Macro Settings
  - Edit Random Pixel Disposition (0-20 pixel difference)
  - Edit Time Delay Randomization (will add time delay for every click at a random range between user input's start and end)
  - Edit Random Run Chance (Percentage run chance)
  - Amount of times repeated

- Macro Compiler - runs multiple macros in a list a certain amount of times
  - Add Macro
  - Reset List
  - Amount of times repeated

## How To Use
- Place app.py and macrorecorder.py into a folder of it's own
- Create a folder in the current directory called "macrolist" (this is where all macros will be saved as .txt files)
- Run app.py