# ShopVibe E-commerce Platform

ShopVibe is a modern, responsive e-commerce web application built with a vanilla JavaScript frontend and a Node.js/Express backend. It features a dynamic home page, product search with filtering, shopping cart management, and wishlist functionality.

## 🚀 Features

### Frontend
- **Home Page**: 
  - Dynamic hero slider (configurable via API).
  - "Shop by Category" section.
  - "Latest Products" grid with hover effects.
  - Service features highlights.
  - Responsive navigation bar with scroll effects.
- **Product Search & Discovery**:
  - Real-time search functionality.
  - Filters for Category, Price Range, and Rating.
  - Sorting options (Price, Rating, Newest).
  - Toggle between Grid and List views.
- **User Interaction**:
  - **Quick View**: Modal popup to view product details without leaving the page.
  - **Cart**: Add to cart functionality with visual feedback (animations).
  - **Wishlist**: Toggle items in and out of a wishlist.
  - Toast notifications for user actions.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop screens.

### Backend
- **RESTful API**: Built with Express.js.
- **Endpoints**:
  - Product management (fetch all, search, get by ID).
  - Category listing.
  - Cart and Wishlist management (currently in-memory storage).
  - Configuration endpoints (e.g., slider images).
- **Static File Serving**: Serves frontend assets directly.

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3 (Custom animations, Flexbox/Grid), JavaScript (ES6+).
- **Backend**: Node.js, Express.js.
- **Data**: In-memory data structures (Mock database using JavaScript arrays).

## ⚡ Installation & Setup

1.  **Prerequisites**: Ensure you have [Node.js](https://nodejs.org/) installed on your machine.

2.  **Clone/Download the repository**.

3.  **Install Backend Dependencies**:
    Navigate to the backend directory and install the required packages.
    ```bash
    cd backend
    npm install
    ```

4.  **Start the Server**:
    ```bash
    npm start
    # OR
    node server.js
    ```

5.  **Access the Application**:
    Open your browser and navigate to:
    `http://localhost:3000`
