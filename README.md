# EJS Shop

This is a simple e-commerce application called EJS Shop. It uses the EJS templating engine and Express.js framework to render dynamic web pages. The application displays a list of products and their details, including title, price, description, category, image, and rating.

## Installation

To run the EJS Shop application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:

   ```bash
   cd ejs-shop
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

## Usage

To start the application, use the following command:

```bash
npm start
```

The application will be accessible at [http://localhost:8080](http://localhost:8080).

## Routes

The EJS Shop application provides the following routes:

- `/`: The home page that displays a list of products.

## Data

The product data is stored in the `data.js` file. It includes an array of product objects with properties such as `id`, `title`, `price`, `description`, `category`, `image`, and `rating`.

## Dependencies

The EJS Shop application uses the following dependencies:

- express: Fast, unopinionated, minimalist web framework for Node.js
- ejs: Embedded JavaScript templates for rendering dynamic web pages

These dependencies are specified in the `package.json` file.
