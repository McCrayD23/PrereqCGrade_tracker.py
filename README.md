# PrereqCGrade_tracker.py

# Grade_tracker.py

A simple Python project demonstrating the use of getting the data from a .csv file, and converting the information and producing a third file with the summarized grade and student-to-grade information.

# Project Structure

```text
prereq-starter/
├── data/
│   └── students.csv       # Input file containing raw student grades
├── grade_tracker.py       # Main Python script containing processing functions
├── grade_report.txt       # Formatted output report (generated after execution)
├── requirements.txt       # Project dependencies (uses standard built-in modules)
└── README.md              # Setup and usage instructions
----------------------------------------------------------------------------

""" Requirements & Prerequisites """
Python 3.8+ (Uses standard built-in modules: csv and os).

No external libraries or third-party packages are required.

# SETUP INSTRUCTIONS:
Clone or Download the Repository:
Ensure the project folder contains grade_tracker.py and the data/ directory.

# Open your Terminal:
Launch PowerShell or Git Bash on your machine.

Navigate to the Project Folder:
# Change directory to the root of the project where grade_tracker.py is located:
cd path/to/starter

""" How to Run """
Run the script directly using Python:

# Run In PowerShell terminal
python grade_tracker.py

""" What happens when excecuted """
What Happens When Executed:
Reads Data: Loads student scores from data/students.csv.

Processes Statistics: Calculates numeric averages, letter grades (A–F, N/A), overall class metrics, and identifies the Top 5 performing students.

Generates Output: Creates (or updates) grade_report.txt in the root folder with the formatted results.
