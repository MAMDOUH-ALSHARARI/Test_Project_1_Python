# Personality-Quiz

The Personality Quiz Game is an interactive application developed using Python and the Pygame library. The game presents a series of questions to the user, allowing them to select answers that correspond to different personality types. At the end of the quiz, the game displays the user's personality type based on their selections.



## Features
- **Interactive Interface:** The game uses IPython Widgets to provide a smooth and interactive experience.
- **Computer interaction:** The computer responds instantly after your move with a simple AI that picks random available cells.
- **Status Updates:** See real-time updates about the game’s progress: whose turn it is, who won, or if the game resulted in a draw.
- **Restart Option:** Use the reset button to restart the game at any point.

## Main Components

- **Data Structure:**
Utilizes a list of dictionaries to store questions, options, and corresponding personality types. This structure allows easy access and management of quiz content.

- **Scoring System:**
Implements a scoring system to track the user's responses and calculate their personality type based on the answers selected.

- **Display Functions:**
Defines functions to render text and create buttons, enhancing the user interface and making it intuitive.

- **Event Handling:**
Uses a main loop to handle user interactions (e.g., mouse clicks) and navigate through questions. This includes checking for user input and updating the display accordingly.

- **Result Calculation**
Utilizes a max() function with a lambda expression to determine the personality type with the highest score at the end of the quiz.
## Installation

To run the Personality Quiz Game on your local machine, follow these steps:

1. Clone the Repository

 ```bash
    git clone https://github.com/yourusername/personality-quiz.git
    cd personality-quiz

    ```
2. Install Pygame Make sure you have Python installed. Then, install the Pygame library using pip:

 ```bash
    pip install pygame


    ```


## Team Members
- **Adel** 
- **Mamdouh Alsharari** 
- **Lama**
- **Lina**
- **Mouhnd**

## Game URL
You can access and play the game via this link: [OX Game](https://mybinder.org/v2/gh/MAMDOUH-ALSHARARI/Test_Project_1_Python/HEAD?urlpath=voila%2Frender%2FProject_1_Python.ipynb)
