# Node.js and AWS Projects

- [Node.js and AWS Projects](#nodejs-and-aws-projects)
  - [Node.js Projects](#nodejs-projects)
    - [Images Processing API](#images-processing-api)
    - [Storefront API](#storefront-api)
  - [AWS Projects](#aws-projects)

## Node.js Projects
### Images Processing API

[GitHub Repo](https://github.com/anazhmetdin/ImgsAPI)

- Images Processing API developed with Node.js and tested using Jasmine.
- The API is organized into separate folders for API endpoints and middleware, ensuring maintainability and easy extension.
- Processed images are cached in the thumbs folder.
- Designed for flexibility, scalability, and seamless integration.

Home Page
![API Home Page](Images/ImgsAPI/home.png)

Images Endpoint Documentation
![Images Endpoint](Images/ImgsAPI/endpoints.png)

Example of the Images endpoint
![Images Endpoint](Images/ImgsAPI/example.png)

### Storefront API

[GitHub Repo](https://github.com/anazhmetdin/storefront)

- Node.js project with TypeScript, bcrypt.js and Jasmine for building an online storefront API.
- The database was constructed using migrations and hosted on PostrgreSQL.
- Endpoints are defined following the pattern of RESTful APIs.
- API Architecture is separted into route, middlewares, models and tests. Where each endpoint is fully tested.
- Some Endpoints require authorization like placing an order.

## AWS Projects
