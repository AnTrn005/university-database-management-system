
# University Database Management System

A full-stack web application designed to manage university data and support database operations, including tuition payment processing and transaction management.

Developed as a group project for **COSC 3380 – Database Systems** at the University of Houston.

## Overview

The University Database Management System integrates a relational database with a web-based interface to support university administrative operations. The project demonstrates database design, SQL query execution, frontend and backend integration, and transaction management.

A key focus of the project is maintaining data integrity during tuition payment transactions through input validation and safeguards against inconsistent account balances.

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Tailwind CSS
- **Backend:** Node.js
- **Database:** SQL
- **Tools:** npm, PostCSS, Git, GitHub

## Key Features

### Database Management
- Relational database schema for university information
- SQL queries for retrieving and managing data
- Database initialization and sample data population

### Tuition Payment Processing
- Tuition payment transaction handling
- Input validation to prevent invalid transactions
- Safeguards against inconsistent account balances
- Emphasis on database integrity and reliable updates

### Full-Stack Integration
- Web-based interface for interacting with university data
- Backend integration with database operations
- Responsive interface styling using Tailwind CSS

## Project Structure

```text
university_database_management_system/
├── src/
│   └── input.css             # Tailwind CSS source
├── index.html                # Main application interface
├── script.js                 # Client-side JavaScript
├── server.js                 # Backend application
├── university7_schema.sql    # Database schema
├── seed.sql                  # Sample database data
├── queries.sql               # SQL queries
├── transaction.sql           # Database transactions
├── package.json              # Project dependencies and scripts
├── package-lock.json         # Dependency lockfile
├── tailwind.config.js        # Tailwind CSS configuration
├── postcss.config.js         # PostCSS configuration
└── README.md                 # Project documentation
```

## Getting Started

### Prerequisites

- Node.js
- npm
- A compatible SQL database environment

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/AnTrn005/university-database-management-system.git
```

**2. Navigate to the project directory**

```bash
cd university-database-management-system
```

**3. Install dependencies**

```bash
npm install
```

**4. Set up the database**

Use the provided SQL files to initialize the database:

- `university7_schema.sql` – Creates the database schema
- `seed.sql` – Populates the database with sample data
- `queries.sql` – Contains database queries
- `transaction.sql` – Contains transaction-related SQL operations

Configure the database connection in accordance with your local environment.

**5. Run the application**

After configuring the database, start the backend using the command defined in `package.json`.

## My Contributions

As a member of the development team, my primary responsibilities included:

- **Frontend Development:** Developed and styled user interface components to improve usability and presentation.
- **Backend Development:** Implemented application functionality and integrated frontend interactions with backend operations.
- **Tuition Payment Transactions:** Developed transaction functionality with input validation and safeguards to prevent inconsistent account balances.
- **Full-Stack Integration:** Contributed to connecting the user interface, application logic, and relational database.

## Database Design

The project uses a relational database to organize university information and support data retrieval and updates.

The database implementation includes:

- SQL schema definitions
- Data initialization and population
- Queries for accessing and managing records
- Transaction handling to maintain data consistency

## Learning Outcomes

Through this project, I gained practical experience in:

- Designing and working with relational databases
- Writing SQL queries and implementing database transactions
- Integrating frontend and backend components
- Handling input validation and maintaining data integrity
- Collaborating on a full-stack software development project

## Project Information

**Course:** COSC 3380 – Database Systems  
**Institution:** University of Houston  
**Project Type:** Group Project  
**Focus:** Full-Stack Development, Relational Databases, SQL Transactions
