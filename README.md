# Instagram Profile UI Clone 📸

A modular and clean Flutter UI clone of the Instagram profile screen. This project demonstrates how to build a responsive, structured, and component-based user interface in Flutter, replicating the familiar layout of an Instagram profile page.

## Screenshots / Assets

<p align="center">
  <img src="instagram_pic/instagram_profile_pic.png" width="150" alt="Instagram Profile Pic" />
</p>

*Note: The asset above is located in the `instagram_pic/` directory and is used to simulate the profile image within the app.*

## Features

* **Authentic Profile Layout:** Recreates the standard Instagram profile view, including the header, bio, action buttons, and grid view for posts.
* **Component-Based Architecture:** The UI is broken down into modular, reusable widgets for easy maintenance and scalability.
* **Custom Navigation:** Includes a custom bottom app bar reflecting Instagram's standard navigation layout.

## Project Structure

The codebase is organized into dedicated directories for each UI component to keep the project clean:

* `lib/main.dart`: The main entry point of the Flutter application.
* `lib/Home/home.dart`: The primary scaffold and layout structure for the profile screen.
* `lib/Header/header.dart`: Contains the profile picture, post/follower/following counts, and bio section.
* `lib/Button/buttons.dart`: Implementation of the 'Edit Profile', 'Share Profile', and other interaction buttons.
* `lib/Main_Section/section.dart`: The tabbed view (Posts, Reels, Tagged) and the grid layout displaying user content.
* `lib/Botttom_AppBar/appbar.dart`: The bottom navigation bar UI.
* `lib/Images/images.dart`: Helper file for managing and loading grid images.

## Prerequisites

To run this project, ensure you have the following installed:
* [Flutter SDK](https://docs.flutter.dev/get-started/install)
* A supported IDE (e.g., VS Code, Android Studio)
* A connected physical device or a configured emulator/simulator

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/instagram_profile_clone.git](https://github.com/your-username/instagram_profile_clone.git)
