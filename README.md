# My Online Store


## Project Overview

My online Store is a web-based retail application designed to demonstrate the capabilities of Angular and Node.js in creating a dynamic and responsive online shopping experience. This project serves as the MVP (Minimum Viable Product) for an e-commerce platform, allowing users to browse products, manage a shopping cart, and complete purchases securely.

### Tagline
Empowering your shopping experience with technology-driven solutions.

## Features

- **Product Browsing**: Users can view a list of available products.
- **Product Details**: Click on any product to see more detailed information.
- **User Authentication**: Secure login and registration system.
- **Shopping Cart**: Users can add items to their cart and manage them.
- **Checkout Process**: Integrated payment solution for order processing.

## Technologies

- **Frontend**: Angular
- **Backend**: Node.js with Express
- **Database**: PostgreSQL
- **APIs**: Stripe for payment processing
- **Other**: Docker for containerization, Heroku for deployment

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- Angular CLI
- PostgreSQL
- Docker (optional)

### Installing

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mystore.git
   cd mystore
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up the database**
   - Create a PostgreSQL database and note the credentials.
   - Run the SQL scripts found in `/database` to set up the schema.

4. **Configure environment variables**
   - Rename `.env.example` to `.env`.
   - Update the `.env` file with your database credentials and other configurations.

5. **Run the application**
   ```bash
   npm start
   ```
   Visit `http://localhost:4200` to view the application.

## Deployment

To deploy this project on Heroku, follow these steps:

1. **Create a Heroku account and log in**
2. **Set up Heroku CLI on your machine**
   - Refer to the [Heroku documentation](https://devcenter.heroku.com/articles/heroku-cli) for setup instructions.
3. **Deploy the application**
   ```bash
   heroku create
   git push heroku master
   heroku open
   ```

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests to the `develop` branch. Ensure you follow the established code style and update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc.
