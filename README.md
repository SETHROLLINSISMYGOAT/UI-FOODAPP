Food Delivery App UI

<img width="337" height="596" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/e4d38a78-14be-497f-b29f-e7422b311884" />
<img width="330" height="605" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/d1ad08bc-81d0-49fb-a6c6-22b9d48ff05a" />

This repository contains the UI implementation for a modern food delivery application, designed to provide a seamless and intuitive user experience. The layout is crafted to be visually appealing and responsive, showcasing common patterns found in food ordering applications.

Features
This UI demonstrates the following key elements and design principles:

Responsive Layouts: Built using ConstraintLayout to ensure adaptability across various screen sizes and orientations.

Image Carousel: A prominent image section with indicator dots for showcasing food items.

Floating Information Card: A detailed card overlapping the main image, displaying restaurant ratings, delivery information, and a description.

Category Chips: Horizontal scrollable chips for filtering or navigating between different food categories (e.g., Burger, Sandwich, Pizza).

Recommended Items List: A scrollable list of food items, each presented in a distinct card format with image, title, description, rating, and "Add to Cart" button.

Filter Chips: Horizontal scrollable filter options for refining the recommended items.

Item Details Screen: A dedicated screen for individual food items, featuring:

Detailed item information (title, subtitle, description).

Rating and delivery details.

Size selection chips (R, M, L).

A prominent "Add To Cart" button.

Bottom Navigation Bar: A sleek, rounded navigation bar at the bottom for quick access to different sections of the app (Home, History, Support, Profile).

Technologies Used
Android SDK

XML for layout definitions

androidx.constraintlayout.widget.ConstraintLayout for flexible and efficient UI positioning.

Setup Instructions
To get this project up and running on your local machine:

Prerequisites:

Android Studio installed.

Android SDK (API Level 21 or higher recommended).

Clone the Repository:

git clone https:https://github.com/SETHROLLINSISMYGOAT/UI-FOODAPP.git

Open in Android Studio:

Launch Android Studio.

Select File > Open... and navigate to the cloned project directory.

Sync Gradle:

Android Studio will automatically try to sync the Gradle project. If it doesn't, click File > Sync Project with Gradle Files.

Add Images:

This project uses placeholder images referenced as drawables. You will need to place your own image files named burger_main.jpg (or .png) and burger_item.jpg (or .png) into the app/src/main/res/drawable/ folder.

Run the Application:

Select an emulator or connect a physical Android device.

Click the Run button (green play icon) in the toolbar.

Project Structure & Resources
res/layout/activity_main.xml: Defines the main restaurant view.

res/layout/item_recommended.xml: Defines the reusable layout for individual recommended food items.

res/layout/activity_item_details.xml: Defines the layout for the item details screen.

res/values/colors.xml: Contains all custom color definitions used throughout the UI.

res/values/strings.xml: Contains all text strings used in the UI, enabling easy localization.

res/drawable/: Contains custom shape XML drawables (e.g., rounded_card_background.xml, chip_selected_background.xml) and vector assets for icons (e.g., ic_star.xml, ic_home.xml). All required drawable XMLs and vector asset definitions are provided in the project.

Future Enhancements
Implement click listeners for all interactive elements.

Integrate with a backend for dynamic data loading.

Add animations and transitions for a more fluid experience.

Implement quantity selection for items.

Add a search functionality.

License
This project is open-sourced under the MIT License. See the LICENSE file for more details.
