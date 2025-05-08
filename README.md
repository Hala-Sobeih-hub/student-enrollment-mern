# student-enrollment-mern

# 📚 Weekend School Enrollment System

This is a full-stack MERN application built for a weekend Arabic school to manage student registration, track tuition payments, and assign students to appropriate learning levels based on age and reading skills.

## 🌟 Features

### 🧑‍💼 Parent Dashboard
- Register up to 5 children in a single form
- Upload financial aid documents securely
- Enroll in optional after-school Arabic classes
- View tuition balance and make online payments
- Sign parental consent agreements

### 🛠️ Admin Dashboard
- Secure login for school admins
- View and manage all parent submissions
- Assign students to levels individually
- Track financial aid applications
- Monitor payment status per family
- Export reports for attendance or planning

### 💡 Additional Highlights
- Secure file uploads (e.g. tax return PDFs/images)
- Automated fee calculation based on number of children
- User authentication (JWT + bcrypt)
- Responsive and mobile-friendly interface

---

## 📷 Screenshots

> _Coming soon — add images or GIFs of the parent and admin dashboards here._

---

## 🧪 Tech Stack

| Layer      | Tech                        |
|------------|-----------------------------|
| Frontend   | React.js, Tailwind CSS      |
| Backend    | Node.js, Express.js         |
| Database   | MongoDB + Mongoose          |
| Auth       | JWT, bcrypt                 |
| File Upload| Cloudinary (or Multer/S3)   |
| Payments   | Stripe (optional, planned)  |

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/weekend-school-enrollment.git
cd student-enrollment-mern

### 2. Install dependencies
```bash
# Backend
cd server
npm install

# Frontend
cd ../client
npm install

### 3. Create .env files
Create .env files in the server/ directory with the following:

```bash
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

4. Run the app locally

```bash
# In one terminal
cd server
npm run dev

# In another terminal
cd client
npm run dev
Open http://localhost:5173 to view in the browser.

🛣️ Roadmap
 Stripe integration for online tuition payments

 Admin-level reports and filters

 Email notifications (confirmation, reminders)

 Arabic language support (i18n)

 Student attendance tracker

🧑‍💻 Author
[Your Name]
GitHub Profile | LinkedIn

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

yaml

---

Would you like me to generate a live version of this with your name and links filled in?
