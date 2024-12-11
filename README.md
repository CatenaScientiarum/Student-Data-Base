Libraries used
<windows.h>.
Used for data input/output (functions printf, scanf, fopen, etc.).
<stdlib.h
Provides functions for working with memory, type conversions (atof) and other basic operations.
<string.h
Used to process strings (for example, strcmp, strncpy, strcspn functions).
<time.h
Provides functionality for working with time and generating unique identifiers.

# Student database

This project is a calculation work with the topic “Student Database”. The program is based on a console application written in the C programming language, which allows you to perform various operations with the database.

## Functionality
The program supports the following functions:
1. **Adding ads** - the ability to create new records in the database.
2. **Deleting ads** - deleting a record by its unique identifier.
3. View ads** - displays all records in the database.
4. Update ads** - changes information about the ad.
5. Saving the database - saves the data to a file.
6. Load database** - reads data from a file.
7. Exporting the database - saves the information in CSV format.
8. Update configuration** - changes the parameters of the configuration file.
9. View ads by city** (depends on the license).
10. View ads by price** (depends on the license).
11. **Print data description** - generates a text description of the database structure.
12. **Generating a license key** (available for the administrator).

## File structure
The project consists of the following main files:
- `RGR.c` - the main file with the program entry point.
- `FNCTS.h` - header file with function declarations.
- `FNCTS.c` - implementation of the main functions.
- `modules.c` - additional modules for working with the database.

## Requirements
- Windows OS
- A compiler that supports C (for example, GCC or Microsoft Visual Studio)
- Console with Windows-1251 encoding for correct display of Cyrillic characters.

## Configuration file
The `RGR.cfg` file is used to store configuration parameters, such as the license key and user data. The program creates this file automatically if it is missing.

## How to run.
1. Compile the program using a compatible compiler.
2. Run the resulting executable file in the console environment.
3. Follow the instructions in the menu to work with the database.

## Licensing features
Some features of the program are available only if you have a license key. If the key is missing or invalid, these features will not be available. The administrator can generate a new key through the program menu.

## Contribution
Project author: **Latyshev Y.M.**.  
Group: **515a**.  
Version: **29**

## License.
This project was created for educational purposes only.

Translated with DeepL.com (free version)