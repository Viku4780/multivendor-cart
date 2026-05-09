# 🛒 MultiVendor Cart

A full-featured Multi-Vendor E-commerce Cart System that allows multiple sellers to list products and customers to browse, add to cart, and place orders seamlessly.

This project demonstrates how a marketplace like Amazon or Flipkart works under the hood, where multiple vendors manage their own products while users shop from a unified platform.

---

## 🚀 Features
* 👤 User Authentication
  * Register / Login functionality
  * Secure session handling
* 🏪 Multi-Vendor System
  * Multiple sellers can add and manage products
  * Vendor-specific product listings
* 🛍️ Product Management
  * Add, update, delete products
  * Categorization support
* 🛒 Shopping Cart
  * Add to cart functionality
  * Update quantity / remove items
  * Persistent cart behavior
* 📦 Order Management
  * Place orders
  * Track orders (basic)
* 🔐 Admin Control
  * Manage users/vendors
  * Moderate vendors/products


## 🧠 Concept Behind This Project

Multi-vendor platforms are more complex than single-store e-commerce because:

* Each vendor manages their own inventory
* The platform handles:
  * commissions
  * order distribution
  * unified checkout

This project is a simplified implementation of that architecture.


## 🛠️ Tech Stack

(Update this based on your actual repo stack if needed)

* Frontend: Next.js , Redux-Toolkit, Axios and TypeScript
* Backend: Node.js / Express , NextAuth, Cloudinary and Nodemailer
* Database: MongoDB(mongoose)
* Payment Integration: Stripe


## Installation & Setup

### 1. Clone the repository

```Bash
git clone https://github.com/Viku4780/multivendor-cart.git
cd multivendor-cart
```

### 2. Install dependencies

```Bash
npm install
```

### 3. Setup environment variables

Create a .env file:

```env.local
MONGODB_URL=your_mongodb_url
AUTH_SECRET=fkfoet3454sta0d52M2W5S
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
CLOUDINARY_CLOUD_NAME=cloudinary_cloud_name
CLOUDINARY_API_KEY=cloudinary_api_key
CLOUDINARY_API_SECRET=cloudinary_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
NEXT_BASE_URL=http://localhost:3000
STRIPE_WEBHOOK_SECRET=
GMAIL_USER=your_gmail
GMAIL_APP_PASSWORD=your_gmail_password
GEMINI_API_KEY=your_gemini_api_key

```

### 4. Run the project

```Bash
npm run dev
```


## 🔮 Future Improvements
* 🧾 Invoice generation
* 📦 Advanced order tracking
* ⭐ Product reviews & ratings

## 🤝 Contributing

Contributions are welcome!

```
# Fork the repo
# Create a new branch
git checkout -b feature-name

# Commit changes
git commit -m "Added new feature"

# Push
git push origin feature-name
```

Then open a Pull Request


## 📄 License

This project is licensed under the MIT License.


## 🙌 Acknowledgements
* Inspired by real-world marketplaces like Amazon, Flipkart
* Built as a learning project for mastering full-stack development


## Author
Vikrant Kumar
* Github: https://github.com/Viku4780


## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!