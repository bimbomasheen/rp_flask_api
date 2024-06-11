# Flask REST API Project

This is a RESTful API built with Connexion, Flask, SQLAlchemy, and Marshmallow, using SQLite as the database. The API is defined through .yml with OpenAPI. A Swagger UI is also provided for.

## Technologies Used

- Flask: A lightweight WSGI web application framework for building web applications.
- SQLAlchemy: A SQL toolkit and Object-Relational Mapping (ORM) system for Python, providing a full suite of well known enterprise-level persistence patterns.
- Marshmallow: An ORM/ODM/framework-agnostic library for converting complex datatypes, such as objects, to and from Python data types.
- SQLite: A C library that provides a lightweight disk-based database.
- OpenAPI: A specification for machine-readable interface files for describing, producing, consuming, and visualizing RESTful web services.
- Swagger UI: A visual and interactable representation of the API's resources, automatically generated from the OpenAPI specification.

## Getting Started

1. Clone the repository:

   ```
   git clone https://github.com/bimbomasheen/rp_flask_api.git
   ```

2. Install the dependencies:

   ```
   pip install -r req.txt
   ```

3. Run the application:
   ```
   python app.py
   ```

## Swagger UI

Swagger UI available at `/api/ui` endpoint

## API Documentation

The API documentation is available at `/api/docs` endpoint, which is powered by OpenAPI.

## License

[MIT](https://choosealicense.com/licenses/mit/)
