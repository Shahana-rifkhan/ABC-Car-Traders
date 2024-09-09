# ABC-Car-Traders
ABC Car Traders is committed to maintaining a long-lasting goodwill and trust with their customers as a supplier of high-quality vehicles and transport solutions provider. The company’s service centers are designed to deliver excellent services, helping customers achieve their vehicle dreams. Their experienced team assists customers in selecting the right products and services from a diverse range of vehicles, spare parts, and services.

## Project Overview

This project aims to develop a C# software application to support ABC Car Traders' mission of becoming the **Number One Preferred Supplier** of high-quality motor vehicles and related services. The software will streamline operations for both the **Admin** and **Customer** roles, enhancing customer satisfaction, service quality, and business growth.

### Key Mission

- To provide **Profitable Growth** through **Superior Customer Service**.
- To ensure **Innovation, Quality, and Commitment** in vehicle sales and services.

## Features

### Admin Features

- **Login**: Admin authentication and access control.
- **Manage Car Details**: Add, update, and delete car information.
- **Manage Car Parts Details**: Manage inventory of car parts.
- **Manage Customer Details**: View and manage customer information.
- **Manage Customer Order Details**: Track and manage orders from customers.
- **Generate Reports**: Create sales, inventory, and performance reports.

### Customer Features

- **Register**: New customers can register for an account.
- **Login**: Existing customers can log in to access their account.
- **Search Car Details**: View available cars in the inventory.
- **Search Car Parts Details**: Browse the available car parts.
- **Order Car/Car Parts**: Place orders for cars and car parts.
- **View Order Status**: Track the progress of placed orders.

## Technologies Used

- **Programming Language**: C#
- **Database**: (Add the specific database details here, e.g., SQL Server, MySQL)
- **Framework**: (Add any relevant C# frameworks used, e.g., ASP.NET)
- **IDE**: Visual Studio

## Installation Instructions

1. **Clone the Repository**:
  - First, clone the project repository to your local machine:

    ```bash
    git clone git@github.com:YourUsername/ABC-Car-Traders.git

2. **Open the Solution in Visual Studio**:
  - Open Visual Studio.
  - Go to `File -> Open -> Project/Solution`.
  - Navigate to the cloned repository folder and select       `ABC_Car_Traders.sln`.

3. **Restore NuGet Packages**
Once the solution is open, restore the NuGet packages:

  - Right-click on the solution in the Solution Explorer.
  - Select `Restore NuGet Packages`.

4. **Configure the Database**:

  - Use the Included Database Files: The project includes a local database (leave.mdf and leave_log.ldf):
  - Attach these files to your SQL Server instance using SQL Server Management Studio (SSMS).
  - Update the connection string in the `App.config` file to point to your local SQL Server instance.

5. **Build the Solution**:

  - In Visual Studio, go to `Build -> Build Solution` or press `Ctrl + Shift + B`.

6. **Run the Application**:

  - Set the desired project (Employee or Admin) as the startup project:
    - Right-click the project in the `Solution Explorer`.
    - Select `Set as Startup Project`.
  - Press `F5` to start debugging and run the application.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
```bash
This README provides a comprehensive guide to installing and running your ABC Car Traders. You can adapt it to your specific project needs.


