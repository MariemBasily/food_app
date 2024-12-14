# Food App

## Overview
The **Food App** is a Flutter application that provides a clean and interactive user interface for browsing and purchasing food items. The app includes a detailed product page with navigation, item quantity adjustment, and a summary of the total price. The immersive design and functionality create a seamless user experience.

## Features
- **Immersive UI:** The app uses the `SystemUiMode.immersiveSticky` mode for a distraction-free experience.
- **Navigation:** Users can navigate between the home page and individual item pages using predefined routes.
- **Product Page:**
  - Displays detailed information about the selected item, including an image, description, and price.
  - Allows users to adjust the quantity of the selected item.
- **Cart Summary:**
  - Displays the total price of the items.
  - Includes a "Buy Now" button with a visually appealing design.
- **Custom Components:** Custom widgets like `SingleItemNavBar` ensure code reusability and consistency in design.

## Screenshots

![image](https://github.com/user-attachments/assets/0fc1e8e0-f113-408a-ba3d-60bee4d94ff6)

![image](https://github.com/user-attachments/assets/c4fd064e-6261-425b-891d-b2479230bb6e)



## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/MariemBasily/food_app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd food_app
   ```
3. Install dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

## File Structure
The project follows a well-organized structure:
```
food_app/
├── lib/
│   ├── main.dart               # Main entry point of the app
│   ├── pages/
│   │   ├── home_page.dart      # Home page of the app
│   │   ├── single_item_page.dart # Detailed product page
│   └── widgets/
│       └── single_item_nav_bar.dart # Custom navigation bar for the product page
└── assets/
    └── images/
        └── bg.png              # Background image for the product page
```

## Dependencies
The app uses the following Flutter dependencies:
- `flutter/material.dart`: For UI components and material design elements.
- `flutter/cupertino.dart`: For iOS-styled icons and widgets.

## How to Use
1. Launch the app.
2. Browse the home page to explore food items.
3. Select an item to view its details.
4. Adjust the quantity and click on "Buy Now" to proceed with the purchase.

## Future Enhancements
- Add a dynamic home page with a list of food items.
- Implement a cart system to allow users to add multiple items.
- Integrate payment gateway APIs for real transactions.
- Add backend support to fetch food data dynamically.

## Author
Developed by **Mariem Basily**.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request to improve the app.
