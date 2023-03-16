# University Module Management System

This is a simple university module management system implemented using classes `Student`, `Module`, and `StudentSupportOffice`. The system allows you to manage students' enrollment and unenrollment in university modules.

## Class Descriptions

### Student

The `Student` class represents a student and stores the student ID. The class provides a human-friendly representation of the student (toString()) and supports total ordering of students (students are Comparable).

### Module

The `Module` class represents a university module and stores the module ID, a class list (an array of enrolled students with default capacity for 5 students), and the current size of the class list. The class allows students to be enrolled if they are not already in the class list (while maintaining the class list in ascending order based on student ID) and unenrolled (the class list must not have gaps that "break" the sequence of enrolled students). The class provides a human-friendly representation (toString(), improving printouts by ignoring empty elements within the class list).

### StudentSupportOffice

The `StudentSupportOffice` class is responsible for creating three modules: "CIS2206", "CIS2360", and "CIS2205" and creating five students: "U0000001", "U0000002", "U0000003", "U0000004", "U0000005". The class enrolls and unenrolls students to modules according to the given scenarios.

## Usage

1. Clone this repository
2. Compile and run the main class (`StudentSupportOffice`)
3. The initial enrollment of students in modules will be displayed
4. The updated enrollment of students in modules after changes will be displayed

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch with your feature or bug fix
3. Commit your changes and push them to your fork
4. Create a pull request to this repository

## License

This project is released under the MIT License. Please see the `LICENSE` file for more details.
