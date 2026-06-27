# Airbnb Rental Management and Data Analysis System using PostgreSQL

## 📌 Project Overview
This project designs and implements a relational database system to manage and analyse 
Airbnb rental listing data using PostgreSQL. It demonstrates how a structured database 
can store, organize, and retrieve property data to support real-world business 
decision-making.

**Academic Project | MBA – Business Analytics | GLS University | Semester IV | 2025-26**  
**Guide:** Dr. Amish Soni

---

## 🎯 Objectives
- Design and implement an Airbnb rental database using PostgreSQL
- Perform SQL-based data retrieval and analysis on property listings
- Identify top-rated and highest-priced properties for business insights
- Analyse property distribution and availability across multiple locations

---

## 🛠️ Tools & Technologies
| Tool | Purpose |
|---|---|
| PostgreSQL 18 | Database creation, management & querying |
| pgAdmin 4 | GUI interface for PostgreSQL |
| SQL | Data insertion, retrieval, filtering & analysis |

---

## 🗄️ Database Schema
Table Name: airbnb

| Column | Data Type | Description |
|---|---|---|
| host_name | VARCHAR(100) | Name of the property host |
| property_name | VARCHAR(100) | Name of the Airbnb listing |
| property_type | VARCHAR(50) | Type: Apartment, Villa, Cottage, etc. |
| location | VARCHAR(50) | City/location of the property |
| price_per_night | DECIMAL(10,2) | Nightly rental price (INR) |
| rating | DECIMAL(2,1) | Customer rating (out of 5) |
| availability | BOOLEAN | TRUE = Available, FALSE = Booked |

---

## 📊 SQL Queries Performed
1. Create table and insert data (50 records)
2. Filter listings by location (e.g., Goa)
3. Average price per night for each location
4. Most expensive Airbnb property
5. Total number of properties per location
6. Listings with price between 4000 and 6000
7. Top 3 highest-rated properties
8. Count of locations with rating 4.5 or higher
9. Average rating by property type
10. Number of available vs unavailable properties
11. Highest-priced property in each location
12. Locations with average rating greater than 4.5
13. Total revenue potential per location
14. Second highest priced property
15. Locations with more than 3 properties
16. Average price of available properties per location
17. Total properties by property type
18. Locations with both available and unavailable properties
19. Top-rated property in each property type
20. Properties rated above their location average

---

## 🔍 Key Findings
- PostgreSQL efficiently handled all 50 records with fast query execution
- Goa had the highest number of listings among all locations
- Villas and Apartments achieved the highest average customer ratings
- 31 out of 50 properties were available (62% availability rate)
- Andaman had the highest average price per night across all locations
- Correlated subqueries successfully identified above-average properties per city

---

## 📁 Files in This Repository
- airbnb_create_table.sql — Table creation query
- airbnb_insert_data.sql — Data insertion (50 records)
- airbnb_analysis_queries.sql — All 20 analysis queries
- project_report.pdf — Full MBA project report

---

## 👥 Team Members
| Enrollment No. | Name |
|---|---|
| 202400620010201 | Burhanuddin Gadiwala |
| 202400620010205 | Burhanuddin Gangardiwala |
| 202400620010233 | Isha Haria |
| 202400620010300 | Vanshika Majithia |
| 202400620010326 | Sahaj Mitra |
| 202400620010513 | Raj Shah |
| 202400620010551 | Jeet Solanki |

---

## 📚 References
- Cheng & Foley (2019) - Algorithmic management in Airbnb
- Dolnicar (2018) - Peer-to-peer accommodation networks
- Deboosere et al. (2019) - Multilevel hedonic analysis of Airbnb pricing
- PostgreSQL Official Documentation - postgresql.org
