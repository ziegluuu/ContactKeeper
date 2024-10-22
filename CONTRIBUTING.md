
# Contributing to ContactKeeper

Thank you for your interest in contributing to **ContactKeeper**! We appreciate your time and effort in helping us improve this user-friendly contact management system. Whether you're reporting bugs, suggesting new features, or submitting code changes, your contribution is valuable to us.

Please follow the guidelines below to make the process as smooth as possible.

## Table of Contents

- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Feature Requests](#feature-requests)
  - [Pull Requests](#pull-requests)
- [Code of Conduct](#code-of-conduct)
- [Code Guidelines](#code-guidelines)
- [Development Setup](#development-setup)

---

## Getting Started

1. **Fork the repository**:  
   Start by forking the repository on GitHub. This will create a copy of the project under your GitHub account.

2. **Clone your fork**:  
   Clone the repository to your local machine.

   ```bash
   git clone https://github.com/ziegluuu/ContactKeeper.git
   cd ContactKeeper
   ```

3. **Set up the project**:  
   Follow the installation and setup instructions outlined in the `README.md` to get the project running on your machine.

4. **Create a new branch**:  
   Always work on a new feature or bugfix branch.

   ```bash
   git checkout -b feature/your-feature-name
   ```

## How to Contribute

### Reporting Bugs

If you encounter any bugs, feel free to [open an issue](https://github.com/ziegluuu/ContactKeeper/issues) with the following details:

- **Title**: Short description of the issue
- **Description**: Include steps to reproduce the bug, what you expected to happen, and what actually happened
- **Environment**: Provide any relevant information like operating system, browser, or Java version
- **Screenshots**: Add screenshots if applicable

### Feature Requests

We welcome feature suggestions! If you have an idea to improve **ContactKeeper**, please [open a new issue](https://github.com/ziegluuu/ContactKeeper/issues) labeled as a "Feature Request" with the following:

- **Description**: A detailed explanation of the feature
- **Use Case**: How this feature will be helpful to users
- **Mockups/Examples**: Any designs, images, or examples that clarify the suggestion

### Pull Requests

We encourage you to submit pull requests for both new features and bug fixes. Here's how:

1. **Ensure the project builds**: Make sure the project builds without errors before submitting your changes.

2. **Write clear commit messages**: Follow [Conventional Commits](https://www.conventionalcommits.org/) guidelines for writing descriptive commit messages.

   Example: 
   ```
   feat: add contact search functionality
   fix: resolve null pointer exception in contact deletion
   ```

3. **Submit the pull request**: When your feature or bug fix is ready, push the branch to your fork and submit a pull request to the `main` branch of the original repository. Include a detailed description of the changes.

4. **Link to issues**: If your pull request addresses an issue, include the issue number in your pull request description (e.g., `Fixes #12`).

### Pull Request Checklist

Before submitting your pull request, please make sure:

- The code follows the existing coding style and standards.
- All tests pass successfully.
- The pull request includes tests for any new features or changes (if applicable).
- The pull request is well-documented, explaining the purpose and impact of the changes.

## Code of Conduct

By participating in this project, you agree to abide by the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/). We expect all contributors to behave respectfully and to collaborate constructively.

## Code Guidelines

### Coding Style

- **Java**: Follow Java best practices and the [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html).
- **HTML/CSS**: Keep the structure clean, readable, and ensure cross-browser compatibility.
- **Thymeleaf**: Maintain consistent template structure with meaningful naming.

### Commit Messages

- Use descriptive commit messages to explain why a change is being made.
- Use the imperative mood (e.g., "Add feature" instead of "Added feature").

### Testing

- Ensure that your changes are covered by unit or integration tests.
- Make sure tests run successfully by using:

  ```bash
  mvn test
  ```

## Development Setup

To start developing for **ContactKeeper**, follow these steps:

1. **Install Dependencies**:  
   Install all required dependencies by running:

   ```bash
   mvn clean install
   ```

2. **Database Configuration**:  
   Configure your MySQL database by editing the `application.properties` file with your own database credentials.

3. **Run the Application**:  
   Start the application using the following command:

   ```bash
   mvn spring-boot:run
   ```

4. **Running Tests**:  
   To ensure that all tests are passing, run:

   ```bash
   mvn test
   ```

---

We look forward to your contributions! Thank you for helping make **ContactKeeper** better. If you have any questions, feel free to open an issue or reach out to the maintainers.

Happy coding! 🎉
