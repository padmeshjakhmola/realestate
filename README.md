# React Native Real Estate App

---

## Description

This project is a **full-stack real estate application** that I built from the ground up using React Native. It's designed to provide a comprehensive platform for browsing and managing properties, including robust features for user interaction and data presentation. My goal was to create a scalable and user-friendly application that demonstrates modern mobile development practices.

---

## Features

* **Secure User Authentication:** Implemented with Google authentication for seamless and secure sign-ins, ensuring user data privacy and integrity.
* **Dynamic Homepage:** Showcases the latest and recommended properties, complete with intuitive search and filtering capabilities to help users find what they're looking for efficiently.
* **Comprehensive Explore Page:** Allows users to browse all available property types and listings in a structured and organized manner.
* **Detailed Property Views:** Dedicated pages for in-depth information about individual properties, including images, descriptions, pricing, and key features.
* **Customizable Profile Page:** Users can manage their settings, update their personal information, and potentially view their saved properties or listings.

---

## Technologies Used

* **Expo SDK 52:** Utilized for a powerful and efficient development workflow, enabling rapid prototyping and deployment across various platforms.
* **TypeScript:** Employed throughout the codebase for enhanced code quality, ensuring type-safe, clean, and more maintainable code, which significantly reduces runtime errors.
* **Tailwind CSS:** Integrated for rapid and responsive UI development, allowing for highly customizable designs with a utility-first approach.
* **Backend: Appwrite:** Used appwrite for creating a simple database and backend solution.

---

## What I Learned & Implemented

Through the development of this application, I gained significant hands-on experience and honed my skills in:

* **Authentication and Authorization:** Building secure user flows, implementing robust authentication mechanisms, and managing access control.
* **Dynamic Routing:** Structuring seamless and efficient navigation within the application, ensuring a smooth user experience.
* **Custom Data Fetching:** Implementing a mini version of a data fetching library (inspired by concepts like Tanstack Query) for efficient data management, caching, and state synchronization.
* **State Management:** Mastering both local and global state management techniques to handle complex application logic and data flows effectively.
* **Database Architecture:** Designing scalable and efficient database structures tailored for a real estate application, ensuring optimal data retrieval and storage.
* **Clean Code Principles:** Adhering to best practices for writing reusable, type-safe, modular, and highly maintainable code.

---

## Getting Started

To get a copy of the project up and running on your local machine for development and testing purposes, follow these simple steps.

### Prerequisites

Before you begin, ensure you have the following installed on your system:

* **Node.js** (LTS version recommended)
* **npm** or **yarn** (Node.js comes with npm)
* **Expo CLI** (install globally if you haven't already):
    ```bash
    npm install -g expo-cli
    # or
    yarn global add expo-cli
    ```

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/padmeshjakhmola/realestate
    ```
2.  **Navigate into the project directory:**
    ```bash
    cd realestate
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```
4.  **Run the application:**
    ```bash
    npm start
    # or
    yarn start
    ```
    This command will open the Expo Developer Tools in your browser. From there, you can:
    * Scan the QR code with your phone using the Expo Go app.
    * run the app on an Android emulator or iOS simulator.
    * Run in your web browser.

### Configuration (if applicable)

* **Environment Variables:** If your project uses environment variables (e.g., for API keys, backend URLs), create a `.env` file in the root directory based on a `.env.example` (if provided) and fill in the necessary values.
    ```env
    EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_appwrite_project_id
    EXPO_PUBLIC_APPWRITE_ENDPOINT=your_appwrite_endpoint
    EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_appwrite_database_id
    EXPO_PUBLIC_APPWRITE_AGENTS_COLLECTION_ID=your_appwrite_agents_collection_id
    EXPO_PUBLIC_APPWRITE_GALLERIES_COLLECTION_ID=your_appwrite_galleries_collection_id
    EXPO_PUBLIC_APPWRITE_REVIEWS_COLLECTION_ID=your_appwrite_reviews_collection_id
    EXPO_PUBLIC_APPWRITE_PROPERTIES_COLLECTION_ID=your_appwrite_properties_collection_id
    ```
    *Replace the `your_...` placeholders with your actual Appwrite IDs.*
* **Database Setup:** (If your backend is local or requires specific setup instructions, provide them here.)

---

## Contributing

I welcome and appreciate contributions to this project! If you have suggestions for improvements, new features, or find any bugs, please feel free to:

1.  **Fork the repository.**
2.  **Create your feature branch:**
    ```bash
    git checkout -b feature/AmazingFeature
    ```
3.  **Commit your changes:**
    ```bash
    git commit -m 'Add some AmazingFeature'
    ```
4.  **Push to the branch:**
    ```bash
    git push origin feature/AmazingFeature
    ```
