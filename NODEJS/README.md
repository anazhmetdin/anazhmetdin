# Node.js Projects

- [Node.js Projects](#nodejs-projects)
  - [Images Processing API](#images-processing-api)
  - [Storefront API](#storefront-api)

## Images Processing API

[GitHub Repo](https://github.com/anazhmetdin/ImgsAPI)

- Images Processing API developed with Node.js and tested using Jasmine.
- The API is organized into separate folders for API endpoints and middleware, ensuring maintainability and easy extension.
- Provides a comprehensive set of image processing functionalities.
- Includes a live example hosted on railway.app for interactive testing.
- README contains instructions for building and running the app locally.
- Images can be obtained by specifying filename, width, and height parameters.
- Original images are stored in the repository's images folder.
- Processed images are cached in the thumbs folder.
- Designed for flexibility, scalability, and seamless integration.

Home Page
![API Home Page](Images/ImgsAPI/home.png)

Images Endpoint Documentation
![Images Endpoint](Images/ImgsAPI/endpoints.png)

Example of the Images endpoint
![Images Endpoint](Images/ImgsAPI/example.png)

## Storefront API

[GitHub Repo](https://github.com/anazhmetdin/storefront)

- Node.js project with TypeScript, bcrypt.js and Jasmine for building an online storefront API.
- The API supports the frontend application, allowing users to browse products, view product details, and manage their orders.
- Endpoints are defined following the pattern of RESTful APIs.
- API Architecture is separted into route, middlewares, models and tests. Where each endpoint is fully tested
- Products:
  - Index: 'products/' [GET] - Retrieves a list of all products.
  - Show: 'products/:id/' [GET] - Retrieves the details of a specific product.
  - Create [token required]: 'products/' [POST] - Creates a new product (authentication token required).
- Users:
  - Index [token required]: 'users/' [GET] - Retrieves a list of all users.
  - Show [token required]: 'users/:id/' [GET] - Retrieves the details of a specific user.
  - Create [token required]: 'users/' [POST] - Creates a new user (authentication token required).
- Orders:
  - Current Order by user (args: user id)\[token required\]: 'orders/:id/' [GET] - Retrieves the current order for a specific user (authentication token required).
  - Place an Order by user (args: user id)\[token required\]: 'orders/:id/' [POST] - Places an order for a specific user (authentication token required).
