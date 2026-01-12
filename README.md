# Assignment Submission- Prathmesh Aphale

This repository contains my submission for the technical assignment covering API data retrieval, data processing and visualization, CSV data import into a database, and demonstration of advanced Python and database programming.

The project is designed to demonstrate practical skills in Python, REST API consumption, SQLite database operations, data processing, and visualization.

Project Overview

This repository contains five main components:

API Data Retrieval and Storage

Student Score Data Processing and Visualization

CSV Data Import into SQLite

Advanced Python Project

Advanced Database System

Each section is implemented as a standalone script that can be run independently.

1. API Data Retrieval and Storage

File: books_api_to_sqlite.py

This script retrieves book data from a public REST API, extracts fields such as title, author, and publication year, and stores the data in a local SQLite database.

Flow:

Fetch data from the Open Library API

Parse the JSON response

Create a SQLite database and table

Insert book records

Retrieve and display stored records

This demonstrates how external APIs can be integrated into a local data store for further use.

2. Student Score Data Processing and Visualization

File: student_scores_analysis.py

This script retrieves student score data from a REST API created using MockAPI. It calculates the average score and generates a bar chart to visualize individual scores and the overall average.

Flow:

Fetch student data from API

Extract names and scores

Compute average score

Generate a bar chart using Matplotlib

This shows how real-time data can be processed and converted into visual insights.

3. CSV Data Import to SQLite

File: csv_to_sqlite.py

This script reads user data from a CSV file and inserts it into a SQLite database.

Flow:

Read users.csv

Create a users table in SQLite

Insert all rows from the CSV file

Verify inserted records

This simulates how external flat-file data can be integrated into a structured database.

4. Advanced Python Code

File: runtime_security_analyzer.py

This is an advanced Python program that simulates container runtime events, detects anomalous behavior using machine learning, converts suspicious activity into vector embeddings, and allows semantic searching of threats.

This project demonstrates:

Data simulation

Machine learning based anomaly detection

Vector embeddings

Semantic search

End-to-end data pipeline in Python

This file is shared as the most complex Python code in this repository.

5. Advanced Database Code

File: security_event_store.py

This script implements a relational database system for container runtime security. It includes multiple linked tables, indexed queries, anomaly tracking, and threat correlation.

It demonstrates:

Relational schema design

Foreign key relationships

Indexing for performance

Anomaly tracking

Analytical queries

This file is shared as the most complex database code in this repository.

How to Run

All scripts are written in Python 3.

Install required packages:

pip install requests matplotlib pandas scikit-learn sentence-transformers faiss-cpu


Run any script individually:

python books_api_to_sqlite.py
python student_scores_analysis.py
python csv_to_sqlite.py
python runtime_security_analyzer.py
python security_event_store.py


For the CSV import script, make sure users.csv is present in the same folder.
