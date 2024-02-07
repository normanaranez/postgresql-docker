# Project Name

## Setup

Follow these steps to set up the project:

1. **Clone the repository**
git clone https://github.com/username/repository.git


Replace `username` and `repository` with the actual username and repository name.

2. **Navigate to the project directory**
cd repository


Replace `repository` with the actual repository name.

3. **Create a `.env` file**

Create a `.env` file in the root of the project directory and add the following lines:

POSTGRES_USER=your_username 
POSTGRES_PASSWORD=your_password 
POSTGRES_DB=your_database


Replace `your_username`, `your_password`, and `your_database` with your actual PostgreSQL username, password, and database name.

4. **Run Docker Compose**
docker-compose up


This command will start the PostgreSQL and Adminer services.

## Accessing the Database

You can access the PostgreSQL database at `localhost:5432` using any PostgreSQL client with the username, password, and database name specified in the `.env` file.

You can access the Adminer database management tool at `localhost:8080`.