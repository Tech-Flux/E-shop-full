# 📦 **Ecommerce Web App**

![Ecommerce Web App](https://i.imgur.com/ucdCcWz.jpeg)

Welcome to the Ecommerce Web App! This project is a full-featured ecommerce application built with React, Node.js, Express, and MongoDB. It provides a seamless shopping experience with a user-friendly interface, robust authentication, and various payment methods.

## 🛠️ **Features**

- **User Authentication:** Secure login and registration using JWT.
- **Product Listing:** Display a variety of products fetched from the backend.
- **Shopping Cart:** Add, remove, and manage products in the cart.
- **Coupon Code Validation:** Apply discount codes and update the total price dynamically.
- **Payment Integration:** Choose between PayPal and M-PESA for payment.
- **Order Summary:** View the total amount, including discounts, before checkout.

## 🚀 **Technologies Used**

- **Frontend:**
  - React
  - Tailwind CSS
  - React Icons

- **Backend:**
  - Node.js
  - Express
  - MongoDB
  - Mongoose

## 📂 **Project Structure**

```plaintext
E-shop-Web-App/
├── backend/
│   ├── node_modules/
│   ├── index.js
├   ├── upload/
│   └── package.json
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── index.js
│   ├── tailwind.config.js
│   └── package.json
├── README.md
└── package.json

```

## 🏁 **Getting Started**

Follow these steps to set up the project locally.

### Prerequisites

- Node.js
- MongoDB
- npm or yarn

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/x-poison/E-shop-full.git
    cd E-shop-full
    ```

2. **Backend Setup:**

    ```bash

    cd backend
    npm install

    ```
    - Enter the MongoDB connection string
    - Obtain one here [![MongoDB](https://img.icons8.com/color/48/000000/mongodb.png)](https://www.mongodb.com/)
    - Goto backend/index.js and paste it as shown bellow

    ```bash

    // Database connection with mongoDB

    mongoose.connect("MONGODB URI");

    ```

    - Start the backend server:

    ```bash
    node index.js

    ```

3. **Frontend Setup:**

    Open a new terminal window and navigate to the project root directory:

    ```bash
    cd frontend
    npm install
    ```

    Start the frontend development server:

    ```bash
    npm run dev

    ```

### Running the Application

- The backend server will run on `http://localhost:4000`.
- The frontend development server will run on `http://localhost:5173`.

### Features

- **Product Listing:** Browse through a variety of products.
- **Shopping Cart:** Add or remove products from the shopping cart.
- **Checkout:** Securely checkout using PayPal or M-PESA.
- **Authentication:** Register and log in to manage your orders.
- **Coupon Codes:** Apply coupon codes for discounts.

## List Product
![Ecommerce Web App](https://i.imgur.com/qGdKi1k.jpeg)

## Add Product
![add](https://i.imgur.com/o8R30Qx.jpeg)

### Project Structure

- **Backend:** Node.js, Express, MongoDB, Mongoose
- **Frontend:** React, Context API for state management

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

### Contact

For any inquiries, please reach out to [your-email@example.com].
