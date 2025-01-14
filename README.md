# FIFA 2014 World Cup Graph Database Project

## Project Overview
This project focuses on designing and querying a graph database for the FIFA 2014 World Cup dataset. The project explores the capabilities of graph databases and uses Neo4j to analyze and answer complex queries about player data. It also demonstrates the ETL process, property graph design, and Cypher querying for insights.

## Dataset Description
The dataset includes detailed information about players who participated in the 2014 FIFA World Cup, such as:
- **Player Details**: Name, age, position, jersey number, height, and international goals.
- **Club Information**: Club name and country.
- **National Team Stats**: Caps and whether the player plays in their home country.

## Key Features
1. **Graph Database Design**:
   - Designed a property graph using the Arrows App to represent players, clubs, and countries as nodes, with relationships capturing player affiliations and national team participation.

2. **ETL Process**:
   - Transformed the dataset into structured CSV files for import into Neo4j.
   - Addressed potential performance issues by creating filtered datasets for optimized querying.

3. **Cypher Querying**:
   - Wrote queries to answer questions such as:
     - Which club does a specific player play for?
     - What is the jersey number of a player with a given ID?
     - Find all players at a specific club or position.
     - Discover the top 5 countries with the highest average international goals.
   - Designed additional custom queries for unique insights.

4. **Graph Data Science Discussion**:
   - Discussed the advantages of graph databases over relational databases for this dataset.
   - Explored practical applications of Graph Data Science, such as identifying key influencers in a network.

## Technologies Used
- **Neo4j**: Graph database platform for data storage and querying.
- **Arrows App**: For designing the property graph schema.
- **Python/Excel**: For preprocessing the dataset into CSV format.
- **Cypher**: Query language for interacting with the graph database.

## Project Files
- **`cypher_scripts.txt`**: Contains all Cypher scripts for graph creation and querying.
- **CSV Files**:
  - `original/`: Unfiltered dataset in CSV format.
  - `filtered/`: Optimized dataset with reduced records for performance.
- **`design.png`**: Screenshot of the graph schema designed in the Arrows App.
- **`project_report.pdf`**: Comprehensive report including:
  - Graph design rationale.
  - ETL process description.
  - Query screenshots and results.
  - Comparison of graph and relational databases.
  - Application of Graph Data Science.
- **`queries_results/`**: Screenshots of executed queries and their outputs.

## How to Run
1. **Setup Neo4j**:
   - Install Neo4j Desktop or start a Neo4j instance.
   - Create a new project and database.

2. **Import Data**:
   - Use the Cypher scripts in `load_script.txt` to create nodes and relationships by importing CSV files.

3. **Run Queries**:
   - Execute the `cypher_scripts.txt` file to analyze the data and answer the project questions.

## Key Insights
- Demonstrates how graph databases simplify complex relationships and queries.
- Highlights the efficiency of Cypher for retrieving meaningful insights.
- Showcases the practical application of data-driven decision-making in sports analytics.

## Acknowledgments
- University of Western Australia - CITS3401/CITS5504 course.
- FIFA 2014 World Cup dataset for providing the basis for this project.

---
