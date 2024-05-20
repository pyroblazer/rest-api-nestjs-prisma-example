## REST-API-NestJS-Prisma-Example

Pyroblazer (Ignatius Timothy Manullang)

A simple backend REST API example built using NestJS, Prisma, PostgreSQL and Swagger. 

### Installation

1. Install dependencies: `pnpm install`
2. Start a MySQL database with docker using: `docker-compose up -d`. 
    - If you have a local instance of MySQL running, you can skip this step. In this case, you will need to change the `DATABASE_URL` inside the `.env` file with a valid [MySQL connection string](https://www.prisma.io/docs/concepts/database-connectors/mysql#connection-details) for your database. 
3. Apply database migrations: `pnpx prisma migrate dev` 
4. Start the project:  `pnpm run start:dev`
5. Access the project at http://localhost:3000/api