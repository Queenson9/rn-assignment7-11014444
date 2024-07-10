# DCIT202 Mobile Application Development - Assignment 7

## Project Overview

This project builds on the design from the previous assignment and incorporates new features and components as specified in the assignment brief. The goal is to develop a mobile application that displays products, allows users to view product details, and manage a shopping cart.

## Application Components

### HomeScreen

The HomeScreen is responsible for displaying a list of available products to the user. This screen is the main entry point of the application and provides an overview of the products fetched from an external API.

### ProductDetailScreen

The ProductDetailScreen shows detailed information about a selected product. When a user selects a product from the HomeScreen, they are navigated to this screen to view more information, including product descriptions, images, and prices.

### CheckoutScreen

The CartScreen displays the items that the user has selected to add to their cart. It provides a summary of the products chosen, allowing users to review their selections before proceeding to checkout.

### Drawer Component/Navigation Menu

The application includes a drawer component or navigation menu that can be accessed through a swipe gesture or a button. This component provides easy navigation between the different screens of the application, such as HomeScreen, ProductDetailScreen, and CartScreen.

### Add to Cart Button

Each product on the HomeScreen and ProductDetailScreen includes an “Add to Cart” button. This button allows users to add products to their shopping cart for future purchase.

### Remove from Cart Button

Each item in the CartScreen includes a “Remove from Cart” button. This functionality allows users to remove products from their cart if they change their mind or make an error in selection.

## Core Features

### Data Fetching

The application fetches data from an external API to populate the product list. This is done using the fetch API or axios library, ensuring that the application can retrieve up-to-date product information from the server.

### Asynchronous Operations

Asynchronous operations are managed using async/await or promises. This approach ensures that data fetching and other asynchronous tasks are handled efficiently, providing a smooth user experience without blocking the main thread.

### Product List Rendering

The application dynamically renders the product list based on the data fetched from the external API. Each product is displayed with relevant details such as name, price, and image, providing a comprehensive overview for users.

### Local Storage

Selected items are stored locally on the device using local storage solutions such as AsyncStorage, SecureStore, or FileSystem. This ensures that users can retain their cart items even if the application is closed or restarted.

### User Functionality

The application offers the following functionalities to users:

    -	View Available Products: Users can view a comprehensive list of available products fetched from an external API.
    -	Preview Product Details: Users can select a product to view detailed information about it, including descriptions, images, and prices.
    -	Add Products to Cart: Users can add products to their shopping cart using the “Add to Cart” button.
    -	Remove Products from Cart: Users can remove products from their cart using the “Remove from Cart” button.
    -	View Cart Items: Users can view the items they have added to their cart, providing a summary before proceeding to checkout.

### Setup Instructions

To set up and run the project, follow these steps:

    1.	Create Repository:
    2.	Clone Repository:
    3.	Commit Tasks Separately
    4.	Access UI Design: Access the UI design to guide your implementation.
    5.	Download Resources
    6.	Include Screenshots: As you develop the application, take screenshots of the app demonstrating the required  functionalities and include them in your repository.

### Project Structure

The project is organized into the following structure:

- assets
- src
  - screens
  - HomeScreen.js
  - ProductDetailScreen.js
  - CheckoutScreen.js
- App.js
- package.json
- README.md

## Design Choices

### User Interface Design

The UI design is based on the provided [mockup](UI mockup). It ensures a user-friendly and intuitive interface, making it easy for users to navigate through the application and interact with the various components. The navigation is handled using a drawer component, allowing users to access different screens quickly and efficiently.

### Data Fetching Mechanism

Data fetching is implemented using the fetch API due to its simplicity and wide browser support. Alternatively, the axios library can be used for more advanced features and better error handling. Asynchronous operations are handled with async/await, providing a clean and readable code structure for managing data flow and ensuring a seamless user experience.

### Local Storage Implementation

Local storage is implemented using AsyncStorage, which is a simple and efficient way to store key-value pairs locally on the device. This allows the application to persist user data, such as the items in their cart, even if the app is closed or restarted. For enhanced security and performance, SecureStore or FileSystem can also be used.

## Screenshots

<img src="https://i.ibb.co/KWQLZKY/Screenshot-20240709-174604.jpg" width="400px"/>
<img src="https://i.ibb.co/58J3vKJ/Screenshot-20240709-174615.jpg" width="400px"/>
<img src="https://i.ibb.co/bLJdKfY/Screenshot-20240709-174628.jpg" width="400px"/>
<img src="https://i.ibb.co/qsz93vv/Screenshot-20240709-174649.jpg" width="400px"/>
