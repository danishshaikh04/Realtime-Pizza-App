**Real-Time Pizza Order Tracking App**


This is a real-time food ordering application built using Node.js, Express.js, MongoDB, HTML, Sass, and Razorpay for payment integration. The app allows users to browse food items, place orders, and track order status in real-time. It includes separate admin and user panels for managing food listings, orders, and payments.

**Features**
**Real-Time Order Tracking:** 

Users can track the status of their pizza orders in real-time using WebSocket technology.


**Admin Panel:**

Manage pizza listings, prices, and availability.
View and update order statuses.


**User Panel**:

Place new pizza orders.
Track order status and history.

**Payment Integration:**

Integrated Razorpay payment gateway for secure online payments.

**Technologies Used**

**Backend:**
Node.js
Express.js
MongoDB (with Mongoose for data modeling)

**Frontend:**

HTML
Sass (SCSS) for styling

**Real-Time Communication:**

WebSocket with Socket.io

**Payment Integration:**

Razorpay SDK for payment processing

**Installation**

**Clone the repository:**

git clone [https://github.com/yourusername/realtime-pizza-app.git](https://github.com/danishshaikh04/Realtime-Pizza-App.git)

Install dependencies:

cd realtime-pizza-app
npm install


**Set up environment variables:**


Create a .env file in the root directory.
Define the following variables:




PORT=3000

MONGODB_URI=mongodb://localhost/pizza-app

RAZORPAY_KEY_ID=your_razorpay_key_id

RAZORPAY_KEY_SECRET=your_razorpay_key_secret


**Start the server:**

npm start


Access the application:
Open your web browser and navigate to http://localhost:3000.


**Usage**

**Admin Panel:**

Access the admin panel by visiting /admin route.
Log in using admin credentials.
Manage pizza listings and view order details.

**User Panel:**

Access the user panel by visiting /user route.
Sign up or log in as a user.
Place new pizza orders and track order status.
