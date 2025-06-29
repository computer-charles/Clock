# Clock Project

This is a simple C++ console application that demonstrates how to manage and display time using both 12-hour and 24-hour clock formats. The program allows a user to increment the time by one hour, one minute, or one second through a simple text-based menu.

## Features

- Keeps track of time using a `Clock` class.
- Displays the current time in both 12-hour and 24-hour formats side by side.
- Automatically rolls over hours, minutes, and seconds when limits are reached.
- Provides a clear menu for the user to interact with the clock.

## How It Works

The program starts with the time set to 00:00:00. A user can choose from a menu to add one hour, one minute, or one second. The updated time is shown each time in both formats. The clock automatically handles the overflow of seconds to minutes and minutes to hours.

## Build and Run

To compile and run the program, follow these steps:

1. Make sure you have a C++ compiler installed (such as `g++`).
2. Clone this repository or copy the code into a `.cpp` file (for example, `clock.cpp`).
3. Open a terminal and navigate to the directory containing your file.
4. Compile the program:
