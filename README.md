# CS-360

**Summary of Requirements and Goals:**
The WeightTrackerApp is designed to help users track their daily weight, set personal weight goals, and receive notifications when they achieve their desired weight. The main user needs addressed by this app are weight management, progress tracking, and goal achievement notifications. The app simplifies the process of logging daily weight entries and visualizing progress, ensuring users stay motivated toward their health goals.

**Screens and Features:**
To support user needs, the app includes key screens such as:

**Login Screen: Allows users to securely log in or create an account.**
Daily Weight Entry Screen: Facilitates easy logging of daily weight data.
Goal Weight Screen: Allows users to set and update their target weight.
Weight Tracking Screen: Displays the user's weight history in a grid, helping them visualize their progress.
The UI was designed with simplicity and accessibility in mind, ensuring all elements were easy to navigate, even for non-tech-savvy users. My design choices, such as large buttons and clear instructions, were successful because they provided a smooth and intuitive user experience.

**Coding Approach:**
I approached the coding process by focusing on modularity and code reusability. Breaking down the app into smaller components (such as user authentication, database operations, and UI interactions) allowed me to develop each part systematically. I utilized object-oriented principles to ensure my code was maintainable and scalable. In the future, this strategy can be applied to projects requiring similar structuring and organization.

**Testing and Code Functionality:**
To ensure the functionality of the app, I conducted iterative testing using Android Studio's Emulator. I tested each feature after implementation, including login functionality, weight entry, goal setting, and database interactions. This process was essential as it revealed minor bugs early on, such as data handling issues in the SQLite database. Fixing these issues promptly ensured smooth app operation and a positive user experience.

**Overcoming Challenges:**
One of the significant challenges I faced during development was implementing the SQLite database functionality, especially ensuring that user data persisted even after the app was closed. To overcome this, I had to research and experiment with various SQLite techniques and test data storage under different scenarios. This required a lot of troubleshooting, but ultimately led to a successful implementation.

**Key Success:**
The component I am particularly proud of is the weight tracking feature, which reads and displays user data from the SQLite database in a clean, grid-based UI. This required me to combine my skills in database management and user-centered design, demonstrating my ability to implement both backend functionality and frontend design that work harmoniously.
