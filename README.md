
# Python-Java Integrated Application

## Overview
This project demonstrates the integration of a Python Flask application with a Java backend using the Py4J library. The application processes data and performs calculations by delegating tasks to the Java module.

## Requirements
- Python 3.x
- Flask library
- Py4J library
- Java Development Kit (JDK)

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install Python dependencies:
   ```bash
   pip install flask py4j
   ```

3. Start the Java backend:
   - Ensure Py4J is configured in the Java application.
   - Compile and run the Java application.

4. Start the Python server:
   ```bash
   python app.py
   ```

5. Test API endpoints:
   - `POST /process-data` for data processing.
   - `POST /perform-calculation` for calculations.

## Java Backend
The Java backend should expose methods:
- `processData(String input)`
- `performCalculation(int num1, int num2)`

## License
MIT License
