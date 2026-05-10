# Internee.pk Scalable Database System

## Objective
Implement a scalable database to manage intern 
applications and records on AWS RDS.

## Tech Stack
| Technology | Purpose |
|---|---|
| AWS RDS MySQL | Cloud Database |
| MySQL Workbench | Database Management |
| Local MySQL (WAMP) | Source Database |

## Database Schema
- **interns** — Student profiles
- **applications** — Internship applications  
- **internships** — Available positions

## Migration Steps
1. Created local MySQL database with dummy data
2. Exported data from local MySQL (WAMP)
3. Connected MySQL Workbench to AWS RDS
4. Migrated all tables and records to AWS RDS
5. Enabled Read Replica for performance

## Read Replica
- Primary: internee-db (eu-north-1b)
- Replica: internee-db-replica (eu-north-1c)


## 📸 Screenshots


### 1. RDS Dashboard — Primary + Replica both Available

<img width="1903" height="823" alt="RDS Dashboard " src="https://github.com/user-attachments/assets/cb4a5a2c-4d99-4026-8486-08ada8789a9e" />


### 2. MySQL Workbench - Connected to RDS

<img width="1096" height="745" alt="Mysql-connection" src="https://github.com/user-attachments/assets/034f2605-5576-4a3a-81de-2d1cea5737a5" />

### 3. MySQL Workbench — Tables created + data inserted

<img width="1920" height="1042" alt="dateCreated" src="https://github.com/user-attachments/assets/a7c0d093-0d5f-406f-aaa7-cb30d9723517" />


### 4. Local MySQL — Original data

<img width="1920" height="1022" alt="Local MySQL — Original data " src="https://github.com/user-attachments/assets/e1236ff8-d978-45d7-9307-c5dfdb0ff25e" />






