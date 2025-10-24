🧩 Overview

The Student Registration System is a JavaFX-based desktop application developed to automate and streamline the process of student enrollment.
It offers an intuitive and user-friendly interface that enables users to input student details, select courses, and store the information securely in a local text file.
The system is lightweight, efficient, and designed primarily for educational institutes or small-scale organizations that require a simple registration management tool.

⚙️ Features

🧾 Student Registration – Add new students by entering their personal details and selecting relevant courses.

💾 File Handling – Automatically stores data in a local text file located within the data folder for future access and record-keeping.

✅ Data Validation – Ensures all mandatory fields are correctly filled before submission, minimizing errors.

🖱️ User-Friendly Interface – JavaFX-based design provides a clean, responsive, and easy-to-navigate interface.

🔁 Smooth Navigation – Enables seamless switching between application screens using intuitive buttons and mouse interactions.

🧱 Project Structure
SRC/
 ├── Back_End/         # Handles backend logic and data processing  
 ├── Front_End/        # Contains GUI components and FXML layout files  
 ├── Resources/        # Includes images, stylesheets, and other resource files  
 └── Data/             # Stores text files containing registered student information  

🖥️ Implementation Details

Language: Java (Object-Oriented Programming)
Framework: JavaFX

Main Components

Main.java – Launches and initializes the JavaFX application environment.

ProjectController.java – Controls user input, event handling, and registration logic.

Student.java – Defines the student model including name, date of birth, and course selection.

project.fxml – Manages the main graphical user interface layout.

statuslogin.fxml – Handles the login interface for secure access.

🧮 Error & File Handling

Uses try-catch blocks to handle exceptions and maintain stable file operations.

Default file storage path: /data/student_records.txt

Supports custom file paths for flexibility and scalability.

🚀 Future Enhancements

🔗 Integration with databases such as MySQL or SQLite for persistent data management.

✏️ Addition of edit/delete functionalities for existing student records.

🧠 Implementation of advanced validation and detailed error handling mechanisms.

🎨 Enhancement of GUI with modern themes, animations, and responsive design.

🏁 Conclusion

The Student Registration System offers a simple yet powerful solution for managing student data efficiently.
With its clean interface, robust backend structure, and JavaFX-driven design, it stands as a practical example of integrating GUI programming with data handling in Java.
This project highlights the potential of JavaFX for creating real-world applications in the field of education and administrative management.

👨‍💻 Developer

Developed by: Noor-ul-Huda
