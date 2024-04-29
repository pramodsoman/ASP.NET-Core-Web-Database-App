
# ASP.NET Core Web Database App (Jokes Web App)

## Overview:
This project is a demonstration of creating a web database application using ASP.NET Core, Visual Studio, and C#. It showcases the implementation of the MVC (Model View Controller) design pattern, configuration of database tables using Entity Framework, customization of Razor forms, creation of controller methods, styling pages with CSS and Bootstrap, and integration of a search function to filter database results.

## Features:

- **Joke Management:** Users can create, view, edit, and delete jokes.
- **Search:** Users can search for jokes based on keywords in the joke question.
- **Authentication:** Users must be logged in to create, edit, or delete jokes.
- **Authorization:** Only authenticated users can perform certain actions.
- **Responsive Design:** The application is styled using CSS to provide a responsive user interface.
  
## Project Structure:
1. **Environment Setup:**
   - Installed Visual Studio and ASP.NET Core SDK.
   - Created a new ASP.NET Core project.
   - Configured the project to utilize MVC architecture.

2. **Data Model Creation:**
   - Defined the necessary model classes for the application.
   - Configured Entity Framework to interact with the database.
   - Generated database migrations to create tables.

3. **View Implementation:**
   - Customized Razor forms for data input, display, and editing.
   - Styled the views using CSS for improved presentation.

4. **Controller Development:**
   - Implemented controller classes to handle user requests.
   - Developed CRUD operations for managing database records.
   - Incorporated search functionality within the controller.

5. **User Interface Enhancement:**
   - Utilized Bootstrap classes to enhance the UI for better user experience.

## Getting Started:
To run this project on your local machine, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/pramodsoman/ASP.NET-Core-Web-Database-App
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd ASP.NET-Core-Web-Database-App
   ```

3. **Install Required Software:**
   - Ensure that Visual Studio is installed on your machine.

4. **Open the Project:**
   - Launch Visual Studio.
   - Go to `File` > `Open` > `Project/Solution`.
   - Browse to the directory where you cloned the repository, select the ASP.NET-Core-Web-Database-App.sln file, and click `Open`.

5. **Restore Dependencies:**
   - Right-click on the solution in the Solution Explorer.
   - Choose `Restore NuGet Packages` to install the necessary dependencies.

6. **Configure the Database Connection:**
   - Open the `appsettings.json` file in the project.
   - Locate the database connection string and ensure it matches your local database setup.
   - Update the connection string if necessary.

7. **Run the Application:**
   - Press `F5` or click the `Start` button in Visual Studio to compile and launch the application.
   - The application will open in your default web browser.

8. **Explore and Customize:**
   - Explore the application's features and functionalities.
   - Modify the code, add new features, or customize it according to your requirements.

## Technologies Used:
- **ASP.NET Core:** Framework used for developing web applications.
- **C#:** Programming language employed for backend logic.
- **Entity Framework Core:** ORM framework for database interaction.
- **Visual Studio:** Integrated development environment for .NET projects.
- **CSS:** Styling language for web pages.
- **Bootstrap:** Front-end framework for responsive and visually appealing designs.

## Conclusion:
This project demonstrates the creation of a web database application using ASP.NET Core and C#. By following industry best practices and utilizing popular frameworks like Entity Framework and Bootstrap, the application achieves efficient data management and a modern user interface. The MVC architecture ensures separation of concerns, making the application scalable and maintainable. Overall, this project serves as a practical example of building robust web applications with ASP.NET Core.

---

## Contributing:
If you would like to contribute to the project, please fork the repository and submit a pull request with your changes.

## License:
This project is licensed under the MIT License.

---
