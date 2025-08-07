# Docker Assignment 01
Shivansh 8983634

## Overview
This project demonstrates a multi-service Docker Compose setup including MySQL with PHPMyAdmin, PostgreSQL with pgAdmin4, and a ReactJS frontend with a NodeJS backend.

## How to run

1. Clone this repo  
2. Run `docker-compose up -d --build`  
3. Access services on following ports:  
   - ReactJS: http://localhost:3000  
   - NodeJS API: http://localhost:5000  
   - MySQL: port 3306  
   - PHPMyAdmin: http://localhost:8081  
   - PostgreSQL: port 5432  
   - pgAdmin4: http://localhost:8080  

## Notes
- Persistent volumes are configured for MySQL and PostgreSQL data  
- Environment variables are used for database credentials
