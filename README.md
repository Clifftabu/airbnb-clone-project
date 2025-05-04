#Readme.md
# Airbnb Clone Project

# Project Overview

The Airbnb Clone Project is a real WORLD application designed to simulate the development of a robust booking platform.It focuses on creating a scalable backend system using modern technologies, enabling users to manage properties, make bookings, and process payments securely. 

# Project Goals
- Develop a fully functional backend for a booking platform similar to Airbnb.
- Ensure high scalability, maintainability, and security in the system.
- Implement and showcase industry best practices in backend development.

# Tech stack
- Django:Web framework used for backend development and API design.
- MySQL: A relational database for storing and managing data.
- GraphQL: Query language for APIs to enable efficient and flexible data 
  fetching.
- Docker: For containerization, ensuring consistent development and deployment environments.

# Team Roles
-Backend Developer:
  Responsible for designing, building, and maintaining the backend logic and APIs. Ensures robust application performance and data management.
- Database Administrator :
  Focuses on designing and managing the database structure, ensuring data integrity, and optimizing database performance.
- DevOps Engineer:
  Sets up and manages CI/CD pipelines, automates deployments, and ensures system scalability using tools like Docker.
- Project Manager:
  Oversees project timelines and ensures collaboration among team members and to achieve project goals effectively.

# Technology Stack
- Django:Web framework used for backend development and API design.
- MySQL: A relational database for storing and managing data.
- GraphQL: Query language for APIs to enable efficient and flexible data 
  fetching.
- Docker: For containerization, ensuring consistent development and deployment environments.

# Database Design
The key entities are:
1. Users:
   - id (Primary Key)
   - name
   - email
   - password (encrypted)
   - role (e.g., guest, host)
2. Properties:
   - id (Primary Key)
   - name
   - location
   - description
   - price_per_night
   - host_id (Foreign Key referencing Users)
3. Bookings:
   - id (Primary Key)
   - property_id (Foreign Key referencing Properties)
   - user_id (Foreign Key referencing Users)
   - start_date
   - end_date
   - total_price
4. Payments:
   - id (Primary Key)
   - booking_id (Foreign Key referencing Bookings)
   - amount
   - payment_date
   - payment_status
Beloq are the entities' relationships:
- A user can own multiple properties (one-to-many).
- A property can have multiple bookings (one-to-many).
- A user can book multiple properties (one-to-many).
- A booking is associated with one payment (one-to-one).

#








  

  



