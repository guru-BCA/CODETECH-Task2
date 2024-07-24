# CODETECH-Task2

**Name**: Guru Prasanth S  
**Company**: CODE TECH  
**ID**: CT4PP3076  
**Domain**: Python Programming  
**Duration**: 4 weeks  
**Mentor**: Neelam Harish  


# Student Grade Calculator

## Overview

The **Student Grade Calculator** is a Python program that allows users to manage and track student grades across various subjects or assignments. The program calculates the average grade, determines the corresponding letter grade, and calculates the GPA based on the entered grades.

## Features

- **Input Grades**: Add grades for different subjects or assignments.
- **Calculate Average**: Automatically calculate the average grade for the student.
- **Letter Grade**: Determine the letter grade (A, B, C, D, F) based on the average grade.
- **GPA Calculation**: Calculate the GPA using a standard 4.0 scale.
- **Report Generation**: Display a detailed report of the student's grades, average grade, letter grade, and GPA.

## Requirements

- Python 3.x

## How to Use

1. **Run the Program**:
   - Make sure Python is installed on your machine.
   - Save the program script as `student_grade_calculator.py`.
   - Run the script using the command: `python student_grade_calculator.py`.

2. **Enter Student Information**:
   - You will be prompted to enter the student's name.

3. **Enter Grades**:
   - You can enter grades for different subjects or assignments.
   - To stop entering grades, type 'done' when prompted for the subject.

4. **View Report**:
   - After entering all the grades, the program will display a detailed report including:
     - Student's name
     - Grades for each subject
     - Average grade
     - Corresponding letter grade
     - GPA on a 4.0 scale

## Example Usage

```
Enter the student's name: John Doe
Enter the subject (or 'done' to finish): Math
Enter the grade for Math: 85
Enter the subject (or 'done' to finish): Science
Enter the grade for Science: 90
Enter the subject (or 'done' to finish): English
Enter the grade for English: 78
Enter the subject (or 'done' to finish): done
```

Output:
```
Student: John Doe
Grades:
  Math: [85]
  Science: [90]
  English: [78]
Average Grade: 84.33
Letter Grade: B
GPA: 3.00
```

## Additional Information

- The program supports adding multiple grades for each subject.
- The GPA calculation is based on the following scale:
  - A: 4.0
  - B: 3.0
  - C: 2.0
  - D: 1.0
  - F: 0.0

## Contributing

If you have suggestions or would like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).

