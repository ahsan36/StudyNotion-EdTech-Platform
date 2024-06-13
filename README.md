# # Project Description 📝
StudyNotion is a fully functional ed-tech platform that enables users to create, consume, and rate educational content.
The platform is built using the MERN stack, which includes ReactJS, NodeJS, MongoDB, and ExpressJS.

# # System Architecture 🏰

☝ The StudyNotion ed-tech platform consists of three main components:
The front end, the back end, and the database. The platform follows a client-server architecture, with the front end serving as the client and the back end and database serving as the server.

# 🎨 Front-end
The front end of the platform is built using ReactJS, which is a popular JavaScript library for building user interfaces. ReactJS allows for the creation of dynamic and responsive user interfaces also Loading Skeleton, which are critical for providing an engaging learning experience to the students. The front end communicates with the back end using RESTful API calls.

# ⚙️ Back-end
The back end of the platform is built using NodeJS and ExpressJS, which are popular frameworks for building scalable and robust server-side applications. The back end provides APIs for the front end to consume, which include functionalities such as user authentication, course creation, and course consumption. The back end also handles the logic for processing and storing the course content and user data.

# 🛢️ Database
The database for the platform is built using MongoDB, which is a NoSQL database that provides a flexible and scalable data storage solution. MongoDB allows for the storage of unstructured and semi-structured data, which is useful for storing course content such as videos, images, and PDFs. The database stores the course content, user data, and other relevant information related to the platform.

**The front end of StudyNotion has all the necessary pages that an ed-tech platform should have. Some of these pages are:**
# For Students:

**Homepage 🏠:** A brief introduction to the platform with links to the course list and user details and random background. 
<br>
**Course List 📚:** A list of all the courses available on the platform, along with their descriptions and ratings.
<br>
**Wishlist 💡:** Displays all the courses that a student has added to their wishlist.
<br>
**Cart Checkout 🛒 :** Allows the user to complete course purchases.
<br>
**Course Content 🎓:** Presents the course content for a particular course, including videos and related material.
<br>
**User Details 👤:** Provides details about the student's account, including their name, email, and other relevant information.
<br>
**User Edit Details ✏️:** Allows students to edit their account details.

# For Instructors:

**Dashboard 📊:** Offers an overview of the instructor's courses, along with ratings and feedback for each course.
<br>
**Insights 📈:** Provides detailed insights into the instructor's courses, including the number of views, clicks, and other relevant metrics.
<br>
**Course Management Pages 🛠️:** Enables instructors to create, update, and delete courses, as well as manage course content and pricing.
<br>
**View and Edit Profile Details 👀:** Allows instructors to view and edit their account details.

# Back-end ⚙️
The back-end of the platform is built using NodeJS and ExpressJS, providing APIs for the front-end to consume. These APIs include functionalities such as user authentication, course creation, and course consumption. The back-end also handles the logic for processing and storing the course content and user data.

## Back-end Features
**User Authentication and Authorization 🔐:** Students and instructors can sign up and log in to the platform using their email addresses and passwords. The platform also supports OTP (One-Time Password) verification and forgot password functionality for added security.
<br>
**Course Management 🛠️:** Instructors can create, read, update, and delete courses, as well as manage course content and media. Students can view and rate courses.
<br>
**Payment Integration 💳:** Students will purchase and enroll in courses by completing the checkout flow, followed by Razorpay integration for payment handling.
<br>
**Cloud-based Media Management ☁️ :** StudyNotion uses Cloudinary, a cloud-based media management service, to store and manage all media content, including images, videos, and documents.
<br>
**Markdown Formatting ✍️:** Course content in document format is stored in Markdown format, allowing for easier display and rendering on the front-end.
<br>
Data Models and Database Schema
The back-end of StudyNotion uses several data models and database schemas to manage data, including:

**Student Schema 🧑‍🎓:** Includes fields such as name, email, password, and course details for each student.
<br>
**Instructor Schema 👩‍🏫:** Includes fields such as name, email, password, and course details for each instructor.
<br>
**Course Schema 📚:** Includes fields such as course name, description, instructor details, and media content.
<br>

# Database 🛢️
The database for the platform is built using MongoDB, a NoSQL database that provides a flexible and scalable data storage solution. MongoDB allows for the storage of unstructured and semi-structured data. The database stores the course content, user data, and other relevant information related to the platform.

<br>



# React & Tailwind CSS Starter Pack

This is a starter pack for creating React projects with Tailwind CSS configured. It uses React version **18.2** and Tailwind CSS version **3.2**.

## Usage

This starter pack includes a basic setup for using **Tailwind CSS with React**. To start building your own components and styles, follow these steps:

1. Clone the repository to your local machine.
    ```sh
    git clone https://github.com/thepranaygupta/react-tailwind-css-starter-pack.git
    ```

1. Install the required packages.
    ```sh
    cd react-tailwind-css-starter-pack
    npm install
    ```

1. Start the development server.
    ```sh
    npm start
    ```
1. Open the project in your browser at [`http://localhost:3000`](http://localhost:3000) to view your project.
1. Create your React components and add your styles using Tailwind classes. You can also create new CSS files and import them into your components.

The project is set up to use `postcss-cli` to process your CSS files. You can add your own `tailwind.config.js` file to customize your Tailwind setup.

## Contributing

Contributions are welcome! If you have any suggestions or find any issues, please feel free to open an issue or a pull request.
