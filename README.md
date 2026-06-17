# CampusReclaim - Lost & Found System

CampusReclaim is a modern web-based Lost & Found platform designed for college campuses. It helps students and staff quickly report lost items, post found items, and reconnect owners with their belongings.

## Features

* 🔐 Google Authentication using Firebase Auth
* 📱 Responsive and mobile-friendly design
* 📸 Image upload with automatic compression
* 📋 Report Lost Items
* 🤝 Report Found Items
* 🔍 Search and filter functionality
* 📍 Location-based item reporting
* 📞 Contact information sharing
* ☁️ Real-time database updates with Firebase Firestore
* 🎨 Modern UI built with Tailwind CSS

## Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6 Modules)
* Tailwind CSS
* Font Awesome

### Backend & Database

* Firebase Authentication
* Firebase Firestore

## Project Structure

├── index.html
├── Firebase Configuration
├── Authentication Module
├── Lost & Found Item Management
├── Image Compression System
└── Search & Filter Features

## How It Works

1. User logs in using Google Authentication.
2. User selects:

   * "I Lost Something"
   * "I Found Something"
3. User fills in item details:

   * Item Name
   * Phone Number
   * Location
   * Category
   * Description
   * Image
4. Data is stored in Firebase Firestore.
5. Reports are displayed in real time for all users.
6. Owners and finders can connect using the provided contact information.

## Installation

1. Clone the repository:

git clone https://github.com/your-username/CampusReclaim.git

2. Open the project folder.

3. Configure Firebase:

   * Create a Firebase project.
   * Enable Google Authentication.
   * Enable Firestore Database.
   * Replace the Firebase configuration in the code with your own credentials.

4. Run the project:

Simply open `index.html` in your browser or host it using GitHub Pages.

## Future Enhancements

* Advanced search functionality
* Item matching using AI
* Email notifications
* Admin dashboard
* Chat system between users
* Claim verification process

## License

This project is open-source and available under the MIT License.

## Author

Developed by Deepu as a student-focused solution for managing lost and found items on campus.
