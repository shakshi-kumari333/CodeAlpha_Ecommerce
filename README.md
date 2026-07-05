A simple full-stack E-commerce store b
Internship — Task 1**.


## ✨ Features
- User registration & login (JWT auth,
- Product listing with search
- Product details page
- Shopping cart (add / update / remove
- Order processing (checkout creates a
- Order history


## 🛠 Tech Stack
- **Frontend:** HTML, CSS, JavaScript 
- **Backend:** Node.js, Express.js
- **Database:** A lightweight JSON-fil
works instantly on any OS
- **Auth:** JWT stored in an HTTP-only


## 📁 Project Structure
```
CodeAlpha_Ecommerce/
├── backend/
│   ├── config/db.js          # JSON-f
│   ├── middleware/auth.js    # JWT au
│   ├── routes/                # auth,
│   ├── server.js              # Expre
│   ├── seed.js                # Seeds
│   └── package.json
└── frontend/
    ├── index.html              # Prod
    ├── product.html            # Prod
    ├── cart.html                # Sho
    ├── orders.html              # Ord
    ├── login.html / register.html
    ├── css/style.css
    └── js/api.js
```


## 🚀 How to Run


1. **Install dependencies**
   ```bash
   cd backend
   npm install
   ```


2. **Seed sample products**
   ```bash
   node seed.js
   ```


3. **Start the server**
   ```bash
   npm start
   ```


4. Open your browser at **http://local
   (The Express server serves the fron
needed.)


## 🔌 API Endpoints


| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/auth/register` | Regist
| POST | `/api/auth/login` | Login |
| POST | `/api/auth/logout` | Logout |
| GET | `/api/products` | List all pro
| GET | `/api/products/:id` | Get a si
| GET | `/api/cart` | View current use
| POST | `/api/cart` | Add item to car
| PUT | `/api/cart/:id` | Update cart 
| DELETE | `/api/cart/:id` | Remove it
| POST | `/api/orders` | Checkout (cre
| GET | `/api/orders` | View order his


## 📌 Notes
- Database file (`ecommerce.json`) is 
- This project fulfills CodeAlpha Task
order processing, and user registratio


---
Built as part of the **CodeAlpha Full 

