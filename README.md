# Bookchef : Get your books OnBoard
Welcome to BookChef, your all-in-one website for books is designed to provide users with a platform to browse, search for, and purchase books online. It includes features such as user authentication, a catalog of books, a shopping cart, and secure payment processing.

## The Dashboard
![Sample Image](/public/images/mainpage.png)
![Sample Image](/public/images/bookdescription.png)
![Sample Image](/public/images/cart.png)

#### Live Website
[Click Here](https://bookchef.vercel.app/) 

## Features
- User authentication and authorization
- Browse and search for books
- Add books to the shopping cart
- Secure payment processing
- User profiles with order history
- Admin panel for managing books and orders

## Technologies Used
- *Next.js*: The web framework used for building the frontend of the application.
- *Prisma*: The database toolkit used for interacting with the SQL database.
- *SQL*: The relational database used to store information about books, users, and orders.
- *TypeScript*: The statically-typed superset of JavaScript used for writing the application code.
- *Tailwind CSS*: The utility-first CSS framework used for styling the frontend.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the project dependencies using `npm install` or `yarn install`.
3. Set up the database. See the [Database](#database) section for instructions.
4. Set up your environment variables. See the [Environment Variables](#environment-variables) section for details.
5. Run the application locally using `npm run dev` or `yarn dev`.

## Project Structure
The project structure is organized as follows:

- `pages/`: Contains Next.js pages and routing.
- `components/`: Contains reusable React components.
- `prisma/`: Contains Prisma schema and migrations.
- `styles/`: Contains Tailwind CSS configuration and styles.
- `public/`: Contains static assets.

Add more details about the project structure here if necessary.

## Database
This project uses a SQL database with Prisma. You can set up your database by following these steps:
1. Install a SQL database (e.g., PostgreSQL, MySQL).
2. Create a new database for the project.
3. Update the `DATABASE_URL` environment variable in the `.env.local` file with your database connection URL.
4. Run database migrations using `npx prisma migrate dev`.
   
## Environment Variables
The following environment variables should be defined in a `.env.local` file at the project root:

DATABASE_URL=your-database-connection-url
JWT_SECRET=your-secret-key
STRIPE_SECRET_KEY=your-stripe-secret-key

Make sure to replace the placeholder values with your actual configuration.

## Running the Application

To run the application locally, use the following command:
bash
npm run dev

This will start the development server, and you can access the application in your web browser at `http://localhost:3000`.

## Deployment
This project can be deployed to various hosting platforms such as Vercel, Netlify, or your own server. Refer to the deployment documentation of your chosen hosting service for specific instructions.

## Contact
Have questions or feedback? Feel free to reach out to me at sankalpforwork@gmail.com.
