# Student Performance Analytics System

A Python mini project that analyzes student marks and attendance using **Python, NumPy, Pandas, and CSV**.

## Features
- Reads student information from `students.csv`
- Validates required columns and checks that marks/attendance are between 0 and 100
- Calculates each student's total and average marks
- Assigns pass/fail status (a student passes only if every subject mark is at least 40)
- Assigns grades using the rules below
- Prints overall statistics, subject-wise analysis, top five students, department-wise averages, and attendance summary
- Exports the analyzed records to `student_results.csv`

## Grading rules
| Condition | Grade |
|---|---|
| Fails any subject (below 40) | F |
| Average >= 90 | A+ |
| Average >= 80 | A |
| Average >= 70 | B |
| Average >= 60 | C |
| Average >= 50 | D |
| Average below 50, but passes all subjects | E |

## Project files
- `main.py` — main Python program
- `students.csv` — sample input dataset (30 demonstration records)
- `student_results.csv` — generated output file (created when the program runs)
- `requirements.txt` — required Python packages
- `Student_Performance_Analytics_Report.pdf` — project report

## Requirements
- Python 3.9 or newer
- pip

## Run the project
1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run:
   ```bash
   python main.py
   ```
5. Check the terminal summary and the generated `student_results.csv`.

## Upload to GitHub
1. Sign in at [GitHub](https://github.com/).
2. Create a new repository, for example `student-performance-analytics`.
3. Upload the files in this folder, or use GitHub's **Add file → Upload files** option.
4. Commit the changes.

## Dataset note
The CSV contains demonstration data for learning and project evaluation. Replace it with authorized student data if needed; do not upload private student information publicly.
