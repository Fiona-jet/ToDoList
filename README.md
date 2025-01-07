# To-Do List Application (Group Project)
 ## Project Overview
 The To-Do List application is a SwiftUI-based project developed using Xcode. It is designed to help users organize and manage their daily tasks efficiently. This application includes features such as user registration, task creation, and Firebase integration for data persistence.--
## My Contributions
 Below is a detailed description of the features I developed and implemented in this project:
 ### 1. **App Icon Design**- Designed and integrated custom app icons to provide a unique and visually appealing identity to the application.- Created support for both light and dark modes, ensuring a consistent user experience.- Ensured compatibility for various device sizes.
 ### 2. **Register View**- Implemented the user registration screen (`RegisterView`) using SwiftUI.- Added features such as:
  - **Header Design:** Displaying title and subtitle with a dynamic background.
  - **Input Fields:** Text fields for name, email, and password with proper bindings and validation.
  - **CTA Button:** A "Create Account" button styled with SwiftUI, linked to the user registration functionality.
  - **Dark Mode Support:** Ensured visual compatibility for both light and dark appearances.
  - Utilized a `RegisterViewModel` to manage state and handle registration logic effectively.
 ### 3. **Login View**- Developed a login screen (`LoginView`) that allows users to access their accounts.
- Features include:
  - **Header Design:** Title and subtitle with a dynamic background in red.
  - **Input Fields:** Text fields for email and password, integrated with `LoginViewModel`.
  - **Error Display:** Real-time error messages for invalid login attempts.
  - **Navigation:** Linked to the registration view for new users.
 ### 4. **Firebase Authentication**- Integrated Firebase Authentication for user management.- Enabled email-based sign-up and login functionality.- Verified data by monitoring user authentication and registration in Firebase Console.
 ### 5. **Firestore Database Integration**- Configured Firestore to store user data (e.g., name, email, registration date).- Structured the database to allow easy retrieval and storage of task-related data.
 ### 6. **Daily Tasks View**- Implemented a view to display a list of daily tasks (`DailyTasksView`).- Features include:
  - Dynamic task display using a `ForEach` loop.
  - Integration with Firestore for loading and displaying tasks.
  - Button to parse task details and handle actions such as editing or marking tasks as completed.
 ### 7. **Task Creation and Validation**- Designed a "New Item" screen where users can create tasks with details such as title, due date, and time.- Added input validation to ensure all fields are filled, and the due date is valid (not in the past).- Implemented user-friendly error messages for invalid inputs.
### 8. **Launch Screen**- Created a launch screen with the app title "Tick Task," ensuring a professional first impression.- Optimized design to work seamlessly across various screen sizes.
 ### 9. **Sample Data and JSON Handling**- Prepared a JSON file containing sample tasks for testing and demonstration purposes.- Example tasks include daily activities such as "Morning Exercise" and "Review Goals," complete with IDs and timestamps.
 ### Screenshots
 Below are some highlights of the features I implemented:
 1. App Icon Design
 2. Registration Screen (Light and Dark Modes)
 3. Login Screen with Error Display
 4. Firebase Authentication and Firestore Integration
 5. Navigation and Welcome Screen
 6. Task Creation with Validation
 7. Daily Tasks View
 8. Launch Screen--
## Technologies Used- **Language:** Swift (SwiftUI framework)- **Development Environment:** Xcode- **Database:** Firebase Firestore- **Authentication:** Firebase Authentication
--
## Acknowledgments
 I would like to thank my team members for their collaboration and support throughout the development of this project. This experience has been a valuable opportunity to enhance my skills in iOS development.--
## Contact
 For any questions or further information about my contributions, feel free to contact me
