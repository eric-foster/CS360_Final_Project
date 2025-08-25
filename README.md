# CS360_Final_Project
## 1. Requirements and Goals
The goal of my app was to create a functional inventory control application that allows users to manage their own data securely. The app was designed to meet the needs of individual users by supporting account creation, secure login, and persistent storage of inventory data. A key requirement was ensuring that each user only sees and manages their own items, which addressed privacy and personalization needs. By combining authentication, CRUD operations, and SMS notification functionality, the app provided a practical solution to tracking and managing inventory.

## 2. Screens and Features
To meet user needs, the app included several key screens: a login/registration screen, a dashboard that displays user-specific inventory in a grid, an add-item screen, and a detail screen for updating or removing items. Features like plus/minus buttons for quantity adjustments, update functionality, and a back-navigation option ensured smooth and intuitive workflows. My UI design kept users in mind by emphasizing clarity, simplicity, and easy navigation. The design was successful because it minimized clutter and ensured that all primary functions were accessible within one or two taps.

## 3. Coding Approach
My coding approach was iterative and modular, building the app in small, testable components rather than attempting to complete everything at once. I used strategies like separating data access with DAO classes, passing user IDs through intents for personalization, and writing concise, well-commented code for readability and maintainability. These strategies allowed me to isolate problems quickly and make incremental progress. In the future, this approach can be applied to larger projects to ensure scalability and reduce errors during development.

## 4. Testing
I tested the app frequently using the Android Emulator, checking functionality after implementing each feature. This included verifying login behavior, ensuring CRUD operations updated the database correctly, and testing navigation flows between activities. Testing was important because it revealed issues such as data not refreshing properly on the dashboard or missing constraints in the UI that affected layout. By identifying these problems early, I was able to refine the app and make it more reliable before finalization.

## 5. Overcoming Challenges
Throughout the project, one of the main challenges I faced was ensuring that each user only accessed their own data while maintaining a simple and intuitive design. To overcome this, I innovated by passing user IDs into the database queries and filtering all inventory items by account. Another challenge was refreshing the dashboard without requiring the user to log out and back in, which I solved by reloading data on activity resume. These adjustments required creative problem-solving and taught me to think more critically about app architecture.

## 6. Areas of Success
I was particularly successful in implementing the database and user authentication components of the app. These features demonstrated my ability to structure persistent data storage, enforce data privacy across different users, and integrate the database with the UI in real time. Successfully linking the login system with user-specific inventory management showcased both my technical skills and my understanding of user-centered design. This component of the app was a strong demonstration of my growing knowledge and ability to build functional, secure, and scalable mobile applications.
