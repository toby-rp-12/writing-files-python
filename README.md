# writing-files-python
My first python code that writes/saves files!

## Summary
This project from my CS class is a short Python exercise designed to teach the basics of working with files. It focuses on reading from files, writing to files, and appending data safely using Python’s built-in file handling tools.

The program includes automatic tests that run when the script is executed.

I had to troubleshoot a lot for this assignment, but I am happy that I eventually understood it.

## Key Features

- Uses Python’s `open()` function correctly
- Demonstrates file modes: write (`w`), append (`a`), and read (`r`)
- Ensures files are always closed properly
- Handles missing files without crashing
- Includes automatic testing after implementation
- Uses UTF-8 encoding for safety

## Functions

### save_message(path, msg)
- Creates or overwrites a file
- Writes exactly `msg` into the file

### append_message(path, msg)
- Adds a new message to the end of a file
- Each message is added on its own line
- Creates the file if it does not already exist

### load_message(path)
- Reads and returns the entire contents of a file
- Returns an empty string if the file does not exist

## Requirements & How to Run
### Requirements
- Python 3.x
- No external libraries required
### How to Run:
1. Make sure Python 3 is installed.
2. Save the file as:
```
writingfiles.py

```
3. Navigate to the folder containing the file.
4. Run the script using python.

## Example Usage
**Input:**

```
save_message("note.txt", "hello")
append_message("note.txt", "more text")
print(load_message("note.txt"))
```
**File contents:**
```
hello
more text
```
