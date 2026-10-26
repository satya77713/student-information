# 🎓 Student Information Dictionary Using Python

## 📌 Project Overview

The **Student Information Dictionary** is a beginner-friendly Python project developed as part of my internship learning journey at **Veda Technology**.

This project uses a Python dictionary to store student records, search for students using their unique student IDs, add new student information, and update existing records.

## 🎯 Objectives

- Store student information using Python dictionaries.
- Search for a student using their student ID.
- Add new student records.
- Update existing student information.
- Understand key-value pairs and structured data representation in Python.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Platform:** Google Colab / Jupyter Notebook
- **Version Control:** GitHub

## 📂 Project Structure

```text
Student-Information-Dictionary/
├── Student_Information.ipynb
└── README.md
```

## 💻 Student Information

Each student record contains the following details:

- **Student ID:** Unique identifier for each student
- **Name:** Student's name
- **Age:** Student's age
- **Course:** Student's course of study

The project initially stores these sample records:

| Student ID | Name | Age | Course |
|---:|---|---:|---|
| 101 | Rahul | 20 | Python |
| 102 | Priya | 21 | Data Science |
| 103 | Arjun | 19 | AI & ML |

## ✨ Features

### 1. Search Student

Search for a student by entering their student ID. If the ID exists, the program displays the student's name and course. Otherwise, it displays a message indicating that the student was not found.

### 2. Add Student

Add a new student record containing the student's name, age, and course.

Example:

```python
add_student(104, {
    "name": "Vikram",
    "age": 22,
    "course": "Web Development"
})
```

### 3. Update Student Information

Update an existing student's name, age, and course by entering their student ID.

Example:

```python
update_student_info("vijay", 25, "frontend")
```

The function asks for the student ID and updates the corresponding record if it exists.

## 📊 Sample Output

**Searching for a student:**

```text
enter student id : 102
Student 102 is Priya, studying Data Science.
```

**Adding a student:**

```text
Student 104 added successfully.
```

**Updating student information:**

```text
enter student id : 104
Student 104 information updated successfully.
```

After the update, the record for student ID `104` contains the name `vijay`, age `25`, and course `frontend`.

## ▶️ How to Run the Project

1. Clone or download this GitHub repository.
2. Open `Student_Information.ipynb` using Google Colab or Jupyter Notebook.
3. Run the notebook cells in order.
4. Enter a student ID when prompted by the search or update operation.
5. Review the output to see the student records and changes.

## 📚 Learning Outcomes

Through this project, I practiced:

- Creating and accessing Python dictionaries.
- Working with nested dictionaries.
- Searching for records using dictionary keys.
- Adding new key-value pairs.
- Updating existing dictionary values.
- Using conditional statements and functions.
- Displaying student information using formatted strings.

## 🔮 Future Improvements

- Prevent duplicate student IDs when adding records.
- Display an error message when an update request uses an unknown student ID.
- Add a function to delete student records.
- Add an option to display all student records in a readable format.
- Validate student information before adding or updating records.

## 👨‍💻 Author

**Satya**

GitHub: [satya77713](https://github.com/satya77713)

---

*Created as part of my Python internship learning journey at Veda Technology.*
