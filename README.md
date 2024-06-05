# Food Delivery App

## Overview
This is a simple food delivery application interface designed using HTML and CSS. The application is structured to provide users with a seamless experience in browsing restaurants, viewing categories, and managing their orders.

## Features
- **Responsive Design**: Optimized for various device sizes with a focus on usability.
- **Restaurant Listings**: Displays a list of top restaurants with images and ratings.
- **Search Functionality**: Allows users to search for restaurants or food items.
- **Order Management**: Users can view their current order details and checkout.
- **Category Browsing**: Users can browse different food categories.

## Technologies Used
- **HTML5**
- **CSS3**
- **Google Fonts (Roboto)**

## Getting Started

### Prerequisites
To run this application, you need a web browser. No additional software is required.

### Installation
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/food-delivery-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd food-delivery-app
   ```

### Running the Application
Open the `index.html` file in your preferred web browser:
```bash
open index.html
```

## Project Structure
The project consists of a single HTML file and embedded CSS styles.

### HTML Structure (`index.html`)
- **Dashboard**: The main container for the application.
  - **Restaurant Panel**: Contains navigation, welcome banner, categories, and restaurant listings.
    - **Nav Bar**: Provides a menu, title, and search bar.
    - **Welcome Banner**: A welcoming section with an introductory message.
    - **Categories**: Lists different food categories.
    - **Restaurant List**: Displays available restaurants with images and ratings.
  - **Order Panel**: Manages user order details and checkout process.
    - **User Info**: Shows user-related information like the number of items in the cart.
    - **Order Details**: Displays the current order with options to edit and checkout.

### CSS Structure (`styles.css`)
- **General Styles**: Includes resets, body styling, and font imports.
- **Root Variables**: Defines color variables for consistent theming.
- **Dashboard and Panels**: Styles for the main container and its child elements.
- **Nav Bar**: Styles for the navigation bar elements.
- **Welcome Banner**: Styling for the welcoming message and its elements.
- **Categories**: Styles for the category list and its items.
- **Restaurant List**: Grid layout and styles for restaurant items.
- **Order Panel**: Styles for the order summary, including user info and order details.

## Customization
You can customize the application by modifying the HTML and CSS files according to your needs. For example:
- **Changing Colors**: Modify the CSS variables in the `:root` selector.
- **Adding Categories**: Add more `<li>` elements in the `.category-list` section.
- **Adding Restaurants**: Add more `<li>` elements in the `.restaurant-list` section with appropriate details.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contributing
Feel free to fork this project, submit issues, or send pull requests. Contributions are welcome!


