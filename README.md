# Red-Light-Germ-Fight
Cornerstone of Engineering (Stacked) - Spring 2025, Final Project

## Project Overview
Red Light Germ Fight is a project combining Arduino and MATLAB to create a graphical game interface controlled by external electronic components, including a 3-button console and a joystick console. The project educates on Antibiotic Resistance to elementary-aged students through gamified representations of the causes and effects of Antibiotic Resistance.

### Note on Content and Contributions
These programs are not the final version of the project code and is missing some game and storytelling elements that were included in the final project. The following code was developed entirely by the author with support and advice about code logic and game ideas from the professor, TA, and groupmates. Additionally, ChatGPT (OpenAI) was used for assistance with initial understanding and implementation of image display and image manipulation functions in MATLAB.

### Setup and Required Downloads/Add-ons
This project is run in MATLAB App Designer and requires the MATLAB Support Package for Arduino Hardware to be downloaded. It also requires an Arduino Uno board to be plugged into the COM6 serial port to run.

The project includes two different scripts - one game controlled by a joystick, and another game controlled by a console of three buttons. These two games differ very slightly in terms of gameplay and objectives, but the general format of manipulating falling image blocks with feedback is very similar. 

*In both games, blocks respond to button presses and joystick movements, directing an avatar to a certain block or which block should be targeted. Then, the images update based on how this movement is related the objectives of each game. 3 vertical blocks fall and a move to target one block must be made each round of falling, then the order of the blocks randomly regenerates each falling cycle.*

These games can also be controlled by keys for easier troubleshooting and so that programming progress is not affected by hardware problems.

### Examples

Video Demonstration of Button Game (early stage)
https://github.com/user-attachments/assets/a3ff3cc8-0cf6-4995-ad56-1d6998397240

Video Demonstration of Joystick Game (early stage)

Image of Full Project Including Hardware Button and Joystick Controls
![RLGF_Setup](https://github.com/user-attachments/assets/ab25cb4f-b861-461e-8954-f93779bffbac)



