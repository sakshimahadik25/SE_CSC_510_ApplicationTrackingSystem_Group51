# Lessons Learned from Project 1: Application Tracking System

In our journey through Project 1, the "Application Tracking System," for the Software Engineering course, we encountered numerous challenges and roadblocks that made the development process more arduous than it needed to be. This markdown document delves into the difficulties we faced, examines how these challenges could have been circumvented, and outlines the best practices we intend to adopt in Project 2 to ensure a smoother and more successful development experience.

## Identifying Pain Points

1. **Inadequate Documentation**: One of the most significant hurdles we faced was the lack of comprehensive documentation, especially for the backend. It made understanding the existing codebase and making changes a frustrating experience. No clear documentation was provided for using the MongoDB database and clear steps weren’t provided to connect to the MongoDB instance. Since web scraping was a crucial part of our application, the lack of documentation in this area was a major setback. It made it difficult to troubleshoot issues and modify the scraping process.

2. **Lack of Code Comments**: The absence of comments in the code added another layer of complexity. Without proper explanations, it was challenging to decipher the purpose and functionality of various components.

3. **Poor Modular Structure**: The backend code lacked a modular structure, which resulted in a tangled mess of interdependent components. This made it hard to isolate and fix issues without affecting other parts of the system.

4. **Configuration and Database Separation**: The absence of a separate configuration file and database instance made it less maintainable and secure. Changes in configurations had to be hardcoded, leading to potential errors.

5. **UI Design and Usability**: The user interface had room for improvement. It lacked a proper profile page to display education and work experience, and the Google OAuth integration was missing, limiting authentication options.

6. **Functionality Issues**: We encountered issues where the date field on the search page also didn't match the information displayed, leading to confusion.

7. **Delete Functionality**: The functionality for deleting applications on the search page was confusing and needed refinement.

## Avoiding the Pain

### Documentation and Comments
To avoid the issues related to documentation and code comments, we commit to the following practices in Project 2:

- **Comprehensive Documentation**: We will ensure that both frontend and backend code have thorough documentation. This includes high-level overviews, API documentation, and inline comments for complex logic.

- **Code Comments**: We will adopt a culture of commenting code as we write it, explaining the purpose of functions, variables, and any non-trivial logic.

### Modular Code

- **Implement a Modular Structure**: We will structure our code into clear and distinct modules, each responsible for specific functionalities. This will enhance code readability and maintainability.

- **Follow Best Practices**: We will adhere to software engineering best practices, including the SOLID principles, to ensure a well-structured and maintainable codebase.

### Configuration and Database Separation
To separate configuration and database concerns:

- **Use Configuration Files**: We will create separate configuration files, allowing us to easily adjust settings without altering the code.

- **Utilize Database Instances**: We will employ database instances and connection pools to establish a robust and secure connection with the database.

### UI Improvement

- **Implement a Proper Profile Page**: We will create a dedicated profile page that displays user education and work experience, providing a more comprehensive user experience.

- **Integrate OAuth**: We will integrate Google OAuth or other authentication methods to enhance security and user convenience.

### Functionality Enhancement

- **Thorough Testing**: We will conduct rigorous testing, including unit tests and end-to-end tests, to identify and rectify any functionality issues before they reach production.

- **Regular Code Reviews**: We will conduct regular code reviews to identify and address issues in the codebase.

### Improved UI Behavior

- **UI/UX Design Guidelines**: We will adhere to UI/UX design guidelines to ensure a seamless and intuitive user experience. The “Added" button should be disabled once the user has added the application so it does not change to "Add" when clicked.

### Clarify Delete Functionality

- **User-Friendly Design**: We will redesign the delete functionality on the search page to make it more intuitive and user-friendly, reducing confusion.

## Conclusion

Project 1's Application Tracking System provided us with valuable insights into the challenges of software development when dealing with an incomplete and undocumented codebase. By recognizing these pain points and committing to best practices in Project 2, we aim to create a more efficient, maintainable, and user-friendly application while avoiding the pitfalls that hindered our progress in our first project. 
