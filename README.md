# Optimizing Logistics Through Data

This project focuses on building a scalable, data-driven logistics management system to improve shipment tracking, customer service, and operational efficiency. It addresses the limitations of traditional Excel-based tracking by implementing a structured database solution with real-time capabilities.

## Problem Statement
As logistics operations grow, manual tools like Excel become insufficient for handling large volumes of data, leading to inefficiencies, delays, and poor customer experiences. Courier Nexus introduces an automated, secure, and scalable database to track shipments, manage claims, monitor customer feedback, and optimize delivery operations.

## Key Features
- Real-time shipment tracking and delivery updates.
- Detailed package management (dimensions, weight, rates).
- Customer feedback logging and analysis.
- Claims processing with traceability.
- Indexed database for faster queries and optimized performance.
- Web application for visualizing queries and logistics data.

## Target Users
1. **Logistics Operations Team:** Add and manage shipments, track packages, and update delivery statuses.
2. **Customer Service Representatives:** Access shipment details and resolve claims or delays.
3. **Warehouse and Delivery Teams:** Record delivery attempts and locations.
4. **Administrators & IT Teams:** Manage security, permissions, and backups.

## Database Design
- **Entities:** Packages, Shipments, Senders, Receivers, Service Areas, Claims, Customer Feedback, Delivery Attempts, Delivery Locations, Shipping Rates.
- **Normalization:** All tables are designed to comply with BCNF to reduce redundancy and maintain data integrity.
- **Indexing:** Optimized indexes on key columns (e.g., `shipment_id`, `tracking_number`, `receiver_id`) to speed up query execution.
- **Cascading and Constraints:** Enforced referential integrity using foreign keys, unique constraints, and default values.

## SQL Operations
The system supports:
- **Insertions:** Adding new packages, shipments, and senders.
- **Updates:** Modifying shipment statuses or pricing details.
- **Queries:** Aggregating shipment statuses, fetching recent claims, and analyzing feedback ratings.
- **Deletions:** Removing outdated or resolved claims.
- **Optimizations:** Indexed queries for faster join operations and filtering.

## Tech Stack
- **Languages:** Python, SQL
- **Libraries:** Faker (for mock data generation), SQLite/PostgreSQL
- **Web Application:** Flask for query visualization
- **Tools:** ER Diagrams, SQL query optimization with indexing

## Highlights
- Reduced query execution time by implementing targeted indexing.
- Designed a normalized, BCNF-compliant database to handle large datasets.
- Developed SQL queries with `GROUP BY`, `JOIN`, subqueries, and aggregate functions.
- Created a web interface for visualizing database queries and operations.

