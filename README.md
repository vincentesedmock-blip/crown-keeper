# Crown Keeper - Wig Sales Website

A modern, responsive e-commerce website for premium African hair wigs.

## 🌟 Features

- **Product Catalog**: Browse and filter wig collections
- **Shopping Cart**: Add items to cart with local storage
- **Responsive Design**: Works perfectly on mobile, tablet, and desktop
- **Professional Styling**: Modern UI with gold and brown color scheme
- **Multiple Pages**: Home, Shop, About, and Contact pages
- **Contact Form**: Get in touch with the team

## 📁 Project Structure

```
crown-keeper/
├── index.html          # Home page
├── products.html       # Product catalog
├── about.html          # About page
├── contact.html        # Contact page
├── style.css           # Main stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/vincentesedmock-blip/crown-keeper.git
   ```

2. Open `index.html` in your web browser

3. Or use a local server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## 🛒 Features Overview

### Home Page
- Hero section with call-to-action
- Featured collections
- Why choose us section

### Shop Page
- Product grid with filtering options
- Add to cart functionality
- Price ranges and product types

### About Page
- Company mission and story
- Commitment to quality and ethics
- Team information

### Contact Page
- Contact form
- Business information
- Social media links

## 💻 Technologies Used

- HTML5
- CSS3 (Flexbox, Grid)
- Vanilla JavaScript
- Local Storage API

## 🎨 Design Features

- **Color Scheme**: Gold (#d4af37) and Brown (#2c1810)
- **Responsive Grid**: Auto-fitting product cards
- **Smooth Animations**: Hover effects and transitions
- **Professional Typography**: Clear hierarchy and readability

## 🔧 Customization

### Add Products
Edit `products.html` and add new product cards to the grid:
```html
<div class="product-card">
    <div class="product-image">Image</div>
    <h3>Product Name</h3>
    <p>Description</p>
    <span class="price">$Price</span>
    <button class="btn btn-primary add-to-cart" data-name="Name" data-price="Price">Add to Cart</button>
</div>
```

### Change Colors
Modify the CSS variables in `style.css`:
- Primary Gold: `#d4af37`
- Dark Brown: `#2c1810`
- Light Beige: `#f9f7f4`

## 📱 Responsive Breakpoints

- Desktop: 1200px and above
- Tablet: 768px - 1199px
- Mobile: Below 768px

## 🔒 Local Storage

The shopping cart is saved in browser local storage, so items persist between sessions.

## 📞 Support

For questions or support, contact:
- Email: info@crownkeeper.com
- Phone: 1-800-CROWN-KEEPER

## 📄 License

This project is open source and available under the MIT License.

## 🎉 Next Steps

1. Add product images
2. Implement backend for cart and checkout
3. Set up payment processing
4. Add user accounts and orders
5. Integrate inventory management
6. Add reviews and ratings

---

**Crown Keeper** - Celebrating Black Beauty | Premium African Hair Wigs
