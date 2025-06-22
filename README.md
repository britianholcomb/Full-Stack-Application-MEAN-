# CS465
CS-465 Full Stack Development with MEAN

# Architecture
In this project, I worked with different types of frontend development including static Express HTML templates, dynamic JavaScript functionality, and a more interactive single-page application (SPA) using Angular. The Express HTML approach was helpful for simple, server-rendered pages, especially for the customer-facing parts of the site. JavaScript added interactivity like form validation. The SPA, on the other hand, provided a smoother user experience by loading data dynamically without needing full page reloads. This approach improved performance and responsiveness, especially for the administrative interface. The backend used a NoSQL MongoDB database because of its flexibility and ability to store data in JSON-like documents, which is a great fit for the kind of dynamic, nested data we were dealing with.

# Functionality
JSON is a lightweight data format used to transfer data between a server and a client. While it’s based on JavaScript, JSON is purely a data format—it doesn’t contain executable code like JavaScript does. In full stack development, JSON acts as the bridge between the frontend and backend. For example, when the frontend makes a GET request to an API, the server responds with data in JSON format, which the frontend can then render dynamically.

# Testing
Testing APIs in a full stack application involves validating the methods (GET, POST, PUT, DELETE) to ensure endpoints behave correctly. For example, we tested if a POST request to /api/trips actually created a new trip and responded with a proper success status and data. When layers of security like authentication and authorization are added (such as token-based auth), testing becomes more complex because you have to simulate login, pass tokens in headers, and verify access control. Understanding endpoint structures and securing them properly is crucial to prevent unauthorized access while ensuring that legitimate users can perform necessary actions.

# Reflection
This course has helped me move closer to my professional goals by giving me hands-on experience with full stack development—from frontend design to backend architecture. I’ve developed skills in building RESTful APIs, working with MongoDB, creating SPAs with Angular, and using tools like Postman for testing. I’ve also strengthened my ability to debug, refactor, and write modular code. 
