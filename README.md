# Online Exam & Testing System Simulator

## Project Description
This project simulates an online testing system by generating and managing exams composed of multiple question types, including true/false, multiple choice, and fill-in-the-blank questions. Each question type is implemented as a separate class and organized using inheritance and hash maps to store and retrieve question data efficiently. The system tracks individual student performance, evaluates each exam, and computes class-wide statistics. A command-line interpreter is used to interact with the system and display student names, exams taken, and submitted answers.

## How It Works
- A question generator creates different question types and stores them using **hash maps**.
- **Inheritance and polymorphism** allow all question types to share a common structure while supporting unique behaviors.
- **Serialization** is used to store and retrieve exam and student data.
- The testing system:
  - Builds and administers exams
  - Records student responses
  - Grades completed exams
  - Calculates per-student and class-level performance metrics
- A **command-line interface (CLI)** outputs a student’s name, exam information, and answers for review.

## Skills Demonstrated
- Object-oriented programming in Java
- Inheritance, interfaces, and polymorphism
- Hash map usage for data storage and retrieval
- Serialization for persistent data handling
- CLI development for user interaction
- Class design and separation of concerns

## Key Takeaways
This project highlights my ability to:
- Design an extensible OOP architecture
- Implement multiple question types using inheritance and interfaces
- Serialize and deserialize complex objects
- Manage large sets of exam and student data using hash maps
- Develop a command-line interpreter to simulate basic system functionality
- Apply Java to build a structured, maintainable, and scalable application
