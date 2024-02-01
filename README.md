# Login System using Servlet and JSP

## Overview
This is a simple login system developed using Java Servlets and JSP. Users can log in with predefined credentials, and upon successful authentication, they are redirected to a welcome page. A logout feature is also included.
## Files
## 1. Login.java
•	Description: Servlet handling the login functionality.
•	Endpoint: /Login (configured using @WebServlet annotation)
•	Features:
•	Validates username and password.
•	Creates a session for the authenticated user.
•	Redirects to welcome.jsp on successful login.
•	Redirects to login.jsp on failed login.
## 2. Logout.java
•	Description: Servlet handling the logout functionality.
•	Endpoint: /Logout (configured using @WebServlet annotation)
•	Features:
•	Invalidates the session.
•	Redirects to login.jsp after logout.
## 3. welcome.jsp
•	Description: JSP page displayed after successful login.
•	Features:
•	Displays a welcome message.
## 5. aboutus.jsp
•	Description: JSP page providing information about the website or application.
•	Features:
•	Placeholder content.
## 6. videos.jsp
•	Description: JSP page displaying videos or related content.
•	Features:
•	Placeholder content.
## Deployment
Deploy the WAR file generated after building the project on a servlet container. Make sure the container is properly configured.
## Note
In a production environment, we use secure authentication mechanisms, handle password hashing, and integrate with a database for user management.

