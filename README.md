Syntecxhub Backend Development Internship

📌Task - Product Crud API

A RESTful API built using **Node.js**, **Express.js**, and **MongoDB** following the **MVC (Model-View-Controller)** architecture. This API allows users to perform CRUD (Create, Read, Update, Delete) operations on products, along with filtering, pagination, and error handling.

📁 Folder Structure

```
Product-CRUD-API/
│
├── config/
│   └── db.js                 # MongoDB database connection
│
├── controllers/
│   └── productController.js  # Business logic for CRUD operations
│
├── models/
│   └── Product.js            # Mongoose Product Schema
│
├── routes/
│   └── productRoutes.js      # API routes
│
├── .env                      # Environment variables
├── .gitignore                # Ignore unnecessary files
├── index.js                  # Entry point of the application
├── package.json              # Project metadata & dependencies
├── package-lock.json         # Auto-generated dependency lock file
└── README.md                 # Project documentation
```


 🚀 Features

- Create Product
- Read All Products
- Read Single Product
- Update Product
- Delete Product
- Filter Products by Category
- Filter Products by Price Range
- Pagination
- Error Handling
- RESTful API Design


 🛠 Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- dotenv


 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Product-CRUD-API.git
```

Move into the project folder:

```bash
cd Product-CRUD-API
```

Install dependencies:

```bash
npm install
```


⚙️ Environment Variables

Create a `.env` file in the project root and add:

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/productdb
```


▶️ Run the Project

Start the server:

```bash
npm start
```

For development:

```bash
npm run dev
```

Server URL:

```
http://localhost:5000
```


📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/products | Get all products |
| GET | /api/products/:id | Get product by ID |
| POST | /api/products | Create a new product |
| PUT | /api/products/:id | Update product |
| DELETE | /api/products/:id | Delete product |


 📄 Sample Product JSON

```json
{
  "name": "Laptop",
  "price": 55000,
  "description": "Dell Inspiron Laptop",
  "category": "Electronics"
}
```


 👩‍💻 Author

Pavithra Pushpa Lakshmi K

B.Tech Artificial Intelligence and Data Science

Aspiring Data Analyst | Python Developer | AI & ML Enthusiast
