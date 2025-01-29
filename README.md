# Course Average and Grade Calculator

This is a web-based calculator that allows users to input their marks for a set of courses, calculate the average, and assign a grade based on the average. The calculator will prompt the user to enter the number of courses and marks for each course, then calculate the average and display the grade according to predefined thresholds.

## Features

- Prompts the user to input the number of courses.
- Accepts individual marks for each course and validates the input to ensure they are within the range of 0-100.
- Calculates the average of the course marks.
- Assigns a grade based on the average:
  - A+ for 90 and above
  - B for 80 to 89
  - C for 70 to 79
  - D for 60 to 69
  - F for below 60
- Displays all course marks, the calculated average, and the corresponding grade.

## Requirements

- A web browser to run the HTML file.

## How to Use

1. Open the `index.html` file in a web browser.
2. Enter the number of courses when prompted.
3. Input the marks for each course when prompted.
4. The program will display your course marks, average, and the assigned grade.

## Troubleshooting

- If you enter an invalid number of courses (non-numeric or less than 1), the program will notify you of an invalid input.
- If you enter an invalid mark (non-numeric, less than 0, or greater than 100), the program will notify you to reload and try again.

## Example Usage

1. Upon starting the program, it will ask, "How many courses did you finish?"
2. After entering the number of courses, it will prompt for each course mark.
3. After entering all the marks, it will display:
   - The marks for each course
   - The average score
   - The corresponding grade
