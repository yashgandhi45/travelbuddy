# TravelBuddy: Travel Social Media App

**TravelBuddy** is a simple social media platform for travel enthusiasts. Connect with other travelers, share your experiences, and discover new destinations.

---

## Features

- **Connect with Travelers**: Interact with fellow travelers.
- **Share Posts**: Share photos from your travels.
- **Explore Destinations**: Discover popular and hidden travel spots.
- **Profile Pictures**: Upload a profile picture to personalize your account.

---

## Built With

- **Frontend**: React
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Hosting**: Vercel (Frontend), MongoDB Atlas (Backend)

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yashgandhi45/travelbuddy.git
cd travelbuddy
```

### 2. Backend Setup

1. **Install Dependencies**:
   Navigate to the `server` directory and install the required packages:
   ```bash
   cd server
   npm install
   ```

2. **Set Up MongoDB**:
   - Create a MongoDB account and set up a cluster.
   - In the `server` directory, create a `.env` file and add the following environment variables:
     ```bash
     PORT = 3001
     MONGO_URL = <your-mongo-url>
     JWT_SECRET = <your-jwt-secret>
     ```

3. **Start the Server**:
   ```bash
   npm run start
   ```

   The backend will be running on `http://localhost:3001`.

---

### 3. Frontend Setup

1. **Install Dependencies**:
   Navigate to the `client` directory and install the required packages:
   ```bash
   cd client
   npm install
   ```

2. **Start the Frontend**:
   ```bash
   npm run start
   ```

   The frontend will be running on `http://localhost:3000`.

---

## Usage

- Open `http://localhost:3000` in your browser to access the app.
- Sign up or log in to start connecting with other travelers and share your adventures!

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
