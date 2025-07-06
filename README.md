# Online Judge Database System

This project contains the design and implementation of a relational database system for an online coding platform. It supports core functionalities such as user management, problem storage, contest hosting, and submission tracking.

## Technologies Used
- PostgreSQL
- SQL (DDL & DML)
- ER Modeling

## Features
- Normalized relational schema supporting:
  - Users (participants, admins)
  - Problem statements with metadata and tags
  - Contests and authored problems
  - User submissions with code, status, and analysis
  - Test cases, output sets, solutions, discussions, and posts
- Entity-Relationship (ER) design formalized and documented
- DDL and DML scripts with realistic data

## Files
- `DB_Coding_Platform.pdf` – Final project report with schema explanation and ER diagram.
- `DDLscript.txt` – SQL DDL script to create the entire schema and enforce constraints.
- `INSERT.txt` – SQL script to populate the database with complete test data for all tables.
- `sqlQUERIES.txt` – Set of advanced SQL SELECT queries covering leaderboards, contest statistics, user profiles, and analytics.

## Schema & Data
- All schema definitions are created using `DDLscript.txt`, which includes key constraints, foreign keys, and data integrity checks.
- The schema is initialized under the `CodingPlatform` schema namespace.
- Realistic data including users, problems, contests, submissions, and community interactions is inserted using `INSERT.txt`.

## Query Set
- `sqlQUERIES.txt` includes 20+ curated SQL queries for:
  - Generating leaderboards
  - Analyzing user performance
  - Tracking submission trends
  - Extracting problem and discussion insights

