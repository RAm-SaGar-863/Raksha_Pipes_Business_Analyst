# Raksha Pipes Business Analyst Assignment


## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Generation](#data-generation)
3. [Database Design](#database-design)
4. [Dashboard Creation](#dashboard-creation)
5. [Setup Instructions](#setup-instructions)
6. [Presentation](#presentation)
7. [Screenshots](#screenshots)

## Project Overview
This project involves building a data management and visualization system for Raksha Pipes. It includes generating data, designing a MySQL database, and creating a Power BI dashboard.

## Data Generation
The `data_generation/` folder contains Python scripts to create fake data for Raksha Pipes operations. The script `generate_data.py` generates data for product types, customer details, and sales information.

## Database Design
The `database_scripts/` folder contains SQL scripts for creating and populating the MySQL database. The script `create_tables.sql` sets up the schema with eight related tables. The script `insert_data.sql` populates these tables with the generated data.

## Dashboard Creation
The `dashboard/` folder contains the Power BI dashboard file `raksha_dashboard.pbix`. It visualizes sales trends, product performance, and customer profiles, allowing for interactive data exploration.

## Setup Instructions
1. **Clone the Repository:** `git clone https://github.com/username/Raksha_Pipes_Business_Analyst.git`
2. **Install Dependencies:** `pip install -r requirements.txt`
3. **Run Data Generation Script:** `python data_generation/generate_data.py`
4. **Setup MySQL Database:** Run the SQL scripts to create and populate the database.
5. **Open Power BI Dashboard:** Follow instructions to link the MySQL database and open the dashboard file.

## Presentation
The `presentation/` folder contains the video recording of the project presentation, explaining each step in detail.

## Screenshots
### Data Generation Script
![Data Generation](images/data_generation.png)

### Database Schema
![Database Schema](images/database_schema.png)

### Power BI Dashboard
![Power BI Dashboard](images/power_bi_dashboard.png)

