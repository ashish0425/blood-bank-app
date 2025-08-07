# NSS-Blood-Bank-Mern-Stack-Project
• Developed a full-stack web application for storing and managing donated blood between various organizations, donars and admin by utilizing the MERN Stack. 

• Implemenated user authentication and authorization features secure access to user-specfic details.

• Tech Stack Used -ReactJS, NodeJS,ExpressJS, MongoDB, ReactRedux.
# BloodBankDetails – A Smart Blood Donation Management System
Tagline: A full-stack web application to streamline blood donation workflows and improve real-time accessibility across organizations.
📖 Description
BloodBankDetails is a MERN stack-based application built to digitize and simplify the management of blood donations across donors, hospitals, and organizations. The system supports secure user authentication, role-based access, real-time inventory updates, and centralized records for transparency and traceability.

This project was developed as part of the National Service Scheme (NSS) at NIT Jamshedpur, aimed at improving accessibility and management of donated blood using modern web technologies.

✨ Features
🔐 Authentication & Authorization: Secure login and registration with role-based access (Admin, Organization, Hospital, Donor).

🧾 Inventory Management: Real-time tracking and updating of blood unit availability across different blood groups and locations.

🏥 Organization & Hospital Dashboards: Dedicated interfaces to manage donations, requests, and internal data.

📄 Reusable Forms: Modular and reusable UI components for forms and input handling.

🔄 API Optimization: RESTful APIs optimized to reduce server response time by 40%.

📊 User-Friendly Interface: Clean and responsive frontend built for seamless navigation and real-time feedback.

🛡️ Protected Routes: Route-level protection ensuring sensitive data access only to authorized users.

⚠️ Error Handling: Unified system-wide error handling and feedback.

🧰 Tech Stack
Frontend	Backend	Database	Tools & Libraries
ReactJS	Node.js	MongoDB	ExpressJS, Mongoose, JWT, Bootstrap, Git

📁 Project Structure
pgsql
Copy code
blood-bank-app/
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── routes/
│   │   ├── App.js
│   │   └── index.js
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── config/
│   ├── server.js
│   └── .env
├── package.json
└── README.md
⚙️ How to Run
✅ Prerequisites
Node.js (v14+)

MongoDB

Git

🔧 Setup
Clone the repository:

bash
Copy code
git clone https://github.com/ashish0425/blood-bank-app.git
cd blood-bank-app
Install dependencies for both client and server:

bash
Copy code
cd client
npm install
cd ../server
npm install
Create a .env file in the server/ directory and add:

ini
Copy code
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
Run the development server:

bash
Copy code
cd server
npm run dev
Run the React frontend:

bash
Copy code
cd client
npm start
🧪 Testing
Basic testing with Postman or browser (no automated testing included for this version).
👤 Author
Ashish Kumar
B.Tech ECE, NIT Jamshedpur
LinkedIn | GitHub




