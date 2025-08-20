# 💊 Prescripto

Prescripto is a web-based platform designed to simplify appointment booking with doctors. It provides users with a seamless way to browse available doctors, schedule appointments, and manage their bookings online.

🔗 **Live Demo:** [Prescripto](https://prescripto-pied.vercel.app/)  
📂 **GitHub Repo:** [Prescripto Repository](https://github.com/CharchitAgarwal549/Prescripto)

---

## 🛠 Tech Stack
- **Frontend:** React.js, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Other Tools:** Axios, JWT Authentication, Vercel (Deployment)

---

## ⚡ Features
- User-friendly interface to browse and book doctors.  
- Secure **authentication & authorization** using JWT.  
- Manage appointments with a simple dashboard.  
- Responsive UI for mobile and desktop.  
- Integration with MongoDB for storing users, doctors, and appointment details.  

---

## 📂 Project Structure
```

Prescripto/
│-- client/         # React frontend
│-- server/         # Node.js + Express backend
│-- models/         # MongoDB schemas
│-- routes/         # API routes
│-- controllers/    # Business logic for routes

````

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/CharchitAgarwal549/Prescripto.git
cd Prescripto
````

### 2. Setup Backend

```bash
cd backend
npm install
node server.js
```

### 3. Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

### 4. Environment Variables

Create a `.env` file inside the `backend/` folder:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=4000

# Payment gateways
STRIPE_SECRET_KEY=your_stripe_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_secret

# Cloud storage
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

```

---

## 🎯 Future Improvements

* Add **doctor availability calendars**.
* Implement **online payment integration**.
* Add **email/SMS notifications** for appointments.
* Role-based dashboards (patients, doctors, admins).

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

---

### 👨‍💻 Author

**Charchit Agarwal**
🔗 [GitHub](https://github.com/CharchitAgarwal549)
🔗 [LinkedIn](https://www.linkedin.com/in/charchit-agarwal-/)

```
