# Python – Automating File Updates

![Language](https://img.shields.io/badge/Language-Python-blue)
![Focus](https://img.shields.io/badge/Focus-Access%20Control-green)

## Overview

A practical Python project focused on automating access control by updating an IP address allow list.

The algorithm identifies and removes IP addresses that should no longer have access to restricted resources.

## Tasks Performed

- Opened and read an IP allow list from a text file.
- Converted string data into a Python list.
- Iterated through a separate list of IP addresses to be removed.
- Used conditional statements to identify matching IP addresses.
- Removed unauthorized IP addresses using `.remove()`.
- Converted the updated list back into a string using `.join()`.
- Updated the original file using `.write()`.

## Python Concepts & Functions

| Function / Concept | Purpose |
|---|---|
| `open()` | Open files for reading and writing |
| `.read()` | Read file contents |
| `.split()` | Convert strings into lists |
| `for` loop | Iterate through IP addresses |
| `if` statement | Check whether an IP address exists in a list |
| `.remove()` | Remove specified list elements |
| `.join()` | Convert a list back into a string |
| `.write()` | Save updated data to a file |

## Skills Demonstrated

Python scripting, file handling, data manipulation, automation and access control fundamentals.
