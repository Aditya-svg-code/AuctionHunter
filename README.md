# AuctionHunter

AuctionHunter is a full-stack online auctioning website built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js). This guide provides step-by-step instructions on how to install, clone, and set up the project on both **Windows** and **macOS**.

## Features
- User Authentication (Login & Signup)
- Create, Edit, and Delete Auctions
- Real-time Bidding System
- Secure Payment Integration (if applicable)
- User Dashboard

---

## Prerequisites
Ensure you have the following installed:
- **Node.js** (>= v16)
- **MongoDB** (Local or Cloud - e.g., MongoDB Atlas)
- **Git**

### Install Dependencies
Run the following command to install dependencies globally (optional):
```sh
npm install -g nodemon
```

---

## Installation & Setup

### Clone the Repository
Open your terminal or command prompt and run:
```sh
git clone https://github.com/Aditya-svg-code/AuctionHunter.git
cd AuctionHunter
```

### Install Backend Dependencies
```sh
cd backend
npm install
```

### Install Frontend Dependencies
```sh
cd ../frontend
npm install
```

### Setup Environment Variables
Create a `.env` file inside the `backend` folder and add the following (update values accordingly):
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Start the Backend Server
Run the backend server from the `backend` folder:
```sh
npm start
```

### Start the Frontend Server
Run the frontend server from the `frontend` folder:
```sh
npm start
```

The application should now be running at **http://localhost:3000**.

---

## OS-Specific Instructions

### Windows
1. Install **Node.js** and **MongoDB** from their official websites.
2. Open **Command Prompt** or **PowerShell** and follow the installation steps above.
3. Ensure MongoDB is running using:
   ```sh
   mongod
   ```

### macOS
1. Install **Homebrew** (if not installed) using:
   ```sh
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
2. Install **Node.js** and **MongoDB**:
   ```sh
   brew install node mongodb-community@6.0
   ```
3. Start MongoDB service:
   ```sh
   brew services start mongodb-community@6.0
   ```
4. Open **Terminal** and follow the installation steps above.

---

## Contributing
Feel free to fork the repository, create a new branch, and submit a pull request.

## License
This project is licensed under the **MIT License**.

---

### Need Help?
If you encounter any issues, feel free to open an issue in the repository or reach out!
