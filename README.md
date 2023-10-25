# Clipboard Manager README

## Overview

This simple Python script serves as a basic clipboard manager. It allows you to save and load text data from your clipboard using command-line instructions. This can be particularly useful when you need to quickly store and retrieve pieces of text that you frequently copy and paste.

## Prerequisites

Before using this clipboard manager, make sure you have the following prerequisites installed on your system:

- Python: You need to have Python installed on your computer. You can download it from [Python's official website](https://www.python.org/downloads/).

## Usage

1. **Save Data:**

   To save data to your clipboard manager, run the following command in your terminal:

   ```
   python clipboard_manager.py save
   ```

   - You will be prompted to enter a key to identify the saved data.
   - The current content of your clipboard will be saved with the specified key.

2. **Load Data:**

   To load previously saved data from the clipboard manager, run the following command:

   ```
   python clipboard_manager.py load
   ```

   - You will be prompted to enter the key associated with the data you want to retrieve.
   - If the key exists in the clipboard manager, the associated data will be copied to your clipboard, making it ready for pasting.

3. **List Saved Data:**

   To view the list of keys and the data currently saved in your clipboard manager, run:

   ```
   python clipboard_manager.py list
   ```

   - This will display a list of keys and the corresponding data saved in the clipboard manager.

4. **Unknown Command:**

   If you enter a command that is not recognized by the clipboard manager, it will display an "Unknown command" message.

5. **Multiple Commands:**

   Please note that you should enter only one command at a time. The clipboard manager expects a single command as an argument.

## Data Storage

The clipboard manager stores the saved data in a JSON file named `clipboard.json` by default. You can change the name of the file by modifying the `SAVED_DATA` variable in the script.

## Error Handling

The clipboard manager handles errors gracefully. If the specified key does not exist when attempting to load data, or if the `clipboard.json` file is missing or corrupted, it will respond without crashing.

## Author

This clipboard manager script was created by Aranya Dutta. Feel free to contact me at [thisisaro.official@gmail.com] if you have any questions or suggestions.

## License

No license yet. Working on it.

---
