# HomeSphere Real Estate Management System (HS-REM)

## Introduction
Welcome to HomeSphere, a comprehensive Real Estate Management System designed to streamline property management processes. Created for real estate offices, agents, buyers, and administrators, HomeSphere enhances the efficiency of managing property listings and facilitates smooth interaction among various stakeholders in the real estate market.

## Features

### Property Search and Filtering
- Advanced search functionality based on location, property type, and price range.
- User-friendly browsing of search results with detailed property descriptions.

### User Account Management
- Secure login system with roles for buyers, agents, and administrators.
- Role-based access control to ensure users have access to relevant information and actions.

### Property and Agent Information
- Detailed property listings including images, dimensions, types, and status.
- Easy access to agent contact information for seamless communication.

### Transaction Management
- Comprehensive record-keeping of property transactions for agents and buyers.
- Status updates and history tracking for all property listings.

## Technical Details

- **Programming Language**: Java
- **Database**: MySQL
- **Database Connector**: MySQL Connector/J
- **User Interface**: Swing

## Project Structure

### Java Source Files
- `mypro.java`: Main entry point of the application.
- `Login`: Classes for managing login operations for different user roles.
- `Success`: Classes handling post-login operations for various users.
- `Filter & Query`: Modules for property search and query formulation.
- `Agent Management`: Administrative tools for managing agents.
- `Property & Transaction`: Interfaces and logic for managing property listings and transactions.

### Configuration Files
- `settings.json`: Configuration file for database connections and application settings.

### SQL Scripts
- `Database Schema`: Scripts for creating the required database schema.
- `Data Population`: Scripts for populating the database with sample data.
- `Relationship Management`: Scripts for defining relationships between data entities.

## Getting Started

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- MySQL Database Server
- MySQL Connector/J library

### Installation
1. Clone the project repository to your local machine.
2. Set up a MySQL database and import the schema using the provided SQL scripts.
3. Configure `settings.json` to point to your database and MySQL Connector/J library.
4. Compile the Java source files using `javac` or your preferred IDE.
5. Run `mypro.java` to start the application.

## Contributing
We welcome community contributions. To contribute to HomeSphere, please follow the standard fork-and-pull request workflow.

- Fork the repository.
- Create your feature branch (`git checkout -b feature/AmazingFeature`).
- Commit your changes (`git commit -m 'Add AmazingFeature'`).
- Push to the branch (`git push origin feature/AmazingFeature`).
- Open a pull request.

## Versioning
We use [Semantic Versioning](http://semver.org/) for versioning. For available versions, see the [tags on this repository](#).

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Authors
- **Akash Singh** - *Initial development* - [GitHub](https://github.com/akash22ak)

## Course Information
- **Course Name**: Database Management System (CS241) 
- **Instructor**: Dr. Sumit Mishra (Assistant Professor)

## Institution
- **Institution Name**: Indian Institute of Information Technology Guwahati
- **Year**: 2nd Year, 4th Semester
