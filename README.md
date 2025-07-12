# Personal Information Management (PIM) System

A console-based Personal Information Management system written in C++ for managing personal contact records.

## Overview

PIM_vs14 is a simple database application that allows users to store, edit, and manage personal information including names and addresses. The application uses binary file storage for data persistence.

## Features

- **ADD** - Add new person records with full contact information
- **EDIT** - Edit existing person records by record number
- **PRINT** - Display all stored personal information
- **NEW** - Create new database files
- **OPEN** - Open existing database files
- **HELP** - Display available commands
- **EXIT** - Quit the application

## Data Structure

Each person record contains:
- First Name
- Last Name
- Address Information:
  - House Number
  - Road
  - Amphoe (District)
  - City
  - Zip Code

## Usage

1. Compile and run the application
2. Use the command prompt interface with the following commands:
   - `add` - Add a new person
   - `edit` - Edit an existing person by record number
   - `print` - Display all records
   - `new` - Create a new database file
   - `open` - Open an existing database file
   - `help` - Show command list
   - `exit` - Quit the program

3. When adding or editing records, type `-b` to cancel the operation

## Technical Details

- **Language**: C++
- **Platform**: Windows (Visual Studio 2014 project)
- **Storage**: Binary file format
- **Input Validation**: Duplicate person detection, command validation
- **Memory Management**: Safe string operations using `strcpy_s`, `scanf_s`

## Project Structure

```
PIM_vs14/
├── PIM_vs14.cpp        # Main application entry point
├── pim.h               # Header file with structures and function declarations
├── stdafx.h            # Precompiled header
├── stdafx.cpp          # Precompiled header source
└── targetver.h         # Windows SDK version targeting
```

## Copyright

© 2017 Suttipong. All rights reserved.
