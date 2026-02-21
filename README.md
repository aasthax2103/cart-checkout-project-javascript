# 🚀 Cart & Checkout System (Vanilla JavaScript)

---

## 📌 Project Overview

This project is a **fully functional e-commerce frontend application** built using **HTML, CSS, and Vanilla JavaScript**.

It simulates a real-world online shopping workflow including:

- Product browsing  
- Smart search filtering  
- Cart management  
- Checkout flow  
- Order placement  
- Order history tracking

🌐 **Live Deployment:**  
https://aasthax2103.github.io/cart-checkout-project-javascript/components/amazon.html

The application integrates with a mock backend API and uses **localStorage for persistent cart state**, following real-world frontend architecture practices.

> ⚠️ This is an educational frontend project built for learning purposes only.  
> It is not affiliated with or endorsed by any commercial brand.  
> No real payments or personal data are processed.

---

## ⭐ Key Features

---

### 🛍 Product Browsing
- Dynamic product loading using **Fetch API**
- Object-Oriented Product Models
- Product rating and pricing support

---

### 🔎 Smart Search System
- URL-based search query system  
- Case-insensitive filtering  
- Supports:
  - Product name search  
  - Keyword-based search matching  

Example:
```
store.html?search=socks
```

---

### 🛒 Cart System
- Add to cart with quantity selection  
- Real-time cart size updates  
- Persistent cart using **localStorage**  
- Quantity editing in checkout page  
- Delivery option selection per product  

---

### 📦 Checkout System
Dynamic order summary calculation:

- Product subtotal  
- Shipping cost  
- Tax calculation  

Additional functionality:
- Backend **Order POST request simulation**
- Cart auto-clear after successful order placement  

---

### 📜 Orders History Page
Displays previously placed orders with:

- Order date  
- Order ID  
- Total cost  
- Purchased products  
- Delivery dates  
- **Buy Again** functionality (restores quantity to cart)

---

## 🧠 Technical Concepts Demonstrated

### JavaScript
- ES Modules  
- Async / Await  
- Fetch API  
- Event Handling  
- DOM Manipulation  
- URLSearchParams  

---

## 🏗 Architecture

**Separation of Concerns**

```
Data Layer → UI Rendering → Service Layer
```

Includes:

- Data Layer → `cart.js`, `products.js`, `orders.js`
- UI Rendering Layer → DOM rendering modules
- Service Layer → API communication

---

## 💾 Storage & State Management

- localStorage Cart Persistence  
- URL Query State Synchronization  
- Backend + Frontend State Coordination  

---

## 🌐 Backend Integration

Uses mock backend APIs:

```
GET  https://supersimplebackend.dev/products
POST https://supersimplebackend.dev/orders
```

These endpoints simulate real backend behavior for learning purposes.

---

## 🛠 Tech Stack

- HTML5  
- CSS3  
- JavaScript (ES6+)  
- DayJS (Date formatting)  
- LocalStorage  
- REST APIs  

---

## 📂 Project Structure

```
/data
  cart.js
  products.js
  orders.js
  deliveryOptions.js

/scripts
  store.js
  checkout.js
  orderSummary.js
  paymentSummary.js
  ordersPage.js
  header.js

/pages
  store.html
  checkout.html
  orders.html
```

---

## 💡 What Makes This Project Stand Out

✅ Built using **Pure Vanilla JavaScript (No Frameworks)**  
✅ Production-like state management  
✅ Realistic e-commerce workflow simulation  
✅ Modular and scalable architecture  
✅ URL-driven UI state  
✅ Advanced search logic (Name + Keyword Matching)  

---

## 📈 Future Improvements

- User authentication  
- Payment gateway integration  
- Inventory management  
- Admin dashboard  
- Order tracking timeline  
- Backend database integration  

---

## 👩‍💻 Author

**Aastha Garg**  
B.Tech CSE  
Frontend & Software Development Enthusiast  

---

## ⭐ Support

If you found this project useful or interesting, consider giving it a ⭐ on GitHub!
