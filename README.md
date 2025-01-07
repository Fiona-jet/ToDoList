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
<img width="200" alt="Screenshot 2024-12-31 at 1 20 03ΓÇ»AM" src="https://github.com/user-attachments/assets/94dc27d7-fa89-4598-bff0-6cb7d66320d4" />
    <img width="800" alt="Screenshot 2024-12-31 at 1 21 29ΓÇ»AM" src="https://github.com/user-attachments/assets/90419650-03eb-4dd8-b091-95b335890ba5" />
    
 3. Registration Screen (Light and Dark Modes)
<img width="800" alt="Screenshot 2024-12-29 at 1 48 57ΓÇ»PM" src="https://github.com/user-attachments/assets/b186e224-6d35-47b1-ab8e-d16e1246a62f" />
<img width="800" alt="Screenshot 2024-12-29 at 1 52 12ΓÇ»PM" src="https://github.com/user-attachments/assets/96edc1e4-a11f-4fa4-87c7-0ca3c07d0de5" />
<img width="800" alt="Screenshot 2024-12-29 at 1 56 39ΓÇ»PM" src="https://github.com/user-attachments/assets/5d841feb-b4af-454b-b27f-1366631712d2" />
<img width="800" alt="Screenshot 2024-12-29 at 2 15 02ΓÇ»PM" src="https://github.com/user-attachments/assets/ada6aaa6-591f-41f6-a47a-85db6afd83d4" />

5. Firebase Authentication and Firestore Integration
<img width="1673" alt="Screenshot 2024-12-29 at 4 41 38ΓÇ»PM" src="https://github.com/user-attachments/assets/1ca3aa24-7d60-461b-9374-d66b02c9604b" />
<img width="1366" alt="Screenshot 2024-12-29 at 4 42 34ΓÇ»PM" src="https://github.com/user-attachments/assets/ae1f8423-59ea-45d5-9a77-1a31c95ed77c" />

 4. Login Screen with Error Display
![Screenshot 2025-01-02 091037](https://github.com/user-attachments/assets/4a11591b-f4e7-4a64-a109-e206cab83840)
![Screenshot 2025-01-02 091056](https://github.com/user-attachments/assets/cd35a944-b345-4bf1-8cdf-2227fd9ce6a7)

 6. Navigation and Welcome Screen    
<img width="450" alt="Screenshot 2024-12-29 at 4 52 57ΓÇ»PM" src="https://github.com/user-attachments/assets/e8827dfc-ed99-4433-be7e-76d71bdf407d" />

 7.   Daily Tasks & ViewTask Creation with Validation
 <img width="483" alt="Screenshot 2024-12-31 at 12 19 48ΓÇ»AM" src="https://github.com/user-attachments/assets/5c799247-ecaa-42f5-9fa7-cc6f0fd8f252" />

8.Sample Data and JSON Handling
![Screenshot 2025-01-01 111457](https://github.com/user-attachments/assets/406edbf6-3403-4b42-a9fc-d2be7871a8f5)
<img width="1680" alt="Screenshot 2024-12-31 at 11 52 06ΓÇ»PM" src="https://github.com/user-attachments/assets/302c46fd-2ea7-400e-8b35-03f2962de29d" />

9. Launch Screen--
<img width="1672" alt="Screenshot 2024-12-31 at 1 32 11ΓÇ»AM" src="https://github.com/user-attachments/assets/60cc0752-619a-4fdf-8e5c-f626fe9f6dae" />

 
## Technologies Used- **Language:** Swift (SwiftUI framework)- **Development Environment:** Xcode- **Database:** Firebase Firestore- **Authentication:** Firebase Authentication
--
## Acknowledgments
 I would like to thank my team members for their collaboration and support throughout the development of this project. This experience has been a valuable opportunity to enhance my skills in iOS development.--
## Contact
 For any questions or further information about my contributions, feel free to contact me
