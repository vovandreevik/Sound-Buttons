# Sound Buttons

This project is a simple web application that has buttons that play certain sounds when pressed. The buttons react differently depending on the sequence of their pressing, which adds an interactive element to the work. The project was made for a student trip for one of the events

## Features

- **Three main buttons:** Each button is associated with a specific sound.
- **Conditional sound playback:** Sounds are played immediately or after a short delay, depending on the sequence of button presses.
- **Visual feedback:** Buttons provide visual feedback when clicked (hover and active states).

## Technologies Used

- **HTML5**: For structuring the web page.
- **CSS3**: For styling the web page.
- **JavaScript**: For adding interactivity and sound playback.
- **Google Fonts**: For custom font styling.

## Getting Started

### Prerequisites

Ensure you have the following files in the same directory as your HTML file:

- `1.voice.mp3`
- `2.activity.mp3`
- `3.data.mp3`
- `4.error.mp3`

### Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/sound-buttons.git
    ```

2. Navigate to the project directory:

    ```bash
    cd sound-buttons
    ```

3. Open the `index.html` file in your web browser to see the project in action.

## Usage

1. **Button 1: "Калибровка звукового модуля"**

    - Plays `1.voice.mp3` when clicked.
    - Plays `4.error.mp3` followed by `1.voice.mp3` if clicked again after another button.

2. **Button 2: "Дефрагментация модуля данных"**

    - Plays `3.data.mp3` if the last button clicked was Button 3.
    - Plays `4.error.mp3` followed by `3.data.mp3` otherwise.

3. **Button 3: "Калибровка кинематики"**

    - Plays `2.activity.mp3` if the last button clicked was Button 1.
    - Plays `4.error.mp3` followed by `2.activity.mp3` otherwise.

## Acknowledgements

- [Google Fonts](https://fonts.google.com/) for the Rubik font.
