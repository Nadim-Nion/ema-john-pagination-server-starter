## Ema-John Shopping Website (Server-Side) 

This repository contains the server-side implementation for the Ema-John Shopping Website project. The server is built using Express.js and MongoDB, providing API endpoints to support the client-side application.

### Key Features

- **Pagination Support**: The server implements pagination for fetching products in batches. This ensures efficient loading of product data on different pages of the shopping website.
  
- **Persistent Shopping Cart**: The server manages a shared shopping cart across different pages of the website. Users can add products to the cart from any page and view the cart contents at any time.

- **Order Management**: Users can review their selected products and initiate an order by interacting with the website's "Review Order" functionality.

- **Cart Clearing**: A "Clear Cart" button is provided to allow users to empty the shopping cart when desired.

### Technologies Used

- **Express.js**: The server is built using Express.js, a minimalist web framework for Node.js, to handle HTTP requests, routing, and middleware.

- **MongoDB**: The server interacts with a MongoDB database to store and retrieve product data, manage the shopping cart, and facilitate order processing.

### Back-End API Deployment
- Vercel: https://ema-john-pagination-server-starter-snowy.vercel.app/

### API Endpoints

- **GET /products**: Fetches a batch of products based on pagination parameters (`page` and `size`). Products are retrieved from the database with specified limits and offsets to support pagination.

- **POST /productByIds**: Retrieves products based on a list of provided IDs. This endpoint is used to fetch specific products required for order review based on user selections.

- **GET /productsCount**: Returns the total count of products available in the database. This count is utilized for pagination and displaying total product statistics on the client-side.

### Repository Structure

The repository is structured to encapsulate server-side logic for managing product data, cart functionality, and order processing. Key components include:

- **`server.js`**: Main entry point of the server application, setting up Express routes and connecting to the MongoDB database.

- **`controllers/`**: Contains modules for handling different API endpoints, such as product retrieval, cart management, and order processing.

- **`models/`**: Defines MongoDB schemas and models for interacting with the database collections.

- **`middlewares/`**: Houses custom middleware functions used to enhance request handling and validation.

- **`utils/`**: Utility functions and helpers used across the server application.

### Getting Started

To run this server-side application:

1. Clone this repository to your local machine.
2. Install dependencies using `npm install`.
3. Ensure MongoDB is running locally or provide a MongoDB URI in the server configuration.
4. Start the server using `npm start`.

### 🚀 About Me
Hi, I am Nadim Mahmud Nion. I have recently concluded my graduation from the department of Computer Science and Engineering (CSE) at the Daffodil International University (DIU). I have been learning MERN Stack Web Development since 2022. I am expertise in the following skills:

* React 

* Express.js 

* Node.js 

* MongoDB

* Vite

* React Router

* Firebase

* Vercel

* JavaScript

* Advanced JavaScript

* Daisy UI 

* Bootstrap

* Tailwind

* HTML5

* CSS3

* Media Query

I have built multiple projects using these skills. You are invited to my GitHub profile to know about my projects and don't forget to give a star to my projects.

