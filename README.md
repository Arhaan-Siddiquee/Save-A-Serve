
# Save-A-Serve

## Overview

Save-A-Serve is a humanitarian project aimed at reducing food wastage by creating an efficient delivery system for leftover food to poor and needy individuals. This initiative leverages technology to ensure that excess food from restaurants, events, and households reaches those in need in a timely manner.

## Features

- **User Registration**: Secure registration and login for users (donors and receivers).
- **Food Donation**: Easy food donation process for restaurants, event organizers, and households.
- **Real-Time Tracking**: Track the status of food delivery in real-time.
- **Matching Algorithm**: Intelligent matching of food donors and receivers based on location and food availability.
- **Notification System**: Automated notifications to donors and receivers about the status of their donations and deliveries.
- **Feedback System**: Allow receivers to provide feedback on the food received.
- **Admin Dashboard**: Manage and monitor the entire system efficiently.

## Technologies Used

- **Backend**: Java
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Framework**: Spring Boot (for Java backend)
- **API Integration**: Google Maps API (for location tracking)

## Installation

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- MySQL Server
- Apache Maven
- Node.js and npm (for frontend dependencies)

### Backend Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/Save-A-Serve.git
    ```

2. Navigate to the backend directory:
    ```sh
    cd Save-A-Serve/backend
    ```

3. Install the dependencies and build the project:
    ```sh
    mvn clean install
    ```

4. Setup the MySQL database:
    ```sh
    mysql -u root -p
    CREATE DATABASE saveaserve;
    ```

5. Update the `application.properties` file with your MySQL credentials:
    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/saveaserve
    spring.datasource.username=root
    spring.datasource.password=yourpassword
    ```

6. Run the Spring Boot application:
    ```sh
    mvn spring-boot:run
    ```

### Frontend Setup

1. Navigate to the frontend directory:
    ```sh
    cd ../frontend
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Start the development server:
    ```sh
    npm start
    ```

## Usage

1. **Registration**: Users can sign up as donors or receivers.
2. **Login**: Log in with registered credentials.
3. **Food Donation**: Donors can list excess food items for donation.
4. **Matching and Notification**: The system matches donors with nearby receivers and notifies both parties.
5. **Tracking and Feedback**: Track the delivery status and provide feedback.

## Contributing

We welcome contributions to Save-A-Serve! Please fork the repository and submit pull requests for any enhancements or bug fixes.


## Contact

For any questions or support, please contact us at siddiqueearhaan@gmail.com

---

Thank you for contributing to the Save-A-Serve initiative and helping us make a difference in the lives of many!

---
