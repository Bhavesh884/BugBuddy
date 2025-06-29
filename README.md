# **BugBuddy – Developer Networking App (MERN + Socket.io)**  
**Tinder-style platform for developers to connect, collaborate, and debug together in real-time!**  

[![Demo Video](https://img.shields.io/badge/Watch-Demo-red)](https://www.youtube.com/watch?v=6lzhTa7nFrI&ab_channel=bhaveshbhanusali)  
[![GitHub stars](https://img.shields.io/github/stars/bhavesh884/BugBuddy?style=social)](https://github.com/bhavesh884/BugBuddy)  

---

## **📌 Table of Contents**  
- [Features](#-features)  
- [Tech Stack](#-tech-stack)  
- [Installation](#-installation)  
- [Configuration](#-configuration)  
- [Screenshots](#-screenshots)  
- [Contributing](#-contributing)  

---

## **✨ Features**  
✅ **Swipe-to-Match Algorithm** – Connect with developers in <200ms response time.  
✅ **Real-time Chat** – Socket.io powered messaging with read receipts.  
✅ **OTP Verification** – Reduced fake accounts by 60%.  
✅ **Dockerized Backend** – Easy deployment on AWS EC2.  
✅ **Profile Validation** – GitHub/LinkedIn integration for credibility.  

---

## **🛠️ Tech Stack**  
**Frontend:**  
- React.js (Context API/Hooks)  
- Material-UI for UI components  
- Socket.io-client  

**Backend:**  
- Node.js + Express  
- MongoDB (user profiles, match history)  

**DevOps & Security:**  
- Docker for containerization  
- AWS EC2/S3 for hosting  
- JWT + bcrypt.js for authentication  

---

## **⚙️ Installation**  
1. **Clone the repo:**  
   ```bash
   git clone https://github.com/bhavesh884/BugBuddy.git
   cd BugBuddy
   ```

2. **Install dependencies:**  
   ```bash
   # Frontend
   npm install
   
   # Backend
   cd backend
   npm install
   ```

---

## **🔧 Configuration**  
**Backend (`.env`):**  
```env
PORT=5000
MONGODB_URL=<your_mongodb_uri>
JWT_SECRET=<your_secret_key>
SOCKET_IO_KEY=<optional_socket_key>
```  

**Frontend (`.env`):**  
```env
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_SOCKET_URL=http://localhost:5000
```

---

## **🚀 Running the App**  
1. **Start backend:**  
   ```bash
   cd backend
   npm start
   ```

2. **Start frontend:**  
   ```bash
   npm start
   ```
3. Open `http://localhost:3000` in your browser.  

---

## **📸 Screenshots**

### **Authentication & Profiles**
| Login | Sign Up | Profile Setup |
|-------|---------|--------------|
| <img src="https://github.com/user-attachments/assets/de5cccfa-cd4b-4a18-9436-1d56b6dcf5f7" width="300"> | <img src="https://github.com/user-attachments/assets/86971826-9e19-4de2-acde-b3459e81808" width="300"> | <img src="https://github.com/user-attachments/assets/234dee35-9a64-4795-9584-96afd42f6fcb" width="300"> |

### **Matching & Chat**
| Swipe Interface | Matches | Pending Requests |
|----------------|---------|-----------------|
| <img src="https://github.com/user-attachments/assets/8187428a-0fc0-435d-b1e4-4d249010623b" width="300"> | <img src="https://github.com/user-attachments/assets/78117253-cbd2-4938-9d35-94f7d5a8ab0d" width="300"> | <img src="https://github.com/user-attachments/assets/f96621fb-6dd6-4698-9d21-0e6ff4c1566c" width="300"> |

### **Real-Time Features**
| Chat Window | Video Call |
|------------|-----------|
| <img src="https://github.com/user-attachments/assets/940450ba-c637-4220-9758-6638a9ba2f76" width="300"> | <img src="https://github.com/user-attachments/assets/1764b70e-81b9-4493-b35d-0a90388b3528" width="300"> |


---

## **🤝 Contributing**  
1. Fork the repository.  
2. Create a branch (`git checkout -b feature/your-feature`).  
3. Commit changes (`git commit -m "Add feature"`).  
4. Push to the branch (`git push origin feature/your-feature`).  
5. Open a Pull Request.  

---

## **📜 License**  
MIT © [Bhavesh Bhanusali](https://github.com/bhavesh884)  

---

### **💬 Questions?**  
Reach out: **bhaveshbhanusalip884@gmail.com** | [LinkedIn](https://www.linkedin.com/in/bhavesh-bhanusali/)  

[![Back to Top](https://img.shields.io/badge/Back_to_Top-%E2%86%91-blue)](#bugbuddy--developer-networking-app-mern--socketio)  
