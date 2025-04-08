# NYPD Crime Data Warehouse and Analytics Project

Project Overview

Designed and implemented an end-to-end data analytics solution utilizing the NYPD Arrest Data (Year-to-Date) dataset with focus on dimensional modeling, ETL pipeline development, and crime pattern visualization. The project transformed raw arrest data into actionable insights to support law enforcement resource allocation and public safety initiatives.
Technical Implementation
Data Architecture & Modeling

    Designed a comprehensive dimensional model after thorough analysis of business requirements
    Identified appropriate grain level for fact tables to optimize for crime pattern analysis
    Created logical and physical data models using E/R Studio with proper dimension hierarchies
    Implemented a snowflake schema optimized for complex crime analytics queries

Data Engineering

    Profiled 260,000+ rows of NYPD crime data using Alteryx to identify data quality issues
    Documented data inconsistencies and developed targeted cleaning strategies
    Engineered an automated data pipeline in Azure Data Factory (ADF) to:
        Extract raw arrest data from NYC Open Data portal
        Apply data transformation rules to handle inconsistencies
        Load cleansed data into Snowflake staging tables
    Implemented data quality validation checks throughout the pipeline

Business Intelligence & Visualization

    Developed interactive Tableau dashboards to visualize crime patterns
    Created time-series analysis capabilities to track crime trends by day, week, month, and year
    Built geographic visualizations of arrest distributions across NYC boroughs and precincts
    Implemented demographic analysis tools to examine crime patterns by age, race, and gender
    Designed predictive analytics to identify potential high-crime areas

Business Value Delivered

The solution enabled stakeholders to:

    Identify peak crime periods to optimize police resource allocation
    Track the evolution of crime types over time to inform prevention strategies
    Compare felony vs. misdemeanor rates across different precincts
    Analyze demographic patterns in arrests to support community engagement initiatives
    Use historical data to predict potential high-risk areas for proactive policing
    Provide NYC residents and visitors with safety insights for trip planning

Technical Skills Demonstrated

    Dimensional data modeling (Snowflake Schema)
    Data profiling and quality assessment (Alteryx)
    Cloud-based ETL (Azure Data Factory)
    Data warehousing (Snowflake)
    SQL development for analytical queries
    Data visualization (Tableau)
    Predictive analytics for crime pattern identification
    Version control and collaborative development (GitHub)
    Comprehensive project documentation

This project demonstrates comprehensive data warehouse implementation skills with particular emphasis on transforming public safety data into actionable insights for both law enforcement and the public.



