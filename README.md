
# ContactKeeper

ContactKeeper is a web-based contact management system that enables users to maintain a list of personal or business contacts. After logging in with their email and password, users can create, view, update, and delete contacts.

## Features

- User Authentication (Login using Email and Password)
- Add new contacts with details such as name, email, phone number, etc.
- Update existing contact information
- Delete contacts from the list
- View all contacts with a clean user interface

## Technologies Used

- **Backend**: Java, Spring Boot
- **Frontend**: Thymeleaf, HTML, CSS
- **Database**: MySQL
- **Build Tool**: Maven

## Prerequisites

- Java 11 or higher
- Maven 3.6 or higher
- MySQL installed locally or on a server

## Installation and Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/ContactKeeper.git
   cd ContactKeeper
   ```

2. **Install dependencies**

   Maven is used to manage dependencies. Install them using the following command:

   ```bash
   mvn clean install
   ```

3. **Configure Database**

   You need to set up a MySQL database and configure the `application.properties` file with your database credentials:

   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/your-database-name
   spring.datasource.username=your-username
   spring.datasource.password=your-password
   spring.jpa.hibernate.ddl-auto=update
   ```

4. **Run the application**

   Once the dependencies are installed and the database is set up, you can run the application using:

   ```bash
   mvn spring-boot:run
   ```

5. **Access the application**

   Open your web browser and navigate to `http://localhost:8080`.

## Usage

- **Login**: Enter your email and password on the login page.
- **Manage Contacts**:
  - Add a new contact using the "Add Contact" button.
  - View your list of contacts on the dashboard.
  - Edit or delete contacts from the list as needed.

## Project Structure

- `src/main/java/com/yourpackage/ContactKeeper`: Contains the Java classes for the application.
- `src/main/resources/templates`: Contains the Thymeleaf HTML templates for the frontend.
- `src/main/resources/application.properties`: Configuration file for database and other settings.
- `pom.xml`: Maven configuration and dependency management file.

## Dependencies

The following dependencies are required and can be found in the `pom.xml` file:

- Spring Boot Starter Web
- Spring Boot Starter Data JPA
- Spring Boot Starter Thymeleaf
- MySQL Connector Java
- Spring Boot DevTools (Optional for development)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to open issues or submit pull requests. Contributions are always welcome!

