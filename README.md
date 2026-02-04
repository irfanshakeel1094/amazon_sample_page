# Amazon Clone - E-Commerce Website

A fully functional Amazon clone built with vanilla JavaScript, HTML, and CSS. This project replicates the core shopping experience of Amazon, including product browsing, cart management, checkout process, and order tracking.

## 🌟 Features

- **Product Catalog**: Browse through a wide selection of products with detailed information
- **Shopping Cart**: Add, remove, and update product quantities in your cart
- **Checkout Process**: Complete purchase flow with delivery options
- **Order Management**: View order history and track shipments
- **Order Tracking**: Real-time tracking page for deliveries
- **Responsive Design**: Works seamlessly across different screen sizes
- **Local Storage**: Cart data persists across browser sessions

## 🚀 Live Demo

[View Live Site](#) <!-- Add your GitHub Pages or deployment URL here -->

## 💻 Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Styling with Flexbox/Grid layouts
- **JavaScript (ES6+)**: Core functionality and interactivity
- **JSON**: Product data management

## 📁 Project Structure

```
javascript-amazon-project-main/
├── amazon.html          # Main product listing page
├── checkout.html        # Shopping cart and checkout
├── orders.html          # Order history page
├── tracking.html        # Order tracking page
├── data/
│   └── products.js      # Product data
├── backend/
│   └── products.json    # Product database
├── images/              # Product images and icons
├── styles/
│   ├── pages/          # Page-specific styles
│   └── shared/         # Shared/common styles
└── README.md
```

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   cd YOUR-REPO-NAME
   ```

2. **Open in browser**
   - Simply open `amazon.html` in your web browser
   - Or use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js http-server
     npx http-server
     ```

3. **Access the application**
   - Navigate to `http://localhost:8000/amazon.html`

## 📖 Usage

1. **Browse Products**: Start at the main page to view available products
2. **Add to Cart**: Click "Add to Cart" on any product
3. **View Cart**: Check the cart icon in the header to see selected items
4. **Checkout**: Proceed to checkout page to review and place orders
5. **Track Orders**: View order history and track deliveries

## ✨ Key Features Implementation

### Shopping Cart
- Add/remove items dynamically
- Update quantities
- Calculate totals automatically
- Persist cart data using localStorage

### Product Display
- Grid layout for product cards
- Product images, ratings, and pricing
- Search and filter capabilities

### Checkout Process
- Delivery date selection
- Order summary
- Payment options

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is for educational purposes only.

## 👤 Author

**Your Name**
- GitHub: [@YOUR-USERNAME](https://github.com/YOUR-USERNAME)

## 🙏 Acknowledgments

- Inspired by Amazon's e-commerce platform
- Built as a learning project to practice JavaScript fundamentals

---

⭐ If you found this project helpful, please give it a star!
