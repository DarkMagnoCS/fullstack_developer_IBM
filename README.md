# Dealership Architecture Capstone Project

This project showcases the creation of a comprehensive **dealership architecture** with the following key components:

- **Dealership Landing Page**: A fully deployed webpage where users can view and interact with dealership information.
- **"About Us" Section**: A dedicated section that provides a detailed background of the dealership.
- **Full CRUD Functionality**: Enables users to **create**, **read**, **update**, and **delete** dealership records seamlessly.
- **Database Integration**: The project integrates with a relational database to manage dealership records efficiently.
- **API Integration**: The architecture includes endpoints for interacting with the backend via **RESTful API** methods.

## Technologies Used

- **Python**: Used for backend development.
- **Flask**: Handles the web server logic and routing.
- **HTML/CSS**: Frontend structure and styling.
- **JavaScript**: Adds interactivity to the webpage.
- **PostgreSQL**: Manages the relational database for storing dealership records.
- **Docker**: Used to containerize the project, ensuring a consistent environment.


## Key Features

- **Landing Page**: A visually appealing webpage displaying the dealership’s inventory, with options to filter and search for vehicles.
- **Inventory Management**: Backend support for managing car inventory, including options for **adding**, **updating**, **deleting**, and **viewing** cars.
- **Search and Filtering**: Users can search cars by make, model, or year and filter the inventory based on various criteria.
- **Admin Panel**: Allows admin users to manage dealership and inventory records securely.

## Screenshots

![deployed_landingpage](https://github.com/user-attachments/assets/fae4c754-e0ee-4d2e-b4fa-e9cab7e5abad)
![about_us](https://github.com/user-attachments/assets/ffc0cbf5-309b-429e-a60b-f7a60e3cdb6c)
![car models](https://github.com/user-attachments/assets/1980f996-ebd7-4164-aa26-0f2a16fb280b)
![get_dealers_loggedin](https://github.com/user-attachments/assets/908691d4-cf90-485d-ac3b-cc08b6409069)
![capstone-dealership-architecture](https://github.com/user-attachments/assets/28312d45-f9fa-4590-8765-e7c6721a46d3)

## API Endpoints

The project exposes the following API endpoints for interacting with the dealership database:

- `GET /api/cars`: Retrieves the list of cars in the inventory.
- `POST /api/cars`: Adds a new car to the inventory.
- `PUT /api/cars/<id>`: Updates details of an existing car.
- `DELETE /api/cars/<id>`: Removes a car from the inventory.

## Future Enhancements

- **User Authentication**: Implement login functionality for users and admins.
- **Analytics Dashboard**: Add a dashboard to visualize sales and inventory data.
- **Unit Tests**: Add unit and integration tests for better code coverage.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
