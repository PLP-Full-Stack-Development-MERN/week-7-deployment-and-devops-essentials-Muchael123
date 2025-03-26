
# **MERN Blog Platform**  

A simple blog platform where users can create, edit, and publish blog posts. The project focuses on deploying and maintaining a **MERN (MongoDB, Express, React, Node.js)** application using **DevOps** best practices.  

## **Features**  
✅ Create, edit, and delete blog posts  
✅ RESTful API with Express & MongoDB  
✅ Secure authentication with JWT  
✅ CI/CD pipeline with GitHub Actions  
✅ Backend deployed on **Render**  
✅ Frontend deployed on **Vercel**  
✅ Logging & monitoring with **Morgan, Winston, and Sentry**  

---

## **Installation**  

### **Backend Setup**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/mern-blog-platform.git
   cd mern-blog-platform/backend
   ```  
2. Install dependencies:  
   ```bash
   npm install
   ```  
3. Create a `.env` file and add:  
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```  
4. Start the server:  
   ```bash
   npm run dev
   ```  
   The backend should be running on `http://localhost:5000`.  

---

### **Frontend Setup**  
1. Navigate to the frontend directory:  
   ```bash
   cd ../frontend
   ```  
2. Install dependencies:  
   ```bash
   npm install
   ```  
3. Start the frontend:  
   ```bash
   npm start
   ```  
   The frontend should be running on `http://localhost:3000`.  

---

## **Deployment**  

### **Backend Deployment (Render)**  
1. Push your code to GitHub.  
2. Create a **Render Web Service**.  
3. Set **Build Command**: `npm install`  
4. Set **Start Command**: `node server.js`  
5. Add **Environment Variables** (`MONGO_URI`, `JWT_SECRET`).  
6. Click **Deploy**.  

### **Frontend Deployment (Vercel)**  
1. Push the frontend code to GitHub.  
2. Deploy it on **Vercel** by linking the repository.  
3. Set the **backend API URL** in the frontend `.env` file.  

---

## **CI/CD Pipeline**  
- Uses **GitHub Actions** to run tests on every push.  
- Prevents merging if tests fail.  
- Notifies contributors of build failures.  

---

## **Monitoring & Security**  
✔ **Morgan & Winston** for logging requests and errors.  
✔ **Sentry** for frontend error tracking.  
✔ **Environment variables** for sensitive credentials.  
✔ **HTTPS** enforced for secure communication.  

---

## **Contributing**  
1. Fork the repo.  
2. Create a new branch:  
   ```bash
   git checkout -b feature-branch
   ```  
3. Make changes and commit:  
   ```bash
   git commit -m "Added new feature"
   ```  
4. Push to GitHub and create a Pull Request.  

---

## **License**  
This project is open-source and available under the **MIT License**.  

---
