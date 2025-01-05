# Blog Website - Ur Storiex XBlog

Welcome to **Ur Storiex XBlog**, a modern blog website where users can create, view, and manage blogs with ease. The platform offers features such as authentication, responsiveness, and interactive blog management. It’s built using React, Redux Toolkit, and a mock server with a `db.json` file for data storage.

## Features

- **Authentication**: 
  - Users can register and log in securely.
  - User authentication is handled via JWT (JSON Web Tokens).
  
- **Responsiveness**:
  - The website is fully responsive and works seamlessly across all devices, from desktop to mobile.

- **Create Your Blog**:
  - Users can create their own blogs and share their thoughts with others.
  
- **View Others’ Blogs**:
  - Users can explore and read blogs created by other members of the community.

- **Delete Your Blog**:
  - Users can delete their own blogs if needed.
  
- **Trending Topics**:
  - Check out the trending topics on the platform and explore the most discussed subjects.

- **Navigation**:
  - Move to the next page to view more blogs from other users.

## Tech Stack

- **Frontend**:
  - React
  - Redux Toolkit
  - HTML, CSS (Styled Components for styling)
  - React Router (for navigation)

- **Backend**:
  - JSON Server (for mock backend)
  - db.json (stores blog data)

## Getting Started

Follow the steps below to set up the project locally:

### Prerequisites

- Node.js and npm installed on your system.


### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kaushlesh79/ur_storiex_xblog.git
2. Navigate into the client directory:
   ```bash
     cd ur_storiex_xblog/client
3.Install dependencies for the frontend:
  ```bash
     npm install
 ```
4.Navigate into the server directory:
 ```bash 
     cd ../server
  ```
5.Install JSON Server:
  ```bash
   npm install json-server
```
6.Start the JSON Server:
```bash
   npx json-server --watch db.json --port 5000

  

   
