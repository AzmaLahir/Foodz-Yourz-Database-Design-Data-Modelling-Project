# Foodz@Yourz Database Design & Data Modelling

## Overview
This repository contains the conceptual Extended Entity-Relationship Diagram (EERD) and logical database mapping for **Foodz@Yourz**, an online grocery delivery platform. The architecture models customer basket management, store inventory, driver/vehicle dispatches, order fulfillment, and payment methods[cite: 2].

## Key Features & Highlights
- Supertype & Subtype Specialization:
  - `Employee` specialized into `Driver` and `Warehouse Worker`[cite: 2].
  - `Vehicle` categorized into `Two_W` and `Four_W` with operational capacity constraints[cite: 2].
  - `Product` specialized into `Perishable` (Food/Drink) and `Non-Perishable` items[cite: 2].
  - `Payment` handling both `Card_Pay` and `Mobile_Pay`[cite: 2].
- Business Rule Enforcement: Multiplicity and cardinality rules for order collections, multi-store stock, and delivery locations[cite: 2].
- Logical Mapping: EERD transformed into a normalized UML Logical Entity Relationship Diagram with Primary and Foreign Keys defined[cite: 2].

## Conceptual EERD Diagram
![EERD Diagram](EERD_Diagram.jpg)

## Tools & Notations
- UML Notation for Conceptual and Logical Modeling[cite: 2].
- Data Modeling: Conceptual EERD, Business Decision Logging, Multiplicity Analysis, Attributes & PK/FK Mapping[cite: 2].

## Files Included
- `Foodz_Yourz_Database_Design_Report.pdf`: Complete technical documentation covering business logic and logical schema transformation[cite: 2].
- `EERD_Diagram.png`: High-resolution conceptual database architecture diagram[cite: 2].
- `schema.sql`: SQL DDL scripts for table creation and key constraints.
