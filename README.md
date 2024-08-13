# Picerate - A Social Media Application

Picerate is a social media platform developed primarily with TypeScript, leveraging Appwrite for backend functionality.

## Getting Started

To run this application, you'll need to set up an Appwrite account and replace the existing API keys with your own. Follow these steps to get started:

1. **Clone the Repository**  
   ```bash
   git clone <repository_url>
   ```

2. **Install Dependencies**  
   Navigate to the project directory and install the required dependencies:
   ```bash
   npm install
   ```

3. **Set Up Appwrite Credentials**  
   Create a `.env` file in the root directory and add your Appwrite credentials:
   ```plaintext
   VITE_APPWRITE_URL=
   VITE_APPWRITE_PROJECT_ID=
   VITE_APPWRITE_DATABASE_ID=
   VITE_APPWRITE_STORAGE_ID=
   VITE_APPWRITE_USER_COLLECTION_ID=
   VITE_APPWRITE_POST_COLLECTION_ID=
   VITE_APPWRITE_SAVES_COLLECTION_ID=
   ```

4. **Run the Application**  
   Start the development server:
   ```bash
   npm run dev
   ```

## Features

- **Authentication System**  
  A secure and reliable authentication system to protect user data and privacy.

- **Explore Page**  
  A dynamic homepage where users can discover posts, featuring a section for top creators.

- **Like and Save Functionality**  
  Users can like and save posts, with dedicated sections for managing liked and saved content.

- **Detailed Post View**  
  A comprehensive post page displaying content alongside related posts for an enhanced user experience.

- **Profile Page**  
  A personalized user profile page showing liked posts with options to edit the profile.

- **User Browsing**  
  Explore and interact with other users' profiles and posts.

- **Post Creation**  
  A user-friendly interface for creating posts, including seamless file management, storage, and a drag-and-drop feature.

- **Post Editing**  
  Allows users to edit their posts at any time.

- **Responsive UI with Bottom Navigation**  
  A responsive user interface with a bottom navigation bar, providing a mobile app-like experience.

- **React Query Integration**  
  Utilizes React Query (Tanstack Query) for:
  - Auto-caching to boost performance
  - Parallel queries for efficient data retrieval
  - First-class mutations

- **Backend as a Service (BaaS) - Appwrite**  
  Employs Appwrite as a Backend as a Service, streamlining backend development with features like authentication, database management, file storage, and more.

## Enjoy the App!

Once you've completed the setup, you can start using the app and exploring its features.
