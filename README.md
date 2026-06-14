# 🛒 Grocery List App

A feature-rich Grocery List Application built with React.js that helps users manage their grocery shopping experience efficiently. The app allows users to browse products, search and filter items, apply coupons, receive automatic discounts, and maintain their cart even after refreshing the page.

## ✨ Features

### 🛍️ Cart Management
- Add items to the cart
- Remove items from the cart
- Update item quantities
- View cart total in real-time

### 💰 Automatic Discount System
- Percentage-based discounts are automatically applied when the cart total exceeds a predefined threshold.

### 🎟️ Coupon Code System
- Apply promotional coupon codes for additional discounts.
- Invalid coupon handling with user-friendly feedback.

### 🔍 Search Functionality
- Search products instantly by name.

### 📂 Category Filtering
- Filter products by category for easier browsing.

### 📊 Sorting Options
- Price: Low to High
- Price: High to Low
- Name: A-Z
- Name: Z-A

### 💾 Local Storage Persistence
- Cart data is saved automatically.
- Cart remains intact after page refresh or browser restart.

### ↩️ Undo Last Action
- Undo the most recent cart addition or removal.
- Improves user experience by preventing accidental actions.

## 🛠️ Built With

- React.js
- JavaScript (ES6+)
- React Hooks
- CSS3
- Local Storage API

## 📁 Project Structure

```text
src/
├── components/
│   ├── ProductList
│   ├── ProductCard
│   ├── Cart
│   ├── SearchBar
│   ├── Filter
│   ├── Sort
│   └── CouponInput
│
├── data/
│   └── products.js
│
├── utils/
│   ├── discountCalculator.js
│   └── couponValidator.js
│
├── App.js
└── index.js
```

## 🚀 Getting Started

### Prerequisites

Make sure you have installed:

- Node.js
- npm

### Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/grocery-list-app.git
```

2. Navigate to the project folder

```bash
cd grocery-list-app
```

3. Install dependencies

```bash
npm install
```

4. Start the development server

```bash
npm start
```

The application will be available at:

```text
http://localhost:3000
```

## 💡 Key Concepts Implemented

- React State Management
- Component-Based Architecture
- Array Manipulation
- Search and Filter Logic
- Local Storage Integration
- Discount Calculation
- Coupon Validation
- Undo Functionality
- Responsive UI Design

## 🔮 Future Improvements

- User Authentication
- Wishlist Feature
- Product Images Upload
- Backend Integration
- Payment Gateway
- Order History
- Dark Mode

## 📸 Screenshots

Add screenshots of your application here.

```text
screenshots/
├── home-page.png
├── cart-page.png
├── search-feature.png
└── coupon-discount.png
```

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit a pull request.

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

Rasika Rasi

If you found this project useful, please consider giving it a ⭐ on GitHub.
