# Inventory Management System

A comprehensive inventory management system designed to streamline inventory tracking, order management, and stock control.

## Project Structure

The project is organized into several microservices:

- `api_gateway/`: Main API gateway service that routes requests to appropriate services
- `inventory/`: Handles inventory management operations
- `order/`: Manages order processing and tracking

## Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   # Install dependencies for each service
   cd api_gateway
   pip install -r requirements.txt
   cd ../inventory
   pip install -r requirements.txt
   cd ../order
   pip install -r requirements.txt
   ```

## Running the Application

1. Start the API Gateway:
   ```bash
   cd api_gateway
   python app/main.py
   ```

2. The application will be available at `http://localhost:8000`

## Features

- Inventory Management:
  - Track stock levels
  - Manage product categories
  - Update product information

- Order Management:
  - Create and process orders
  - Track order status
  - Generate order reports

- API Gateway:
  - Route requests to appropriate services
  - Handle authentication and authorization
  - Provide unified API documentation

## API Documentation

API documentation is available through the API Gateway at:
`http://localhost:8000/docs`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue in the GitHub repository or contact the development team.
