# **Student Attendance Management System**  

A web application built with the MERN stack (MongoDB, Express.js, React, Node.js) and Redux, designed to simplify the management of student records and attendance for educational institutions. This system provides secure authentication, comprehensive student and attendance management, and admin-controlled operations.  

---

## **Features**  
- **Authentication & Authorization**  
  - User registration and login functionality with secure authentication.  
  - Admin-restricted access to sensitive operations.  

- **Student Management**  
  - Add, update, and delete student details.  
  - Update student whereabouts for better tracking.  

- **Attendance Tracking**  
  - Record daily attendance efficiently.  
  - Display detailed attendance records.  
  - Export attendance data as CSV files for offline use.  
  - Delete attendance records from previous days.  

- **Admin Controls**  
  - Manage the user list and toggle admin privileges.  
  - Centralized control over data operations, accessible only to administrators.  

---

## **Technologies Used**  
- **Frontend:** React, Redux  
- **Backend:** Express.js, Node.js  
- **Database:** MongoDB  
- **State Management:** Redux  
- **Other Tools:**  
  - CSV Export for attendance records  
  - Role-based access control  

---

## **Installation**  

### **Prerequisites**  
- Node.js and npm installed  
- MongoDB instance running locally or in the cloud  

### **Steps**  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/rajafawadt/attendance-mgmt-mern.git
   cd attendance-mgmt-mern
   ```

2. **Install dependencies**  
   - Backend:  
     ```bash
     npm install
     ```
   - Frontend:  
     ```bash
     cd frontend
     npm install
     ```

3. **Environment Variables**  
   - Create a `.env` file in the `root` folder with the following variables:  
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_key
     PORT=5000
     ```

4. **Run the Application**  
   - Start the backend server(at root):  
     ```bash
     npm start
     ```
   - Start the frontend server:  
     ```bash
     cd frontend
     npm run dev
     ```
   - The application will be accessible at `http://localhost:3000`.

---

## **Usage**  
1. **Register and log in as an admin or user.**  
2. **Admins can:**  
   - Add, edit, and delete student details.  
   - Manage user roles and attendance records.  
3. **Users can:**  
   - View student and attendance records.  

---


## **Contributing**  
Contributions are welcome! To contribute:  
1. Fork this repository.  
2. Create a new branch:  
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:  
   ```bash
   git commit -m "Add your message"
   ```
4. Push to the branch:  
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.  

---

## **License**  
This project is licensed under the MIT License. See the `LICENSE` file for details.  

---

## **Contact**  
- **Author:** Raja Fawad  
- **Email:** [rajafawady@gmail.com](mailto:rajafawady@gmail.com)  
- **GitHub:** [github.com/rajafawady](https://github.com/rajafawady)  
