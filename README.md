# PostGIS Spatial Database Workflows
**Student:** Lauren Bolton  
**Course:** GIST 604B – Open Source GIS  
**Module 4:** PostGIS Database Orchestration  
**University of Arizona**  

## Project Description
This project demonstrates spatial database workflows using PostgreSQL and PostGIS in a containerized environment. It focuses on developing SQL queries to analyze New York City datasets, combining demographic and spatial analysis within a relational database.

## Tools and Technologies
- PostgreSQL
- PostGIS
- Docker
- SQL
- GitHub Codespaces

## What I Did
- Set up a PostGIS-enabled PostgreSQL database using Docker in a cloud development environment
- Imported NYC spatial datasets (neighborhoods, census blocks, streets, and subway stations)
- Developed SQL queries for demographic analysis, including calculating population statistics by borough
- Performed geometry and spatial relationship queries, including feature intersections and distance-based analysis
- Executed spatial joins and multi-table queries to analyze relationships between population and infrastructure

## How to View/Run
- Start the database container with `docker compose up -d`
- Connect to the PostgreSQL/PostGIS database
- Import spatial data into the database
- Run SQL queries from the **sql** folder

## Repository Structure
      .
      ├── .devcontainer            # Container configuration for PostGIS environment 
      ├── sql/                     # SQL scripts for queries 
      ├── demos/                   # NYC spatial datasets used in PostGIS 
      ├── docker-compose.yml     
      └── README.md                # Project documentation 

