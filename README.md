# Flask with MySQL Integration

This project demonstrates how to build a web application using Flask with MySQL as the database backend. The application includes user authentication with secure password hashing and routes for playing a bubble game.

## Features

- User signup and signin with secure password storage using bcrypt.
- MySQL integration for user data storage.
- Dynamic HTML rendering with Flask templates.

## Prerequisites

- Python 3.7+
- MySQL Server


## Project Structure

```plaintext
.
├── app.py             # Main application file
├── templates/         # HTML templates
│   ├── bubble.html    # Home page template
│   ├── enter.html     # Post-login template
│   ├── index.html     # Game template
│   ├── signup.html    # Signup page template
│   └── signin.html    # Signin page template
└── .env               # Environment variables (optional)
```

## Future Improvements

- Implement session management for authenticated users.
- Add more features to the game.
- Improve error handling and input validation.
- Write unit tests for better reliability.

---

