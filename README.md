# Calendar Application

## Overview

This is a C-based console application that displays a calendar for any specified month and year starting from 1945. The application allows users to:

- View the calendar of any month of a particular year.
- Navigate through months and years using arrow keys.
- Jump to a specific month and year.
- Exit the program using the ESC key.

The calendar display includes weekday names and the correct alignment of dates, with Sundays highlighted for easier reference. The application is designed to run on Windows, utilizing the `windows.h` library for console manipulation.

## Features

- **Interactive Navigation**: Use arrow keys to move between months and years.
- **Jump to Specific Date**: Press `P` to enter a specific year and month.
- **Colored Display**: Different colors are used for weekends and weekdays to enhance readability.
- **Simple Interface**: A clean and simple text-based interface.

## Requirements

- Windows OS
- C Compiler (e.g., GCC, MSVC)

## How to Run

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/Calendar-Application.git
    cd Calendar-Application
    ```

2. **Compile the Program**:
    Compile the program using a C compiler. For GCC:
    ```bash
    gcc -o calendar calendar.c -lconio
    ```

3. **Run the Program**:
    ```bash
    ./calendar
    ```

4. **Use the Program**:
   - **Input the Year and Month**: At the prompt, enter the desired year and month to view the calendar.
   - **Navigate**: Use the arrow keys:
     - `UP` and `DOWN` to change the month.
     - `LEFT` and `RIGHT` to change the year.
   - **Jump to a Specific Date**: Press `P` to input a new year and month.
   - **Exit**: Press `ESC` to exit the program.

## Code Structure

- **`main()`**: The main function handles user input and controls the flow of the program.
- **`gotoxy(int x, int y)`**: Positions the cursor at the specified coordinates on the console screen.
- **`SetColor(int ForgC)`**: Sets the text color in the console.
- **`display(int nyr, int nmonth, int tdays, int days[])`**: Displays the calendar for the given month and year.
- **`getKey()`**: Captures the arrow keys and other key inputs.
- **`calendar(int nyr, int nmonth)`**: Calculates the starting day of the month and the total days to display the calendar.

## Contribution

Feel free to fork this repository, open issues, and submit pull requests. All contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Screenshots
### Input
![Calender1](https://github.com/Kushalobroy/Calender-Using-C/assets/92447922/11838a74-ee21-481f-b980-05738691561f)
### Result
![Calender](https://github.com/Kushalobroy/Calender-Using-C/assets/92447922/e25a87b4-8412-41fc-855e-17cb124d0a7e)
