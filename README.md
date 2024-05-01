# Class Name Updater Script

## Overview
This script is designed to update class names across multiple HTML, JavaScript, and CSS files. It ensures that only exact matches of the class name are updated, preventing unintended changes to similarly named classes.

## Features
- Supports HTML, JS, and CSS files.
- Matches complete class names to avoid replacing substrings of larger class names.
- Distinguishes between CSS class syntax and other uses in HTML/JS.

## System Requirements
- Unix-like operating system (Linux, macOS)
- Bash shell
- Standard Unix tools installed (`grep`, `sed`, `xargs`)

## Usage
To use the script, you need to provide the old class name, the new class name, and the path to the directory containing the files you want to update.

### Syntax
```bash
./rename.sh oldClassName newClassName path/to/directory
