Kofi Edu Yankson
10211100299
B.Sc Computer Science


E-Commerce Application
This application is a fully functional e-commerce solution built with Next.js, Prisma, Tailwind CSS, Node.js, React, and Stripe. It features both an Admin and User portion, each with specific functionalities for managing products, orders, and user interactions.
Features
User Side:
Product Viewing: Users can view products ordered by popularity or newest products.
Purchasing: Users can purchase products by providing valid payment information managed by Stripe.
Order History: Users can view all orders they've made on the site.
Download Links: After a successful purchase, users are provided with a download link for the product. The download link expires after a set amount of time.
Restriction on Re-Purchase: Users are not allowed to purchase products they have already bought.
Availability Check: Products marked as unavailable cannot be purchased by users.
Admin Side:
Product Management: Admins can add, edit, delete, and activate products. Products that are not activated will not appear on the customer-facing side of the application.
Data Consistency: When a product is modified, users who have already purchased and downloaded the product will not see the changes applied to their version.
Dashboard: Admins have a dashboard displaying key metrics, including:
Total sales amount
Total number of customers
Number of activated and inactive products
Pages for Admin:
Dashboard
Products
Customers
Sales
Frontend:
Home Page: Displays the most popular and newest products for easy browsing.
Products Page: Allows users to browse all available products.
My Orders Page: Users can view the history of their orders and access past purchases.
Responsive Design: Built with Tailwind CSS, ensuring a responsive and user-friendly interface.
Backend:
Database: Utilizes Prisma to interact with the database, managing user accounts, products, and orders.
Payment Processing: Integrated with Stripe to securely manage payments and provide a smooth checkout process.
Additional Technologies:
Node.js: The backend is powered by Node.js to handle server-side logic and API requests.
React: React is used for caching and to improve performance on the user side.

Technologies Used:
Next.js for the frontend and server-side rendering.
Prisma as the database ORM.
Tailwind CSS for styling and responsive design.
Node.js for backend development.
React for caching and dynamic rendering.
Stripe for payment processing.

Setup Instructions:
Clone the repository:
 git clone <repository-url>


Navigate into your project folder:
 cd <project-folder>


Install dependencies using npm:
 npm install


Set up your .env file with your Stripe API keys and database connection string.
Run the application:
 npm run dev




