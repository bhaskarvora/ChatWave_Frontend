
----------

Hii, I am **Bhaskar Vora** 
I am a self motivated and versatile individual, always eager to take on new challenges. With a passion for learning I am dedicated to delivering high-quality results. With a positive attitude and a growth mindset, I am ready to make a meaningful contribution and achieve great things.

# ChatWave Web Application

**ChatWave** is a modern chat application that enables real-time messaging between users. It offers features for user authentication, chat rooms, private messaging, and administrative controls for managing users and messages. This application provides a seamless user experience with modern design and real-time updates.

# Features

-   **User Authentication**: Secure login and registration with JWT-based authentication.
-   **Real-Time Chat**: Real-time messaging in both individual and group chats where we can attach images, audio, videos and any other files.
-   **User Management**: Admins can manage user accounts and chat history.
-   **Group Management**: Users can create and manage group chats.
-   **Message Management**: View, delete, and manage chat messages.
-   **Responsive Design**: Optimized for both desktop and mobile use.


### Server-Side Architecture Overview

#### 1. Environment Configuration (.env File)

-   Purpose: Contains sensitive configuration and credentials.
    
-   Contents:
    

-   MONGO_URI: MongoDB connection string.
    
-   JWT_SECRET: Secret key for JWT token signing.
    
-   ADMIN_SECRET_KEY: Key for admin-related operations.
    
-   NODE_ENV: Environment mode (e.g., DEVELOPMENT, PRODUCTION).
    
-   CLIENT_URL: URL for the frontend application.
    
-   CLOUDINARY_CLOUD_NAME, CLOUDINARY_API_KEY, CLOUDINARY_API_SECRET: Credentials for Cloudinary file uploads.
    

#### 2. Frontend  

-  Routing and Authentication:

App.jsx: The main application component that handles routing and lazy loading of pages. It includes authentication checks and socket provider setup.
ProtectRoute: A higher-order component that ensures users are authenticated before accessing certain routes.
State Management:

store.js: Configures the Redux store with slices for authentication, miscellaneous state, and chat management. It also integrates API middleware for async operations.
API Integration:

thunks/admin.js: Contains asynchronous thunk actions for admin login, fetching admin details, and logging out. It uses Axios for making HTTP requests.

    


## Install Dependencies

 `npm install` 
 `npm run dev` 




## Application Images

![Screenshot 2024-08-30 164057](https://github.com/user-attachments/assets/e0579ee0-2b24-4c8f-acdc-0b17095d5729)
ChatWave Realtime Chat Application

![Screenshot 2024-08-30 164128](https://github.com/user-attachments/assets/2281e172-a620-4c23-aee6-35e4f09895fe)
Messaging Example We can share any image, audio, video or files

![Screenshot 2024-08-30 164148](https://github.com/user-attachments/assets/648cf0d9-18f2-4ed7-a341-9b3d60beef0f)
Create New Group 

![Screenshot 2024-08-30 164444](https://github.com/user-attachments/assets/dd093ce7-d12c-412a-9114-8b64445e7dab)
Group Details

![Screenshot 2024-08-30 164520](https://github.com/user-attachments/assets/4680c606-73de-4643-b402-febb37d6b134)
Find People for Chat

![Screenshot 2024-08-30 165130](https://github.com/user-attachments/assets/50f26c76-6387-475a-9521-0a9c6705d557)
ChatWave Dashboard Showing Statistics using Line Chart

![Screenshot 2024-08-30 165158](https://github.com/user-attachments/assets/23260062-483e-4962-b6dd-1fe85854dbb0)
ChatWave Dashboard Showing Statistics of Last Messages

![Screenshot 2024-08-30 165212](https://github.com/user-attachments/assets/dcaf544c-6cf5-4818-9fd4-d1ebbd5d3f72)
ChatWave Dashboard Showing All Users











