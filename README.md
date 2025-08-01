# Simple Blog App

This is a simple blog application built with React (frontend) and JSONBin.io (as the backend database). It supports user registration, login, and complete blog post CRUD operations (Create, Read, Update, Delete). Email notifications are handled using EmailJS.

![Screenshot](/src/assets/img/blog-logo.png)

## Features

✅ User Authentication (Register, Login, Logout)
📝 Create, Edit, and Delete Posts
🔒 Protected Routes for Authenticated Users
🖼️ Optional Image Upload for Posts
📬 Contact Form with EmailJS Integration
💻 Responsive UI (Mobile/Desktop)

## Technologies Used

### Frontend
- React
- React Router DOM
- Axios
- Bootstrap (React-Bootstrap)

### Backend
- EmailJS (for contact form)
- JSONBin.io (used as REST API storage)

## How to Use

### Prerequisites

- Node.js and npm installed on your machine

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/olusegunadejoludev/blog_app.git
   ```
   
2. Navigate to the project directory:
   ```
   cd blog_app
   ```
   
3. Install dependencies:
   ```
   npm install
   ```
  
4. Set up environment variables:
   - Create a .env file in the root of the project and add the following variables:
     ```
     REACT_APP_JSONBIN_API_KEY=your_jsonbin_api_key
     REACT_APP_JSONBIN_BIN__USER_ID=your_users_bin_id
     REACT_APP_JSONBIN_BIN__POSTS_ID=your_posts_bin_id

      REACT_APP_EMAILJS_SERVICE_ID=your_emailjs_service_id
      REACT_APP_EMAILJS_TEMPLATE_ID=your_emailjs_template_id
      REACT_APP_EMAILJS_PUBLIC_KEY=your_emailjs_public_key

     ```
    
5. ▶️ Run the App:
   ```
   # Navigate to the project directory
   cd blog_app

   # Start the server
   npm start
   ```
   
6. Open your web browser and visit http://localhost:3000 to use the blog app.

7. 📬 Contact Form Setup (EmailJS)
   
   To enable the contact form:
   ```
   Create an account at EmailJS
   Set up your email service, template, and get your public key
   Copy those values into your .env file as shown above

   ```
   
8.  Image Upload Support

   To enable image upload support:
   ```
   When creating or editing a blog post, users can upload an image file. This image is stored as a base64 string in the JSONBin data for that post and rendered in the blog UI.

   ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you would like to contribute to this project.