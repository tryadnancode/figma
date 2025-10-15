# Figma Restaurant App

This is a Flutter-based mobile application for browsing and reserving restaurants.

## Approach

The application is built using the Flutter framework, allowing for a cross-platform codebase that can be deployed on both Android and iOS devices. The user interface is designed to be simple and intuitive, focusing on a clean presentation of restaurant information.

## Key Decisions

*   **Framework:** Flutter was chosen for its rapid development capabilities and the ability to create a visually consistent UI across different platforms.
*   **UI/UX:** The design prioritizes ease of use, with a straightforward navigation flow. Key information, such as restaurant location, ratings, and images, is prominently displayed.
*   **State Management:** A simple state management approach using `StatefulWidget` and `setState` is employed for managing the UI state. For a larger and more complex application, a more robust solution like Provider or BLoC would be recommended.

## Limitations

*   **Incomplete Features:** The "Reservation" and "Favorites" functionalities in the bottom navigation bar are currently placeholders and do not have full functionality. They display a "coming soon" message when tapped.
*   **Static Data:** The restaurant data is currently hardcoded within the `home_screen.dart` file. In a production environment, this data would be fetched from a backend API.
*   **No User Authentication:** While there are UI elements that suggest user accounts (e.g., the profile card), there is no actual user authentication system implemented. The user email is passed between screens but not validated.
*   **Limited Error Handling:** The application has minimal error handling. For instance, it doesn't handle cases where images fail to load or network requests (if any were implemented) fail.
