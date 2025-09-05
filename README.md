# Student Information Management System (Python)
This is a Python-based Student Information System that allows users to manage student records with features to add, update, delete, view, save, and load data.

It demonstrates the use of loops, functions, lists, tuples, dictionaries, file handling, and scope in Python.
All records are automatically saved to a CSV file (student_records.csv) and reloaded when the program starts.

# Features
- **Add Students** (ID, name, age, and multiple grades)
- **Display Students**
  - From memory  
  - From saved file  
- **Update Student Information**
- **Delete Student Records**
- **View a Single Student**
- **Save Records to File** (`student_records.csv`)
- **Load Records from File** (automatically on startup)

# File Structure
```
├── student_records.csv    # Stores saved student data
├── student_system.py      # Main Python program
├── README.md              # Documentation
```

# Demonstrated:
### 1. Loops
- **While loop** → Keeps showing the menu until the user exits.  
- **For loop** → Displays all students.  
- **Nested loop** → Prints each student’s grades individually.  
- **Break and Continue** → Used in menu handling.  

### 2. Lists
- Stores **multiple grades** for each student.  
- Supports **accessing, updating, deleting, slicing**.  
- Demonstrates **matrix-like list usage**.  

### 3. Tuples
- Stores **fixed student info** (`student_id`, `name`).  
- Demonstrates tuple operations and built-in functions (`len()`, `max()`, `min()`).  

### 4. Dictionaries
- Dictionary of students where:  
  - **Key = student_id**  
  - **Value = dictionary with name, age, and grades list**  
- Demonstrates `.keys()`, `.values()`, `.items()`.  

### 5. Functions
- Separate functions for each operation:
  - `add_student()`
  - `update_student()`
  - `delete_student()`
  - `view_students()`
  - `view_single_student()`
  - `save_to_file()`
  - `load_from_file()`
- Uses **different types of arguments** (required, keyword, default, variable-length).  
- Includes a **lambda function** for average grade calculation.  
- Demonstrates **pass by reference vs value** with lists.  
- Uses **return values**.  
- Shows **scope of variables** (local vs global).  

### 6. File Handling
- Records are saved to a **CSV file** (`student_records.csv`).  
- Data is **loaded automatically** on startup.  
- Program continues working even if no file exists.

# Screenshots
<img width="1310" height="582" alt="image" src="https://github.com/user-attachments/assets/3e72c7a5-6b45-464c-a10e-73da9b16499a" />
<img width="1314" height="598" alt="image" src="https://github.com/user-attachments/assets/9c37149f-5a7e-4474-9b47-6923cee20130" />
<img width="1308" height="571" alt="image" src="https://github.com/user-attachments/assets/e8ed457c-250d-498a-8e86-51a5edf87c05" />
<img width="1332" height="509" alt="image" src="https://github.com/user-attachments/assets/5ecf1b59-9194-449b-b6ad-333c429c098e" />
<img width="1309" height="593" alt="image" src="https://github.com/user-attachments/assets/17951f79-e2e3-4b8b-a71a-c96beeb4e76c" />
<img width="1349" height="571" alt="image" src="https://github.com/user-attachments/assets/88cc070e-235b-4e52-b042-34987a17e91d" />
<img width="1308" height="555" alt="image" src="https://github.com/user-attachments/assets/1f8f6e6c-3520-45f0-9525-a0d52a51a341" />
<img width="1345" height="599" alt="image" src="https://github.com/user-attachments/assets/4749b067-75be-46b5-a578-c2c57b2425a1" />

  
