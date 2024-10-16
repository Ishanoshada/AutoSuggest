# AutoSuggest - Terminal Auto-Suggestion Tool

**AutoSuggest** is a Python terminal application that provides auto-suggestions based on user input. It is designed to enhance the user experience by offering real-time suggestions, making it easier to select names or other items.

## Features

- Real-time auto-suggestions as you type.
- Supports both colored and plain text output.
- Works on Windows and Unix-based systems (Linux, macOS).
- Clear terminal interface.



## Installation

To install AutoSuggest, simply use pip:

```bash
pip install autosuggest
```

## Usage

You can run the AutoSuggest tool directly in your terminal. Here's an example of how to use it:

```python
from autosuggest import AutoSuggest

# List of suggestions
names = ["Alice", "Bob", "Charlie", "David", "Edward", "Fiona", "George", "Hannah", "Ian", "Julia"]

# Customize your input message and whether to use colors
input_message = "Please type a name (Press Backspace to delete, ESC to exit): "
use_colors = True  # Set to False to disable colors

# Create an instance of AutoSuggest
suggestion_tool = AutoSuggest(names, input_message, use_colors)

# Run the auto-suggest feature
selected_name = suggestion_tool.run()
print(f"You selected: {selected_name}")
```

### Running the Tool

To execute the script, save it in a `.py` file and run it from the command line:

```bash
python your_script_name.py
```

Replace `your_script_name.py` with the name of your script.

## Customization

- **Input Message**: Change the `input_message` variable to customize the prompt shown to the user.
- **Color Usage**: Set the `use_colors` variable to `True` to enable colored output or `False` to disable it.

## Contributing

Contributions are welcome! If you'd like to improve this project, please submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or support, please contact us at Ishan.kodithuwakku.official@gmail.com

**Repository Views** ![Views](https://profile-counter.glitch.me/autosuggest/count.svg)

