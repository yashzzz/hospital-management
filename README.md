Hospital Management System


This project is a simple hospital management system written in C++. It uses a linked list queue structure to manage patient information such as ID, first name, last name, age, blood group, and gender.

Features

Add Patient: Add a new patient to the queue.
Remove Patient: Remove a patient from the queue.
List Patients: Display the list of all patients.
Search Patient: Search for a patient by ID.
Input Validation: Ensures valid blood group input.

How to Run

Prerequisites

C++ Compiler (e.g., g++, clang++)
Git (to clone the repository)
Steps to Run
Clone the repository:

git clone 
cd <repository_directory>
Compile the program:

g++ hospital.cpp -o hospital
Run the executable:

./hospital

Usage

Upon running the executable, follow the on-screen prompts to perform various operations like adding a new patient, listing all patients, searching for a patient, etc.

Functions
input(): Takes input for a new patient.
insertatend(): Inserts a new patient at the end of the queue.
insertatbeg(): Inserts a new patient at the beginning of the queue.
getpatientout(): Removes a patient from the queue.
listofpatients(): Lists all patients.
search(int): Searches for a patient by ID.

Contributing

Feel free to fork this repository and contribute by submitting a pull request. Please ensure that your contributions adhere to the coding standards used in this project.

License
This project is licensed under the MIT License.

