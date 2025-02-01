# EduTrack

## Description
The **EduTrack** is a Python-based application that allows users to efficiently manage student records, including adding new students, tracking their marks, and generating class-wise reports. The program is built using **Tkinter** for the graphical user interface (GUI) and **Pandas** for data management and analysis. Additionally, **Matplotlib** is used to visualize the class-wise average marks.

## Features
- **Add Student Data**: Users can input student details such as Roll Number, Name, Class, and Marks.
- **Data Persistence**: The program saves student data in a CSV file (**students.csv**) to ensure records are maintained across sessions.
- **Duplicate Roll Number Check**: Prevents duplicate entries by verifying the Roll Number before adding a student.
- **Generate Reports**: Displays a bar chart showing the average marks per class.
- **CSV File Loading**: Users can load and view student data from an external CSV file.
- **GUI for Adding Students**: A Tkinter-based graphical interface makes adding students easy and user-friendly.
- **Error Handling**: Includes robust error handling for invalid inputs and missing files.

## Dependencies
Ensure you have the following Python libraries installed before running the project:
```bash
pip install pandas matplotlib
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/edutrack.git
   cd edutrack
   ```
2. Run the script:
   ```bash
   python Class_12_Project.py
   ```
3. Follow the on-screen menu to add students, generate reports, or load CSV files.

## Future Enhancements
- Implement a database system (SQLite or MySQL) for better data management.
- Add more visualization options for student performance analysis.
- Improve the GUI with additional features like updating and deleting student records.

## License
This project is open-source and available under the **MIT License**.

---
Feel free to contribute to this project by submitting issues or pull requests!

