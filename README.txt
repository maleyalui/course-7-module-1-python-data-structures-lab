# Student Data Management System Lab
A memory-efficient Python application designed to handle, filter, and process student records using advanced data structures and functional programming techniques.
## Project Overview
The system manages student data stored as tuples. It leverages Python's Sequences, Sets, and Generators to ensure that data processing remains fast and memory-efficient, even as the dataset scales.
### Key Features

Structured Storage: Uses immutable tuples within lists for reliable record keeping.
Dynamic Filtering: Employs list comprehensions for fast data retrieval.
Unique Attribute Tracking: Utilizes set operations to extract distinct data points like majors or course lists.
Memory Efficiency: Implements generator expressions to process large datasets without exhausting system RAM.

## File Structure

File	Purpose
student_data.py	Contains the core dataset (list of student tuples).
filter.py	Logic for filtering students by specific criteria (e.g., Major).
data_processing.py	Formats and displays student records for the UI.
set_operations.py	Handles unique data attributes using set comprehensions.
data_generator.py	Provides memory-efficient iteration through large records.

## Setup & Installation
Clone the repository:

```sh
git clone https://github.com
cd student-management-system
```

Initialize the environment:
Ensure you have Python 3.x installed. No external dependencies are required.
