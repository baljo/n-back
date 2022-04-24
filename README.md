
# INTRODUCTION to this n-back test platform

## 1 What is a n-back task?
The n-back task is a continuous performance task that is commonly used as an assessment in psychology and cognitive neuroscience to measure a part of working memory and working memory capacity. The n-back was introduced by Wayne Kirchner in 1958. See https://en.wikipedia.org/wiki/N-back for more information.
## 2 Installation
Copy the files to a folder of your choice and start the software by running nback_main.py with your favourite Python-IDE or from the command prompt. The software was developed using Python version 3.10.2, but as nothing really fancy is being used, somewhat older and newer versions should work. 
## 3 Instructions for use
The objective is to test and improve your working memory capacity. 

#### Worth to know before testing:
There are 5 levels to choose between, what level/levels you want to test is set in the `Settings` menu.
- Level 0: you are supposed to click `Space` or `Left mouse button` when you see the target number. The target number is set in the settings menu, default is 4.
- Level 1 - 4: You are supposed to click `Space` or `Left mouse button` when the previous n number is repeated. 
-- E.g., if level is 1 and you have seen these numbers: 2, 8, 1, 1 - then you should have reacted once you saw the second 1.
-- If level is 2 and you have seen these numbers: 3, 1, 0, 9, 0, 9 - then you should have reacted when you saw the second 0 and second 9.
#### Testing your memory, quick and easy
Why not start with the easiest i.e., `Play single game`. Unless you have messed with the default settings, you will need to react when seeing number 4.
When the test has ended, you will see your scores. If you get tired during the test, you can abort with `Esc`.
#### Testing your memory, slow and hard
Use `Play multi games` or `Play random multi games`. These work similarly as the single game, but instead of only one game, you will play n amount of games according to the settings. 
Scores will only be shown after the final game. Tired? --> click `Esc`.
#### Feeling confident? Challenge yourself!
If you want to challenge yourself, then you can adjust the settings so that you also need to react when the number shown is **not** same as the target (level 0) or previous n number (level 1 - 5). The keys you use for this are `Enter` or `Right mouse button`.

## 4 Settings
## 5 Improvement recommendations for you to consider doing yourself!
- Error control! 
-- E.g., messing around manually with the settings file - unless you know what you are doing - will cause havoc!
-- Also using invalid log filenames, letters instead of numbers (why would you do that?), or not following the instructions might cause interesting behaviour...
- Supporting letters instead of/in addition to numbers in the game itself
- Now the user needs to change the display resolution completely manually by giving x and y resolution. Change this so the user can select from a list of resolutions supported by the user's hardware.
## Credits
- sound from https://soundbible.com/1598-Electronic-Chime.html
- pygame https://www.pygame.org/news
- pygame-menu https://pygame-menu.readthedocs.io/en/4.2.5/index.html
