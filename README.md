<h1>Coda API</h1>

# Specifications 📋
Small API project carried out in progress during my training at Coda for my 3rd year of license.
This API essentially allows to manage a blog thanks to its requests for registration, connection and all requests allowing to manage the posts (add/modify/delete/view) with a system of categories that can be applied to the posts (add/modify/delete).

## Software Used
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

## Languages Used
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

## How to deploy the API on your machine?

1. **Clone the repository:**
    ```bash
    git clone https://github.com/ArthurAugis/api-coda
    cd api-coda
    ```

2. **Install dependencies:**
    Make sure you have [Node.js](https://nodejs.org/) installed. Then run:
    ```bash
    npm install
    ```

3. **Set up the database:**
    Ensure you have MySQL installed and running. Create a new database:
    ```sql
    CREATE DATABASE your_database_name;
    ```

4. **Configure environment variables:**
    Create a `.env` file in the root directory and add your database connection details:
    ```env
    DATABASE_URL="mysql://user:password@localhost:3306/your_database_name"
    ```

5. **Run database migrations:**
    ```bash
    npm run db:dev:migrate
    ```

6. **Start the server:**
    ```bash
    npm run dev
    ```

7. **Access the API:**
    Open your browser and navigate to `http://localhost:3000`.

Your API should now be running on your local machine.
