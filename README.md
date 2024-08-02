# Online Store API

This is an online store API built with FastAPI.

## Dependencies

- FastAPI
- SQLAlchemy
- Pydantic
- Uvicorn
- bcrypt

## Installation

1. Clone the repository:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:
    ```bash
    uvicorn main:app --reload
    ```

## API Endpoints

### Welcome
- `GET /` - Welcome message

### Users
- `POST /users/` - Create a new user
- `GET /users/` - Get list of users
- `GET /users/{user_id}` - Get user by ID
- `PUT /users/{user_id}` - Update user by ID
- `DELETE /users/{user_id}` - Delete user by ID

### Products
- `POST /products/` - Create a new product
- `GET /products/` - Get list of products
- `GET /products/{product_id}` - Get product by ID
- `PUT /products/{product_id}` - Update product by ID
- `DELETE /products/{product_id}` - Delete product by ID

### Orders
- `POST /orders/` - Create a new order
- `GET /orders/` - Get list of orders
- `GET /orders/{order_id}` - Get order by ID
- `PUT /orders/{order_id}` - Update order by ID
- `DELETE /orders/{order_id}` - Delete order by ID
