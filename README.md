# Periodic Table Database

A command-line application that queries chemical element information from a PostgreSQL database, built as part of the [**FreeCodeCamp Relational Database Certification**](https://www.freecodecamp.org/learn/relational-database/).

## About

This project provides an interactive way to retrieve detailed information about chemical elements from the periodic table. Users can search by atomic number, element symbol, or element name to get comprehensive data including atomic mass, melting point, boiling point, and element type.

## Tech Stack

- **Database**: PostgreSQL
- **Scripting**: Bash

## 🚀 How to Run

1. **Set up PostgreSQL database:** `psql --username=freecodecamp --dbname=postgres < periodic_table.sql`.
1. **Make the script executable:** `chmod +x element.sh`.
1. **Run queries:**
```bash
./element.sh 1 # Query by atomic number
./element.sh H # Query by symbol
./element.sh Hydrogen # Query by name
```

## freeCodeCamp Requirements

This project fulfills all freeCodeCamp requirements.
