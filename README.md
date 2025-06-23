# SQL-Internship-Task--1
E-Commerce Database Schema Design
Task Overview:
This project focuses on designing a basic relational database schema for an E-commerce system, implemented using LiveSQL.

Objective:
Understand how to create databases and tables.
Define relationships between entities using primary and foreign keys.
Practice writing SQL scripts for schema design.

Tools Used:
LiveSQL (https://livesql.oracle.com/) – for writing and testing SQL queries.

Schema Design Overview
Tables Created:
Customers – Stores customer details.
Categories – Lists product categories.
Products – Items for sale, linked to categories.
Orders – Represents orders placed by customers.
OrderItems – Items within each order.

Key Concepts Used:
CREATE TABLE statements
PRIMARY KEY constraints
FOREIGN KEY constraints for relationships
Entity Relationships
One customer → many orders
One order → many order items
One product → many order items
One category → many products

SQL Script:
All tables and relationships were created using CREATE TABLE statements. The full SQL script is available in the schema.sql file in this repo.

Outcome:
A well-structured database schema with properly defined relationships, tested successfully in LiveSQL.
