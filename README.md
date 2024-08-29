# E-Commerce Application

## Introduction

This E-Commerce Application is a full-stack web project designed to simulate a fully functional online store. It features a comprehensive set of functionalities essential for managing products, handling user accounts, processing orders, and maintaining inventory. The project is built using modern web technologies, ensuring a robust, scalable, and user-friendly shopping experience.

## Technologies Used

### Backend
- **ASP.NET Core**: Utilized for building a RESTful API to handle business logic and data management.
- **Entity Framework Core**: Manages database interactions and migrations.
- **SQL Server**: Serves as the primary database to store user, product, and order data.
- **Authentication & Authorization**: JWT (JSON Web Tokens) is implemented to secure API endpoints.

### Frontend
- **Angular**: A powerful front-end framework that provides a dynamic and responsive user interface.
- **TypeScript**: Enhances the development experience with static typing.
- **Bootstrap**: Ensures a responsive and mobile-first UI design.
- **Reactive Forms & RxJS**: Utilized for managing form data and handling asynchronous operations.

### Other Tools
- **Swagger**: Integrated for API documentation and testing.
- **Azure/AWS**: Deployed on cloud infrastructure for scalability and availability.

## Key Features

- **User Management**: Secure registration and login with JWT-based authentication.
- **Product Management**: Admin can add, update, and delete products, while users can browse products with detailed information.
- **Shopping Cart**: Users can add items to their cart, modify quantities, and proceed to checkout.
- **Order Processing**: Complete order workflow, from placing an order to confirming and tracking it.
- **Payment Gateway Integration**: Simulated payment processing to complete the order cycle.
- **Search and Filter**: Advanced search and filtering options to enhance user experience.

## Installation Guide

### Prerequisites
- .NET SDK
- Node.js and Angular CLI
- SQL Server

### Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/soundaryalaharivalipe/E-Commerce-Application.git

2. **Backend Setup**:

   1. Navigate to the `Backend` folder.
   2. Run `dotnet restore` to install dependencies.
   3. Update `appsettings.json` with your SQL Server connection string.
   4. Run `dotnet ef database update` to apply migrations.
   5. Start the backend server with `dotnet run`.

3. **Frontend Setup**:

   1. Navigate to the `Frontend` folder.
   2. Run `npm install` to install Angular dependencies.
   3. Start the Angular application with `ng serve`.

4. **Database Setup**:

   1. Execute the SQL scripts in the `Database` folder to set up the database schema and seed data.

## Running the Application

- Access the frontend at `http://localhost:4200/`.
- The backend API can be accessed via `http://localhost:5000/api/`.

## Usage

- **Admin Panel**: Login as an admin to manage products, view orders, and manage users.
- **Customer Interface**: Browse products, manage your cart, and place orders.
- **Order Tracking**: After placing an order, view its status and history.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`feature/YourFeature`).
3. Commit your changes.
4. Push to the branch and create a pull request.
