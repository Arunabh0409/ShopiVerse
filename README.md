# ShopiVerse🎯

Welcome to ShopiVerse🎯!

---
## Table of Contents📄

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

---
## Features💫

### User Authentication

ShopiVerse offers a robust user authentication system that ensures secure access to the app.

- **Register**: Users can register their accounts using a unique email address and password.
- **Login**: Subsequently, log in with their credentials.
- **Authentication**: Implemented with JWT tokens. The user remains signed in until they close the tab.
- **Form Validation**: Various checks on login and register forms to ensure robustness.

### Application Walkthrough

Once logged in, users gain access to their personalized dashboard.( **BY ADMIN ONLY** ) ( **CRUD OPERATIONS ON PRODUCTS** ) 

- **Add Products**: Create new Products by specifying Posts details.
- **Update Products**: Modify existing Products.
- **Read all Products**: View a comprehensive list of all their Products.
- **Delete Products**: Remove obsolete Products from their list, keeping their dashboard clutter-free.

### Filteration of Products based on Category + Price Ranges 

### Search Functionality : Based on User Search Keywords search Products having Matching in Name and Description 

### Pagination ( limiting the number of products showed on each page to enhance user experience )

### Add to Cart ( Add your favourite products to Cart and buy them )
- **Local Storage Concept For Storing User Products In Browser**
- **State Management Using Context Api ( Maintaining Global State )**

### Form Validation

- **Form Validation**: Validation checks prevent users from setting completion times earlier than the current date or a negative priority, ensuring data consistency.

---

## Installation🛠️

To run **ShopiVerse** locally, follow these steps:

1. Clone the repository: `git clone https://github.com/Arunabh0409/ShopiVerse.git`
2. Navigate to the project directory: `cd ShopiVerse`
3. Install server dependencies: `npm install`
4. Navigate to the client directory: `cd client`
5. Install client dependencies: `npm install`
6. Go back to the main project directory: `cd ..`
7. Create a `.env` file and add the following:
8. NODE_ENV: development
9.  PORT: desired_port_number / 5000
10. MONGO_URL: MongoDB_connection_URL
11. JWT_SECRET: a_string_used_for_encrypting_tokens
12 Run the app: `npm run dev`

---

## Usage💻

1. Register an account using your name, unique email address, and password.
2. Log in to access your personalized dashboard.
3. Add your Posts.
4. Update or delete Posts as needed.

Stay motivated, buy products with ShopiVerse !

---

## License📄

This project is licensed under the MIT License. Please feel free to use, modify, and distribute this code according to the terms of the license.

We hope ShopiVerse helps you stay focused and accomplish your aspirations.
Feel free to star the repository if you find it useful, and don't forget to share it with others who might benefit from this tool.
Happy Shopping! 🎯



