# PYTHON-SPACE

A comprehensive collection of Python tutorials, interactive Jupyter notebooks, example modules, and supporting resources designed to help learners build from basic Python fundamentals through advanced topics like exception handling, logging, and database interactions.

## Table of Contents

- [Overview](#overview)  
- [Repository Structure](#repository-structure)  
- [Interactive Notebooks](#interactive-notebooks)  
- [Example Modules](#example-modules)  
- [Logging & Exception Handling](#logging--exception-handling)  
- [Tests & Sample Data](#tests--sample-data)  
- [Getting Started](#getting-started)  
- [Dependencies](#dependencies)  
- [Contributing](#contributing)  
- [License](#license)

## Overview

This repository is organized as a “learning space” for Python enthusiasts. It contains:

- Step-by-step Jupyter notebooks covering day-based exercises (Day1 through Day9) and a primer on Python fundamentals.
- Self-contained Python modules demonstrating core concepts.
- Folders illustrating exception handling patterns, logging configurations, and test cases.
- Sample data files and result logs to support hands-on experimentation.

## Repository Structure

.idea/  
.ipynb_checkpoints/  
Exception/           ← Custom exception‐handling examples  
Question/            ← Coding challenge questions and prompts  
__pycache__/  
anaconda_projects/db/ ← Example database project files  
logging/             ← Logging configuration and examples  
test/                ← Unit tests for modules  
results/             ← Output files and sample results  

Files at root:  
- `.gitattributes`  
- `0.1 Python Fundamentals.ipynb`  
- `Day2.ipynb` … `Day9.ipynb`  
- `SQL.ipynb`         ← SQL notebook (bonus content)  
- `module.py`  
- `module1.py`  
- `module2.py`  
- `app.log`           ← Sample application log  
- `oops.log`          ← Sample exception log  
- `test1.txt`, `test2.txt`, `test3.txt` ← Sample text data  
- `TEST.txt`          ← Sample test data  
- `LICENSE`  
- `README.md`

## Interactive Notebooks

- **0.1 Python Fundamentals.ipynb** – Introduction to Python syntax, variables, control flow, and basic data structures.  
- **Day2.ipynb** … **Day9.ipynb** – Progressive daily exercises covering functions, modules, file I/O, error handling, object-oriented programming, and more.  
- **SQL.ipynb** – Bonus notebook demonstrating how to connect to and query a SQL database from Python.

## Example Modules

- **module.py** – Core functions and examples of procedural code.  
- **module1.py**, **module2.py** – Additional modules showcasing more advanced patterns, including classes and utility functions.

## Logging & Exception Handling

- **logging/** – Configuration files and example scripts illustrating Python’s built-in `logging` module.  
- **Exception/** – Custom exception classes and usage patterns.  
- **app.log**, **oops.log** – Sample log outputs for regular events and caught exceptions.

## Tests & Sample Data

- **test/** – Unit tests for each module to ensure correctness.  
- **Question/** – Contains challenge prompts to practice problem-solving in Python.  
- **test1.txt**, **test2.txt**, **test3.txt**, **TEST.txt** – Sample input files for file-I/O examples.  
- **results/** – Expected output files and demonstration results.

## Getting Started

1. Clone the repository:  
   ```bash
   git clone https://github.com/DevRitesh08/PYTHON-SPACE.git
   cd PYTHON-SPACE
   ```
2. (Optional) Create and activate a virtual environment:  
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter Notebook or JupyterLab to explore `.ipynb` files:  
   ```bash
   jupyter notebook
   ```

## Dependencies

- Python 3.7+  
- Jupyter Notebook  
- (Optional) Additional packages listed in `requirements.txt`

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve content, add new exercises, or update examples.

## 📄 License

This project is licensed under the [Apache License 2.0](LICENSE).

### 🧾 Attribution Requirement

If you use or reference this code in any form (project, blog, research, etc.), you **must** provide proper credit by:
- Mentioning the author: [Ritesh Swami](https://github.com/DevRitesh08)
- Including a link to this repository
