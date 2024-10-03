# School Grading System Contract

## Description

This project is a Solidity smart contract for managing a school grading system. It includes various functions for adding students, setting their grades, and performing data integrity checks. The contract ensures that each student is uniquely identified by their student ID and UID, and their grades are maintained within acceptable bounds.

## Features

- **Add Student Function** (`addStudent`): Adds a new student to the system with a unique ID and UID.
- **Set Grade Function** (`setGrade`): Allows setting a grade for a specific student.
- **View Grade Function** (`getGrade`): Retrieves the grade of a specific student.
- **Remove Student Function** (`removeStudent`): Removes a student from the system.
- **Check Grade Function** (`checkStudentGrade`): Verifies that a student's grade is within the correct range.
- **Update Name Function** (`updateStudentName`): Allows updating the name of a student.

## Getting Started

### Installing

To use the `SchoolGradingSystem` contract, follow these steps:

1. Copy the code provided in the code file.
2. Paste the code into a development environment like Remix.
3. Compile the contract using Solidity version 0.8.0 or higher.
4. Deploy the contract on the Ethereum network or a test network like Ropsten or a local blockchain.

### Executing Program

1. Deploy the contract using Remix or another Solidity environment.
2. Use the `addStudent` function to add new students by providing a unique ID, UID, and name.
3. Set or retrieve a student's grade using `setGrade` and `getGrade` functions, respectively.
4. Use the `removeStudent` function to remove students from the system when necessary.

### Example Usage

- **Add Student**: Use the `addStudent` function to add a student with a unique student ID and UID.
- **Set Grade**: Assign a grade (0-100) to a student using the `setGrade` function.
- **Get Grade**: View the grade of a specific student with the `getGrade` function.
- **Remove Student**: Safely remove a student from the contract using the `removeStudent` function.
- **Check Grade**: Ensure data integrity using `checkStudentGrade`, which asserts that the student's grade is between 0 and 100.

## Help

For any issues or questions about the `SchoolGradingSystem` project, feel free to contact the author.

## Authors

Harpreet
