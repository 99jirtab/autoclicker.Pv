# autoclicker.Pv
An auto clicker meant to fight for you


# Autoclicker

This Python script is a simple autoclicker that automates mouse clicks at a specified interval. You can start and stop the autoclicker with a keyboard shortcut and exit the program when you're done.

## Features
- Automates mouse clicks at a configurable time interval.
- Allows you to start/stop clicking using a specific key.
- Exit the program with a defined key.

## Prerequisites
1. Install Python (version 3.6 or higher).
2. Install the required library:
   ```bash
   pip install pynput
   ```

## How to Use
1. Clone or download this repository to your local machine.
2. Open the script file `autoclicker.py` in a text editor to modify settings if needed:
   - **`delay`**: Adjust the time interval between clicks (default is `0.1` seconds).
   - **`start_stop_key`**: Change the key to start/stop the autoclicker (default is `s`).
   - **`exit_key`**: Change the key to exit the program (default is `e`).

3. Run the script in your terminal or command prompt:
   ```bash
   python autoclicker.py
   ```

4. Control the autoclicker:
   - Press the **`s` key** to start or stop the clicking.
   - Press the **`e` key** to exit the program.

## Example Configuration
If you want to use custom keys:
```python
delay = 0.2  # Set the delay to 200 milliseconds
start_stop_key = KeyCode(char='a')  # Use 'a' key to start/stop
exit_key = KeyCode(char='q')  # Use 'q' key to exit
```

## Notes
- Be sure to use this script responsibly. Using an autoclicker in games or certain applications may violate their terms of service.
- This script is open-source and can be modified to suit your needs.

## License
This project is licensed under the MIT License.
