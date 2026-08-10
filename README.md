E-Commerce App 🛒
This E-Commerce App is a full-stack web application that enables users to explore a variety of products, filter them based on specific attributes, and add items to their cart by selecting desired variants like size. Users can place orders by providing delivery addresses and selecting their preferred payment method—either Cash on Delivery (COD) or Online Payment. The application integrates Stripe as the online payment gateway, ensuring secure and seamless transactions.

Additionally, an Admin Dashboard is included, where administrators can manage the store by uploading new products, deleting existing ones, and viewing all products listed in the store.




DEMO 🌐
UI Live 👉 LINK

Admin Dashboard 👉 LINK




Table of Contents 📜
Key-Features

Technologies-Used

Installation-and-Setup

Screenshots

Future-Enhancements

Contribution

License




Key-Features
For Users:
Product Exploration: Browse a variety of products and filter them by category, size, and other attributes.
Cart Management: Add, view, and modify products in the cart.
Order Placement: Provide delivery addresses and select payment methods (COD or online payment via Stripe).
Secure Payments: Stripe integration for secure online payments.
For Admins:
Product Management: Add, edit, or delete products.
Order Monitoring: View orders placed by users.
Inventory Overview: Access all products listed in the store.



Technologies-Used
This project is built using the MERN Stack (MongoDB, Express.js, React.js, and Node.js), ensuring a robust, scalable, and modern web application.

Frontend: React.js for building a responsive and interactive user interface.
Backend: Node.js and Express.js for API development.
Database: MongoDB for storing user, product, and order data.
Payment Gateway: Stripe for secure online transactions.



Installation-and-Setup
Clone the repository:
git clone https://github.com/elyse502/ecommerce-app.git
cd ecommerce-app
Install dependencies for both client and server:
cd backend
npm install

cd frontend
npm install

cd admin
npm install
Create an .env file in the root directory for server-side configuration and add the following:
MONGO_URI="your_mongodb_connection_string"
CLOUDINARY_API_KEY="your_cloudinary_api_key"
CLOUDINARY_SECRET_KEY="your_cloudinary_secret_key"
CLOUDINARY_NAME="your_cloudinary_name"
JWT_SECRET="your_jwt_secret_key"
ADMIN_EMAIL="admin_email_address"
ADMIN_PASSWORD="admin_password"
STRIPE_SECRET_KEY="your_stripe_secret_key"
Start the development server:
Back-End
npm run server
Front-End
npm run dev
Admin
npm run dev
Access the app on http://localhost:5173/ for UI and http://localhost:5174/ for Admin Panel.



Screenshots
User Dashboard 👤
ui0


ui1







Admin Dashboard 🔐
ap0


ap1




Future-Enhancements
Add product reviews and ratings.
Implement user authentication with social logins.
Add a "Wishlist" feature for users to save products for future reference.



Contribution
Contributions are welcome! Feel free to fork this repository, create a new branch, and submit a pull request with your updates or fixes.
