# University Database Management

## Description

This repository contains code for managing a university database using SQLite. It provides functionality for generating sample data for students, lecturers, and courses, as well as updating the student count for each course.

## Requirements

To run this code, you need the following:

- Python 3.x
- SQLite3
- Faker

## Functionality

The notebook provides the following functions:

- `Generate_DB(N)`: Generates a sample university database with `N` students, lecturers, and courses. It populates the database with randomly generated data using the Faker library.
- `generate_people(name, N, status)`: Generates `N` people with the given `name` and `status`. The `status` parameter can be one of the following: `'worker'`, `'student'`, `'lecturer'` default random with and no name needed.
- `get_table_data()`: Retrieves and displays the data from all tables in the database.
- `get_data_by_id(id)`: Retrieves data for a specific ID from the `Contact`, `Students`, and `lecturers` tables.
- `get_data_by_name(name)`: Retrieves data for a specific name from the `Contact`, `Students`, and `lecturers` tables.
- `delete_db()`: Deletes the database file `university.db`.
