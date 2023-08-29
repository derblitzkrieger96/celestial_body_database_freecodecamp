# Celestial Bodies Database Project

This project is a part of my learning journey in the field of database management using PostgreSQL. The goal of this project was to create a database that models various celestial bodies such as galaxies, stars, planets, moons, and clusters. Below, I'll provide an overview of the tasks I completed and the structure of the database.

## Project Overview

- **Database Name:** universe
- **Tables Created:** galaxy, star, planet, moon, cluster
- **Total Tables:** 5
- **Total Rows:** galaxy:6, star:6, planet:12, moon:20, cluster:3
- **Total Columns:** galaxy:5, star:5, planet:5, moon:5, cluster:3

## Tasks Completed

1. **Database Creation:** I created a PostgreSQL database named "universe" to store information about celestial bodies.

2. **Table Creation:** I added five tables: galaxy, star, planet, moon and cluster.

3. **Primary Keys:** Each table has a primary key, and the primary key columns follow the naming convention of `table_name_id`.

4. **Automatic Increment:** The primary key columns are set to automatically increment.

5. **Column Types:** I used a variety of data types such as `INT`, `NUMERIC`, `TEXT`, `SERIAL`, `VARCHAR` and `BOOLEAN` to capture different aspects of celestial bodies.

6. **Foreign Keys:** I established relationships between tables using foreign keys. Each "star" is associated with a "galaxy," and galaxies are associated with a "cluster", each "planet" is associated with a "star," and each "moon" is associated with a "planet."

7. **Data Integrity:** I ensured data integrity by using foreign keys to link rows between tables.

8. **Additional Columns:** In addition to required columns, I added columns like `description`, `has_life`, `is_spherical`, and more to provide detailed information about celestial bodies.

9. **Data Insertion:** I inserted data into the database, creating a diverse collection of celestial bodies, stars, planets, and moons.

## Screenshots

### Galaxy Table
![galaxy_table](https://github.com/derblitzkrieger96/celestial_body_database_freecodecamp/assets/100312715/c5c7cc23-83e7-4582-a854-d4f8303b89a2)


### Star Table
![star_table](https://github.com/derblitzkrieger96/celestial_body_database_freecodecamp/assets/100312715/53ac42d5-826d-452c-8382-e92cc3e8664a)


### Planet Table
![planet_table](https://github.com/derblitzkrieger96/celestial_body_database_freecodecamp/assets/100312715/f5219b57-d091-4b45-b737-3064f62b7290)


### Moon Table
![moon_table](https://github.com/derblitzkrieger96/celestial_body_database_freecodecamp/assets/100312715/c7531724-d264-4390-bbbb-a323c33d2e5c)


### Cluster Table
![cluster_table](https://github.com/derblitzkrieger96/celestial_body_database_freecodecamp/assets/100312715/66c07752-4950-444b-8f2b-f004ec6bea21)



## How to Use

1. Clone this repository to your local machine.
2. Use PostgreSQL's `psql` to execute the SQL script containing the database schema and data (`universe.sql`).
3. Explore the database using SQL queries to retrieve information about different celestial bodies.

## Future Enhancements

- Add more columns to capture additional attributes of celestial bodies.
- Implement advanced queries to extract valuable insights from the data.
- Explore data visualization options to represent the relationships and characteristics of celestial bodies.

## Contact Information

If you have any questions or feedback about this project, feel free to contact me at [ddanilodorado@gmail.com](mailto:ddanilodorado@gmail.com). I'm open to collaboration and would love to hear your thoughts!

## Acknowledgments

I'd like to express my gratitude to [FreeCodeCamp](https://www.freecodecamp.org/) for providing the project guidelines and helping me enhance my database skills.

---

Thank you for taking the time to explore my Celestial Bodies Database project! Your feedback and suggestions are highly appreciated.
