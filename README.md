# Cisco Switch Configurator

This Python script provides a graphical user interface (GUI) for configuring Cisco switches via serial connection.

## Introduction

The Cisco Switch Configurator allows users to interact with Cisco switches through a graphical interface, enabling the execution of commands and configuration tasks with ease.

## How It Works

The script establishes a serial connection with the Cisco switch using the specified COM port and BAUD rate. Users can then choose to execute custom commands or predefined command sequences on the switch. The output from the switch is displayed in the GUI, providing options to copy the output to the clipboard or save it to a file.

## Features

- **Serial Communication:** Establishes a serial connection with the Cisco switch using the specified COM port and BAUD rate.
- **Command Execution:** Executes custom commands or predefined command sequences on the switch.
- **Output Handling:** Displays the output from the switch in the GUI and provides options to copy the output to the clipboard or save it to a file.
- **Error Handling:** Provides error messages for invalid inputs or connection issues.
- **Changelog Display:** Shows the version history and changelog within the GUI.

## Getting Started

1. Run the script.
2. Select the COM port and BAUD rate for the serial connection.
3. Choose a command from the predefined list or enter a custom command in the designated field.
4. Click the "Configure" button to execute the selected command(s) on the switch.
5. View the output in the text box provided. You can copy the output to the clipboard or save it to a file using the respective buttons.

## Dependencies

- Python 3.x
- Required Python packages: serial, tkinter, getpass

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

The Port Scanner script was created by [Anthony Constant](https://anthonyconstant.co.uk/).

## Support My Work

If you like this repository or have used any of the code, please consider showing your support:

- Give it a star ⭐️ to acknowledge its value.
- You can also support me by [buying me a coffee ☕️](https://ko-fi.com/W7W144CAO).
