# Geo-Fencing Attendance Manager

A location-based attendance system that verifies user presence within a 10-meter radius before allowing attendance marking.  
Built to ensure genuine, location-verified attendance for institutions using geo-fencing and role-based access control.

---

## 🚀 Features

- Geo-fenced attendance verification (10-meter radius)
- Role-based login: Students, Teachers, and Admins
- Venue selection using dropdown
- Manual student ID entry for flexibility
- Secure authentication using JWT
- Attendance report export as PDF
- Progressive Web App (PWA) support
- Clean and responsive UI with Tailwind CSS

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- Recoil (State Management)
- React Router

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- Cookie-based session handling

### Utilities & Tools
- jsPDF for attendance report generation
- Vite PWA plugin
- ESLint

---

## 📂 Project Structure

```

frontend/
backend/

````

- `frontend` → React + Vite application
- `backend` → Express server and MongoDB integration

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/kushkumar569/geofencing-attendance-manager.git
cd geofencing-attendance-manager
````

### 2. Install dependencies

Install for both frontend and backend:

```bash
npm install
```

### 3. Setup environment variables

Create a `.env` file inside the `backend` folder:

```
MONGO_URL=
JWT_SECRET=
FRONTEND_URL=
BACKEND_URL=
PORT=
```

### 4. Run the backend server

```bash
npm start
```

### 5. Run the frontend

In another terminal:

```bash
npm run dev
```

---

## 🧠 Key Implementations

* Geo-location validation before attendance marking
* Role-based access control for students, teachers, and admins
* Secure JWT authentication with cookies
* PDF generation for attendance reports
* PWA-enabled frontend for app-like experience

---

## 📌 Future Enhancements

* Live map view of attendance location
* Admin dashboard with analytics
* Cloud deployment with GPS accuracy optimization

---

## 👤 Author

**Kush Kumar**

* GitHub: [https://github.com/kushkumar569](https://github.com/kushkumar569)
* LinkedIn: [https://www.linkedin.com/in/kush-kumar-876525257/](https://www.linkedin.com/in/kush-kumar-876525257/)

