## Cloud Wholesale Marketplace
This repository contains the codebase for the Cloud Wholesale Marketplace, an innovative platform designed to connect wholesalers with buyers. The marketplace enables wholesalers to list their products, manage orders, and interact with customers seamlessly. Buyers can browse through a variety of products, place orders, and track their purchases with ease. The platform leverages modern web technologies to ensure a responsive and efficient user experience.

## Project URL
Whole seller Market Place

## Technologies Used

**Backend**
- **Node.js:** Handles the business logic, authentication, and communication with the frontend and database.

**Frontend**
- **React.js**: Provides a dynamic and responsive user interface for interacting with the marketplace.

**Storage**
- **Image Kit:** Used for storing and managing product images and documents.
- **Cloudinary**: Utilized for storing static images.

**Data Storage**
- **AWS S3:** Used for storing various types of data securely.

**Data Visualization**

- **Chart.js**: Integrated for visualizing data and presenting insights on user interactions and other metrics.

**Compute**
- **AWS EC2 T3 Micro**: The platform is hosted on this instance, ensuring reliable compute resources.

**Database**

- **MongoDB**: Serves as the primary database for storing application data.

**Analytics**
- **MS Clarity**: Used for analyzing user behavior to improve the user experience.

## Architecture Overview

**User Interaction**
  1. Users interact with the React.js Frontend to browse products, place orders, and track purchases.

**Backend Communication**

  2. The React.js Frontend communicates with the Node.js Backend to handle user requests and application logic.

**Data Storage**

  3. The Node.js Backend determines where to store data and utilizes AWS S3 for general data storage.
  4. Product images and documents are stored using Image Kit, while static images are managed with Cloudinary.

**Database**

  5. The Node.js Backend interacts with MongoDB to perform CRUD operations on the database.

**Compute Resources**

  6. The entire platform is hosted on an AWS EC2 T3 Micro instance, providing scalable compute resources.
  
**Data Visualization and Analytics**

  7. Data visualization is handled by Chart.js, which is used to present user interaction data and other insights.
  8. User behavior is analyzed using MS Clarity to continually improve the platform's user experience.

## Diagram

<img width="2846" alt="350740515-ff8d84c0-2934-4414-b7b9-3b925fda2cc7" src="https://github.com/user-attachments/assets/fa91aabd-5a84-486d-88bf-f00359478269">

## Getting Started
Follow the instructions below to set up and run the project locally.

### Prerequisites

- Nodejs
- npm
- MongoDB
- AWS Account for S3 Bucket and EC2
- Image Kit and Cloudinary accounts

### Installation

1. Clone the repository

   ```
   git clone https://github.com/AnmolSaigal7/cloud-wholesaleMarketplace.git
3. Navigate to the project directory

   ```
   cd cloud-wholesale-marketplace
5. Install backend dependencies

   ```
   cd backend
   npm install
6. Install frontend dependencies

   ```
   cd ../frontend
   npm install
### Running the Application

1. Start the backend server

   ```
   cd backend
   npm start
2. Start frontend server (client)

   ```
   cd ../frontend
   npm start

### Deployment

Refer to the AWS documentation to deploy the backend to an EC2 instance and configure S3 for data storage. Follow the Image Kit and Cloudinary documentation for integrating image storage solutions.