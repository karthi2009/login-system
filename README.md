Signup:

Users can create an account by entering their name, email, contact number, and password.
Password confirmation ensures the user has entered the intended password.
The system generates a username automatically from the email address (up to the @ symbol).
User data is stored in a binary file (Users.dat).
Login:

Users log in using their username and password.
Upon successful login, the system displays their details (Full Name, Email, Username, Contact Number).
Invalid credentials are handled with appropriate error messages.
File Handling:

User data is persisted in a file, ensuring it remains available even after the program is closed.
Password Masking:

While typing the password, characters are hidden (replaced with *) for security.
Input Validation:

Passwords are matched during signup to ensure accuracy.
Usernames are checked against stored data to verify registration status during login.
