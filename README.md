School Grading System Smart Contract

A decentralized Ethereum smart contract for managing student records and grades, offering functionalities to add students, set grades, and update student information.

This project implements a smart contract on the Ethereum blockchain for managing a school grading system. The smart contract allows adding students, setting grades, retrieving grades, and other operations typical of a school management system.




Features
Add Student: Add a new student to the system with a unique identifier (uid) and name.
Set Grade: Set the grade for a specific student within the range of 0 to 100.
Get Grade: Retrieve the current grade of a student.
Check Student Grade: Verify the validity of a student's grade, ensuring it falls within the valid range.
Update Student Name: Update the name of a student.
Remove Student: Remove a student from the system, including their associated data.
Motivation
The motivation behind this project is to provide a decentralized and transparent solution for managing student records and grades. By leveraging smart contracts on the Ethereum blockchain, the system ensures data integrity, immutability, and accessibility.



Getting Started
To deploy and interact with the smart contract:

Deploy the SchoolGradingSystem.sol contract on Remix or any Ethereum development environment.
Use functions like addStudent, setGrade, getGrade, checkStudentGrade, updateStudentName, and removeStudent to manage student records and grades.
Usage



Prerequisites
Install an Ethereum wallet like MetaMask for interacting with the Ethereum blockchain.
Use Remix or other IDEs compatible with Solidity for smart contract development.
Deployment
Compile SchoolGradingSystem.sol with a Solidity compiler.
Deploy the compiled contract on your chosen Ethereum network (e.g., JavaScript VM, Rinkeby, etc.).
Example
solidity
