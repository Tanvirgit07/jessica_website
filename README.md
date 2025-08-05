# Lawbie 🛒

A modern, feature-rich eCommerce web app tailored for UK and Canada users, offering authentication, geo-based experience toggle, product search/filter, Stripe payments, wishlist, and cart functionality.

---

## 🚀 Live Demo

🌐 [https://lawbie-demo.vercel.app](https://lawbie-demo.vercel.app) *(Add your live demo link here)*

---

## 📸 Screenshots

*(Add screenshots here)*

---

## 🌟 Features

- **User Authentication:** Secure login and registration using JWT
- **Region Toggle:** Switch between UK and Canada bases; UK button changes experience accordingly
- **Product Search & Filter:** Search products by name, filter by category, price, availability
- **Cart & Wishlist:** Add/remove products to cart and wishlist, with quantity management
- **Stripe Payment:** Secure payment processing via Stripe integration
- **Responsive Design:** Mobile-friendly UI for smooth user experience

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS, React Router
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Token)
- **Payment Gateway:** Stripe
- **Deployment:** Vercel (Frontend), Heroku/Render (Backend)

---

## 🔧 Installation & Setup

1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/lawbie.git
   cd lawbie
Install dependencies:

bash
Copy
Edit
npm install
Create .env file in the root folder and add:

env
Copy
Edit
VITE_API_URL=http://localhost:5000
VITE_JWT_SECRET=your_jwt_secret
VITE_STRIPE_PK=your_stripe_public_key
Run the app locally:

bash
Copy
Edit
npm run dev
🔍 Search & Filter
Search products by keywords

Filter by category, price range, and availability

Real-time results updating

💳 Stripe Payment Integration
Secure payment processing

Real-time transaction feedback

Supports card payments via Stripe

❤️ Wishlist & Cart
Add/remove items from wishlist

Manage shopping cart with quantity update and removal

Persistent state with localStorage/session

🔐 Authentication & Authorization
JWT-based user authentication

Protected routes for logged-in users

Role-based access control (optional for Admin features)

🗂️ Folder Structure (Client)
css
Copy
Edit
src/
├── components/
├── context/
├── hooks/
├── pages/
├── services/
├── utils/
├── App.jsx
└── main.jsx
🛣️ Roadmap
 User Authentication

 Region toggle (UK / Canada)

 Product search & filter

 Stripe payment integration

 Wishlist and cart functionality

 Admin Dashboard

 Email notifications

 Order tracking system

🤝 Contribution
Contributions are welcome! Please open an issue or submit a pull request.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

👤 Author
Tanvir Ahmmed
GitHub | Email
