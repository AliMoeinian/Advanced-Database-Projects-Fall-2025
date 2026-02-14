# Advanced Database Projects - Isfahan University

This repository contains 5 semester projects and 1 final project that I designed as a Teaching Assistant (TA) for the Advanced Database course at Isfahan University. The course was taught by Dr. Mohammad Ali Nematbakhsh and targeted master's students in Computer Engineering. These projects cover advanced topics in databases, data engineering, and big data systems, blending theoretical explanations with practical implementations. Each project includes descriptive questions and hands-on tasks to build skills in database design, processing, and analysis. The original PDFs are included for reference.

## Projects Overview

### Project 1: Complex Data Types
Explores modeling and analyzing JSON data in modern databases for social networks, including advantages/drawbacks compared to relational schemas, JSON querying with tools like JSONPath and LlamaIndex APIs, and RDF for knowledge graph construction. Also compares XML and JSON in terms of readability, verbosity, use cases, and data representation for scenarios like book information with nested structures.

### Project 2: Big Data
Covers the origins and 3Vs of Big Data, Hadoop file system architecture (HDFS with NameNode/DataNode/replication and single point of failure analysis), MapReduce phases/advantages/limitations with examples, and handling small files in distributed systems. Includes practical MapReduce programming on an E-Commerce dataset for total sales by country and synthetic Twitter data for top trending hashtags based on engagement metrics.

### Project 3: Data Analytics
Focuses on data integration from heterogeneous sources (CSV/JSON/SQL) with global schema design, attribute mapping, and conflict resolution; star schema for data warehousing with fact/dimension tables like Fact_Sales and Dim_Product. Implements Medallion Architecture using Python/Pandas on a coffee sales dataset, covering bronze (raw ingestion), silver (cleaning/enrichment), gold (aggregations), and business analysis queries for revenue insights.

### Project 4: B+ Tree
Explains B+ Tree concepts and their use in database indexing, with insertion/deletion examples and structures for sequences. 

### Project 5: Query Processing + Query Optimization + Transaction
Details query processing steps (parsing, translation, optimization, evaluation) with examples, relational algebra for efficient queries on a bank database, and sorting cost calculations for large relations. Covers join size estimation/strategies, ACID properties with definitions/importance/examples, transaction state sequences, serializability (conflict vs. view), and concurrent execution analysis for non/serializable schedules.

### Final Project: Intelligent Data Analysis Platform for Uber
Analyzes a 2024 Uber transactions dataset (148,770 records) with feature descriptions, data types, and logical relationships; implements Medallion Architecture for data pipeline from raw to refined layers. Builds a full platform with database design, analytics, and intelligent Q&A using Text-to-SQL via free models (e.g., OpenRouter), including UI development with tools like React or Streamlit for end-to-end data processing and querying.

## Usage
- These can be used as teaching resources, student assignments, or self-study materials.
- Note: Some projects reference external datasets (e.g., Kaggle links) and tools (e.g., Jupyter Notebooks for practical sections).

---

*Designed by Ali Moeinian as TA for Advanced Database, Isfahan University.*
