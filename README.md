# MusicStore-Analytics-DB
A PostgreSQL music store database designed for data analysis and business insights. Explore customer behaviour, sales trends, and track popularity using SQL.
# SQL_Music_Store_Analysis

This project demonstrates **business and data analysis** using a PostgreSQL music store database.

## Project Overview
- Complete database schema with realistic sample data
- Tables: `album`, `artist`, `customer`, `track`, `invoice`, `invoice_line`, `playlist`, etc.
- Example SQL queries to extract business insights:
  - Top customers by purchase
  - Most popular tracks and genres
  - Revenue and invoice analysis
  - Customer behavior analytics

## Tech Stack
- PostgreSQL 17
- SQL queries for data analysis and reporting

## How to Use
1. Restore the database:
```bash
pg_restore -U postgres -d music_database music_store_database.sql
