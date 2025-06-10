# Python Small

`fork` this repository and `clone` it to your local machine.

This repository contains small Python projects and guides for beginners.

There are three markdown files that will lead you through a series of
steps to learn some beginner Python programming.

You will use the `Python interpreter` to learn about variables, functions, and classes.
**Make sure you TYPE the snippets from the markdown files into the Python interpreter**.
Not typing, doing copy/paste, will not help you learn (and is cheating at this point of the course)

## Getting Started

To get started, clone this repository to your local machine:

```bash
cd ~/Projects
git clone https://github.com/ZipCodeCore/JavaSmall
```

Then, navigate to the repository:

```bash
cd JavaSmall
```

## Python Setup

Make sure you have Python installed on your system:

```bash
python3 --version
```

If you don't have Python installed:
- **macOS**: Install via Homebrew: `brew install python3`
- **Windows**: Download from https://python.org
- **Linux**: Use your package manager: `sudo apt install python3` (Ubuntu/Debian)

## Using the Python Interpreter

Unlike Java which requires `jshell` for interactive programming, Python is interpreted by default.

To start the Python interpreter:
```bash
python3
```

You should see the Python prompt:
```
Python 3.x.x (default, ...)
[GCC ...] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

To exit the Python interpreter:
- Type `exit()` and press Enter
- Or press `Ctrl+D` (Linux/macOS) or `Ctrl+Z` then Enter (Windows)

## Python vs Java: Key Differences

| Feature | Java | Python |
|---------|------|--------|
| Interactive Shell | `jshell` | Built-in interpreter |
| Variable Declaration | `int x = 5;` | `x = 5` |
| String Concatenation | `"Hello " + name` | `f"Hello {name}"` |
| Method Definition | `public void method() {}` | `def method():` |
| Class Constructor | `ClassName(params) {}` | `def __init__(self, params):` |
| Boolean Values | `true`, `false` | `True`, `False` |
| Code Blocks | `{ }` | Indentation |

## Learning Path

Use a browser to be able to see the markdown files.
Start with `PythonSmall.md` and follow the links to the other guides:

1. **PythonSmall.md** - Learn Python basics with the interpreter
2. **VARS.md** - Understanding Python variables and types
3. **ClassPerson.md** - Creating and using Python classes

## Python Advantages for Beginners

1. **No compilation needed** - Python code runs directly
2. **Interactive by nature** - No special shell needed like jshell
3. **Readable syntax** - More English-like than Java
4. **Dynamic typing** - No need to declare variable types
5. **Extensive standard library** - Lots of built-in functionality

## Tips for Success

1. **Type, don't copy-paste** - Build muscle memory
2. **Experiment freely** - Python interpreter is forgiving
3. **Use meaningful variable names** - Python encourages readability
4. **Pay attention to indentation** - Python uses whitespace for structure
5. **Read error messages** - Python error messages are helpful

## Common Python Conventions

- **Variable names**: Use `snake_case` (not `camelCase`)
- **Function names**: Use `snake_case`
- **Class names**: Use `PascalCase`
- **Constants**: Use `UPPER_CASE`
- **Indentation**: Use 4 spaces (not tabs)

## File Extensions

- **Python files**: `.py`
- **Python interactive files**: Can be saved as `.py` files

## Running Python Files

Once you create a Python file (like `hello.py`), run it with:
```bash
python3 hello.py
```

## Additional Resources

- Python official documentation: https://docs.python.org/3/
- Python tutorial: https://docs.python.org/3/tutorial/
- Learn Python the Hard Way: https://learnpythonthehardway.org/

## Getting Help

In the Python interpreter:
- `help()` - Interactive help
- `dir(object)` - Show object attributes
- `type(variable)` - Show variable type
- `help(function)` - Help for specific function

Start your Python journey with `PythonSmall.md`!