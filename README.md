**College Social Networking Platform**

This project involved designing and building a custom social networking web application using PHP, MySQL, HTML, CSS, JavaScript and Bootstrap. It is tailored specifically for college students to connect with each other.

**Key Features**

-User profiles - Students can signup and create personal profiles with details like interests, gender, contact information, etc.

-Posting - Students can create text, image, video posts visible to their friends.

-Commenting - Students can comment on and react to posts created by their connections.

-Messaging - Direct messaging functionality to communicate with connections.

-Notifications - Notifying students of friend requests, messages, reactions to their posts.

**Technical Details**

-Developed using PHP, MySQL, HTML5, CSS3, JavaScript (ES6) and Bootstrap

-MySQL used to store user profiles, posts, comments and other application data

-Password hashing used for secure user authentication and session management

-MVC architecture implemented with separation of business logic and presentation views

-AJAX used to send and retrieve data asynchronously for seamless UX

-Responsive UI built using Bootstrap grid and media queries

**Development Workflow**

-Agile methodology

-GitHub for source control

**Architecture**
The application follows a traditional 3-tier architecture:

-Client Tier - This consists of the frontend UI built with HTML, CSS, JavaScript that runs on the user's browser. Communicates with the middle tier via AJAX/XHR calls.

-Application Tier - This tier contains the PHP backend logic for handling request routing, database operations, business logic, and API development.

-Database Tier - MySQL database server for persisting user data, posts, comments and other application information. Optimized through normalization and indexing.

**Optimizations**

Some optimizations implemented:

-Lazy loading of images and comments to improve page load performance.

-CSS and JS minification, compression, caching for faster page loads.

-MySQL indexing on frequently queried columns like post timestamps.

**Learnings**
Key learnings from building this application:

-Implementing core social media functionality like newsfeed, messaging, notifications

-Handling large amounts of data with database optimization techniques

-Building secure user authentication and access control mechanisms

-Development and consumption of REST APIs for frontend/backend communication

-Enabling responsive design across all devices
