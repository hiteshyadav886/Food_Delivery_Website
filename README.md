Food Delivery Website

Introduction:
A comprehensive Food Delivery Website including Admin, Restaurant, and User interfaces, designed for efficient order processing and delivery management.

Features:
Admin Side(My Contribution)-
  Login and Register page: Register and Login keeping in mind necessary fields with required conditions
  Dashboard: Overview of key metrics and statistics.
  All-Order List: View orders by status (Pending, Ongoing, Delivered, Cancelled).
  Restaurant Management: View and reject restaurants.
  User Management: View user accounts and details.
  
Restaurant Side-
  View metrics and manage orders and menu items.
  Update restaurant profile details.
  
User Side-
  Browse restaurants, place orders, and track order status.
  Review restaurants and delivery personnel.
  Manage user profile and order history.

Technologies Used:
  Frontend: HTML, CSS, JavaScript, React.js
  Backend: Node.js, Express.js, MongoDB, Mongoose

Setup and Installation:
1. Clone the repository-
git clone https://github.com/hiteshyadav886/Food_Delivery_Website.git
2. Navigate to the project directory:
cd Food_Delivery_Website
3. Install dependencies:
npm install
4. Set up environment variables: Create a .env file with the following content:
PORT=3001
MONGODB_URL= ://localhost:27017/food_delivery
5. Run the server:
npm start

Usage:
Admin Interface: Access via /admin
Restaurant Interface: Access via /restaurant
User Interface: Access via /

Folder Structure
(admin-frontend):
/public
/src
  /components
    AllOrders.css
    AllOrders.js
    Cancelled.js
    Dashboard.css
    Dashboard.js
    Delivered.js
    final.png
    Header.css
    Header.js
    Login.css
    Login.js
    logo.jpg
    Order.css
    Processing.js
    ProtectedRoute.js
    Received.js
    Register.css
    Register.js
    RestaurantList.css
    RestaurnatList.js
    Sidebar.css
    Sidebar.js
    UserList.css
    UserList.js
  App.css
  App.js
  App.test.js
  index.css
  index.js
  reportWebVitals.js
  setupTests.js
package-lock.json
package.json
README.md

(backend):
/models
    Addrestaurant.js
    AdminModel.js
    Cartmodel.js
    OrderModel.js
    Resmodel.js
    UserModel.js
/routes
    addRestRoute.js
    adminRoute.js
    authRoute.js
    cartRoute.js
    orderRoutes.js
    ownerRoute.js
    restDetailRoute.js
    restOrderRoute.js
    restRoute.js
/controller
    AdminController.js
    AdminCtrl.js
    AdminOrderController.js
    cartCtrl.js
    controller.js
    menuCtrl.js
    orderCtrl.js
    RestCtrl.js
    RestAdmin.js
    reviewCtrl.js
    UserAdmin.js
    userCtrl.js
/middleware
    AdminMiddleware.js
    menuMulter.js
    Middleware.js
    multer.js
/public
index.js
.env
packagr.json
package-lock.json

Contact
Hitesh Yadav
GitHub :      https://github.com/hiteshyadav886
LinkedIn :    linkedin.com/in/hitesh-yadav-028579249
Email:        hiteshyadav886@gmail.com
