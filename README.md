# Student Performance Analysis and Report Generator

This Python project analyzes student performance based on hours studied, attendance percentage, and pass/fail outcomes. It generates visualizations and exports a professional PDF report containing statistical summaries and charts.

---

## Features

- Load student performance data using `pandas`
- Compute key statistics:
  - Number of students passed vs failed
  - Average hours studied
  - Average attendance of students who passed
- Create data visualizations:
  - Bar chart of pass/fail outcomes
  - Histogram of hours studied
  - Scatter plot of attendance vs hours studied (colored by outcome)
- Export results and visualizations to a formatted PDF using `FPDF`

---

## Project Structure

project-folder/
│
├── student_report.py # Main Python script
├── student_report.pdf # Auto-generated PDF report
├── pass_fail_bar_chart.png # Bar chart (saved image)
├── hours_studied_histogram.png # Histogram (saved image)
├── scatter_hours_vs_attendance.png# Scatter plot (saved image)
├── README.md # Project documentation (this file)

yaml
Copy
Edit

---

## Requirements

Make sure you have the following Python packages installed:

```bash
pip install pandas matplotlib fpdf
How to Run
Clone or download the project files.

Open your terminal in the project directory.

Run the script:

bash
Copy
Edit
python student_report.py
The script will:

Print summary statistics to the console

Generate three charts and save them as .png

Create a student_report.pdf with data and visualizations

Output: PDF Report Includes
Title and summary statistics

Full student performance table

Visualizations:

Pass vs Fail Bar Chart

Hours Studied Histogram

Hours vs Attendance Scatter Plot

Learnings
This project is ideal for learning how to:

Perform data analysis with pandas

Visualize data using matplotlib

Automate report generation using FPDF

Contact
For feedback or questions, feel free to contact the project owner.
SEGAI BRYTON MAMPSHIKA
SINESIPHO SIBULO
ONDELA CITYWAYO
MTHUNZI MALEBADI
VHUHWAVHO MAWELA MASALESA
