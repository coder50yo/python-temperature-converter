# Temperature Converter Python Project

This is a simple Python project that converts temperatures between Celsius and Fahrenheit.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Setting Up the Project](#setting-up-the-project)
- [Running the Converter](#running-the-converter)
- [Running the Tests](#running-the-tests)
- [Explanation of the Code](#explanation-of-the-code)
- [Using `.gitignore`](#using-gitignore)
- [Additional Resources](#additional-resources)

## Prerequisites

- [Python](https://www.python.org/downloads/) installed on your system
- [Git](https://git-scm.com/downloads) installed on your system

## Project Structure

The project has the following structure:

```
temperature-converter/
│
├── .gitignore
├── converter.py
├── test_converter.py
└── README.md
```

- `converter.py`: The main Python script that performs the temperature conversions.
- `test_converter.py`: Unit tests for the conversion functions.
- `.gitignore`: A file specifying which files and directories to ignore in the Git repository.
- `README.md`: A comprehensive tutorial on how to set up and run the temperature converter project.

## Setting Up the Project

1. **Clone the Repository**

   First, clone the repository to your local machine. Open your terminal and run the following command:

   ```sh
   git clone https://github.com/coder50yo/temperature-converter.git
   ```

2. **Navigate to the Project Directory**

   Change into the project directory:

   ```sh
   cd temperature-converter
   ```

## Running the Converter

To run the temperature converter, execute the following command in your terminal:

```sh
python converter.py
```

Follow the prompts to choose a conversion type and input the temperature value.

## Running the Tests

To run the unit tests for the conversion functions, execute the following command in your terminal:

```sh
python -m unittest test_converter.py
```

You should see output indicating that the tests passed.

## Explanation of the Code

### `converter.py`

The `converter.py` script defines functions for temperature conversions: `celsius_to_fahrenheit()` and `fahrenheit_to_celsius()`. The script also handles user input to choose a conversion type and input the temperature value for conversion.

### `test_converter.py`

The `test_converter.py` script contains unit tests for each conversion function (`celsius_to_fahrenheit()`, `fahrenheit_to_celsius()`). It uses the `unittest` framework to assert expected results against actual function outputs.

## Using `.gitignore`

The `.gitignore` file specifies files and directories that Git should ignore, such as temporary files, build artifacts, and environment-specific directories.

Here are some common entries in the `.gitignore` file:

- `__pycache__/`: Python's bytecode cache directory
- `*.pyc`: Compiled Python files
- `venv/`, `env/`: Virtual environment directories

## Additional Resources

- [Python Official Documentation](https://docs.python.org/3/)
- [Git Official Documentation](https://git-scm.com/doc)
- [unittest Documentation](https://docs.python.org/3/library/unittest.html)