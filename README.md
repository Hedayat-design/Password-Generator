# Password Generator

A simple and customizable password generator with a graphical user interface built using Python's tkinter library. This application allows users to generate passwords of varying complexity levels and lengths according to their security needs.

## Features

- **Customizable Password Length**: Generate passwords between 5 to 50 characters
- **Multiple Complexity Levels**:
  - Weak: Combination of uppercase and lowercase letters
  - Moderate: Combination of uppercase letters, lowercase letters, and numbers
  - Strong: Combination of letters, numbers, and special characters
- **User-Friendly Interface**: Clean and intuitive GUI with clear feedback messages
- **Input Validation**: Ensures proper length input and complexity selection
- **Visual Feedback**: Displays generated passwords in a separate window

## Requirements

- Python 3.x
- tkinter (usually comes pre-installed with Python)
- random module (built into Python's standard library)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/password-generator.git
```

2. Navigate to the project directory:
```bash
cd password-generator
```

3. Run the application:
```bash
python password_generator.py
```

## Usage

1. Launch the application
2. Enter desired password length (5-50 characters)
3. Select complexity level (Weak, Moderate, or Strong)
4. Click "Generate" to create a password
5. A new window will appear displaying your generated password
6. Click "Quit" to exit the application

## Error Handling

The application includes various error checks:
- Validates that length input is numeric
- Ensures password length is between 5 and 50 characters
- Requires selection of complexity level
- Provides clear error messages with automatic cleanup

## GUI Components

- Password length input field
- Complexity selection radio buttons
- Generate and Quit buttons
- Error message displays
- Separate password display window

## Contributing

Feel free to fork this repository and submit pull requests to contribute to this project. For major changes, please open an issue first to discuss what you would like to change.


## Acknowledgments

- Built using Python's tkinter library for GUI
- Uses Python's random module for secure password generation
- Inspired by the need for customizable password security options
