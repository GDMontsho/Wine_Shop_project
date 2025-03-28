# E-Commerce Backend Project- Wine Shop 🛒

Welcome to my **E-Commerce Backend Project-WineShop**!

In this project I learned:

1. How to build a backend with essential e-commerce functionality.
2. Implement user authentication with JWTs for session persistence.
3. Create and manage product and cart operations.
4. How to apply data validation and sanitation for secure and reliable input handling.
5. How to add admin functionalities and advanced cart features.

### Core Functionalities

1. **User Management**

   - Users should are able to **sign up** and **log in**.
   - I implemented session persistence using **JWTs** to allow users to stay logged in.

2. **Product Management**

   - I pre-seeded the database with an initial set of products.
   - Products have relevant attributes such as `name`, `price`, `description`, and `category`.

3. **Cart Management**

   - Users have a cart to which they can add products.
   - Users can view their cart with a list of added products.

### Extra Features

1. **Admin Role**

   - An `admin` role can:
     - Create new products.
     - Update existing products.
     - Delete products from the database.

2. **Advanced Cart Features**

   - When a product is added to the cart:
     - I added a `quantity` field.
     - Update the quantity if the same product is added more than once.

## Testing

     - I used Postman to test the backend calls.
     - Precice error handling to give developers relevant feedback.

## Installation

1. Clone the repository
2. Install backend dependencies:

   ```bash
   cd backend
   npm install
   npm run dev
   ```

## Future Enhancements

- Build responsive frontend for wineshop
- Advanced filtering and search
-

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

Happy Hacking!!!🤖
