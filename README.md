# Dockerized MySQL with Adminer

This project demonstrates how to set up a MySQL database and Adminer UI using Docker Compose.

## Services Included
- **MySQL 5.7**: A relational database system.
- **Adminer**: A simple web interface to interact with the MySQL database.

## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/dockerized_mysql_adminer.git
    ```

2. Run the services with Docker Compose:
    ```bash
    docker-compose up -d
    ```

3. Access Adminer at [http://localhost:8080](http://localhost:8080) and log in with the following credentials:
    - **System**: MySQL
    - **Server**: mysql
    - **Username**: root
    - **Password**: rootpassword
    - **Database**: mydb
