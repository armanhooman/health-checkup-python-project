# 🩺 Health Check-up Desktop App

A Python desktop application built with **Tkinter** for entering laboratory values, comparing them with predefined reference ranges, visualizing results, and exporting entered data to CSV.

This project was created as a practical exercise in GUI development, data handling, visualization, and Python application structure.

> **Important:** This project is for educational purposes only. It is not a medical diagnostic tool and should not be used as a substitute for professional medical advice or laboratory interpretation.

## Features

- Desktop graphical interface built with Tkinter
- Input fields for 22 laboratory parameters
- Comparison against predefined reference ranges
- Highlighting of values outside the configured ranges
- Bar-chart and radar-chart visualizations
- Display of educational condition/recommendation text
- Basic user profile input
- CSV export of entered results
- Custom application icon

## Technologies

- Python
- Tkinter
- NumPy
- Matplotlib
- Pillow
- CSV

## Project Structure

```text
health-checkup-python-project/
├── main.py
├── logo.png
├── requirements.txt
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/armanhooman/health-checkup-python-project.git
cd health-checkup-python-project
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
python main.py
```

## How It Works

The application contains predefined reference ranges for laboratory values such as WBC, RBC, hemoglobin, platelets, glucose, creatinine, lipid markers, thyroid markers, and others.

After the user enters values, the program classifies each entry as below range, within range, or above range. Results can then be viewed in the interface or visualized using charts.

The application can also export the entered values to a local `results.csv` file.

## What I Practiced

This project helped me practice:

- Event-driven programming
- Tkinter widgets and layouts
- Input validation
- Python dictionaries and collections
- File handling with CSV
- Data visualization with Matplotlib
- Numerical work with NumPy
- Organizing a desktop Python application

## Limitations

The reference ranges and educational messages are hard-coded and simplified. Real laboratory interpretation depends on factors such as age, sex, units, laboratory-specific ranges, medical history, medications, and clinical context.

## Author

**Arman Hooman**

Computer Science student focused on Python, SQL, Data Analysis, and AI Engineering.
