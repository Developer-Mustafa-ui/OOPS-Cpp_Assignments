# Calendar Management System

## Overview

This project file implements a `CalendarDate` class in C++ for handling calendar date operations with validation, date arithmetic, and comparison.

## Features
 
- Date validation for day, month, and year values
- Leap year support
- Display date in `DD-MM-YYYY` format
- Move to the next or previous day
- Add or subtract a number of days
- Overloaded operators for date arithmetic (`+`, `-`, `+=`, `-=`)
- Date difference calculation using `operator-`
- Date equality comparison using `operator==`

## Usage

1. Include the file in a C++ project or use the `CalendarDate` class directly.
2. Create `CalendarDate` objects with default or parameterized constructors.
3. Call methods like `display()`, `nextDay()`, `prevDay()`, `addDays()`, or `subtractDays()`.
4. Use the overloaded operators for arithmetic and date comparisons.

## Notes

- The class currently uses a simple validation mechanism and resets invalid dates to `01-01-2000`.
- The implementation is commented out in the source file, so you may need to uncomment the code before compiling.
