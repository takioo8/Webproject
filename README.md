
# EgyptStore - Modern E-Commerce Website

A modern, responsive fashion e-commerce website featuring a comprehensive shopping experience with user authentication, shopping cart functionality, and product management. Built with HTML, CSS, and JavaScript with a backend API integration.

## 🌟 Features

### Core Functionality
- **Multi-Category Shopping**: Separate collections for Men, Women, and Kids fashion
- **User Authentication**: Complete login and registration system with secure account management
- **Shopping Cart**: Full-featured cart with add, update, and remove functionality
- **Product Management**: Detailed product pages with size selection and pricing
- **Checkout System**: Comprehensive checkout process with shipping and billing information
- **Order Tracking**: View and manage customer orders
- **Responsive Design**: Mobile-first approach ensuring seamless experience across all devices

### User Experience
- **Intuitive Navigation**: Easy-to-use menu system with clear category organization
- **Product Filtering**: Size options (XS, S, M, L, XL, XXL) for each product
- **Featured Products**: Dynamic loading of featured items on homepage
- **Hero Section**: Eye-catching hero banner with promotional offers
- **Newsletter Integration**: Customer engagement through newsletter signup
- **Contact Page**: Direct communication channel with the business

### Design Features
- **Modern UI/UX**: Clean, contemporary design with smooth animations
- **High-Quality Visuals**: Professional product imagery and layout
- **Loading Animations**: Enhanced user experience with loading states
- **Notification System**: Real-time feedback for user actions
- **Social Media Integration**: Connect with customers through social platforms

## 📁 Project Structure

```
Webproject/
├── MainPage.html           # Homepage with featured products and hero section
├── men.html                # Men's fashion collection
├── women.html              # Women's fashion collection
├── kids.html               # Kids fashion collection
├── login.html              # User login page
├── register.html           # New user registration
├── cart.html               # Shopping cart page
├── checkout.html           # Checkout and payment page
├── orders.html             # Order history and tracking
├── product-details.html    # Individual product detail page
├── blog.html               # Fashion blog section
├── about.html              # About us page
├── contact.html            # Contact information and form
├── style.css               # Main stylesheet
├── auth.css                # Authentication page styles
├── cart.css                # Shopping cart styles
├── category.css            # Category page styles
├── contact.css             # Contact page styles
├── newsletter.css          # Newsletter section styles
├── navbar-user-menu.css    # Navigation menu styles
├── product-detail.css      # Product detail page styles
└── img/                    # Image assets directory
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Backend API server running on `http://localhost:5037`
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/takioo8/Webproject.git
   cd Webproject
   ```

2. **Set up the backend API**
   - Ensure your backend API is running on `http://localhost:5037`
   - The API should provide the following endpoints:
     - `GET /api/Products` - Fetch all products
     - `POST /api/Cart` - Add items to cart
     - `GET /api/Cart` - Retrieve cart items
     - Authentication endpoints for user management

3. **Open the project**
   - Open `MainPage.html` in your web browser
   - Or use a local development server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js http-server
     npx http-server
     ```

4. **Access the application**
   - Navigate to `http://localhost:8000` (or your configured port)
   - Start browsing the fashion collections!

## 💻 Usage

### For Customers

1. **Browse Products**
   - Visit the homepage to see featured products
   - Navigate to Men, Women, or Kids sections for specific collections
   - Use the search and filter options to find desired items

2. **Shopping**
   - Select product size before adding to cart
   - Click "Add to Cart" to add items
   - View cart summary in the navigation bar
   - Proceed to checkout when ready

3. **Account Management**
   - Register for a new account or login with existing credentials
   - Track your orders from the Orders page
   - Update profile information as needed

4. **Checkout**
   - Complete shipping and billing information
   - Review order summary
   - Confirm and place order

### For Developers

#### API Integration
The project connects to a backend API for data management:

```javascript
// Example: Fetching products
const response = await fetch('http://localhost:5037/api/Products');
const products = await response.json();

// Example: Adding to cart
await cartService.addToCart(productId, quantity, size);
```

#### Customization
- **Styling**: Modify CSS files for custom branding
- **Layout**: Adjust HTML structure in respective page files
- **Features**: Extend JavaScript functionality in inline scripts or external files

## 🎨 Design Philosophy

The website follows modern e-commerce best practices:

- **Mobile-First Design**: Optimized for mobile devices with responsive layouts
- **User-Centric**: Intuitive navigation and clear call-to-action buttons
- **Performance**: Optimized loading times with efficient image handling
- **Accessibility**: Semantic HTML and keyboard navigation support
- **Visual Hierarchy**: Clear content organization with proper spacing and typography

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Icons**: Font Awesome Pro 5.10.0
- **Design Pattern**: Responsive Web Design
- **API Integration**: RESTful API with async/await
- **Architecture**: Client-side rendered single-page application approach

## 📱 Key Pages

### Homepage (MainPage.html)
- Hero section with promotional banners
- Featured categories showcase
- Latest product collection
- Newsletter signup
- Key features highlight

### Category Pages (men.html, women.html, kids.html)
- Filtered product displays by category
- Grid layout with product cards
- Quick add to cart functionality
- Size selection interface

### Product Details (product-details.html)
- High-resolution product images
- Detailed product descriptions
- Size guide and selection
- Add to cart with quantity control
- Related products suggestions

### Shopping Cart (cart.html)
- Item list with images and prices
- Quantity adjustment controls
- Remove items functionality
- Order summary with totals
- Proceed to checkout button

### Checkout (checkout.html)
- Multi-step checkout process
- Shipping address form
- Billing information
- Order review section
- Payment method selection

## 🔐 Authentication

The website includes a complete authentication system:

- User registration with validation
- Secure login functionality
- Session management
- Protected routes for authenticated users
- Guest checkout option

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Contact Information

**Fashion Store**
- **Address**: Port Said Street, Naga Hammadi City, Qena Governorate
- **Phone**: (+20) 01281925975 / (+20) 01559886232
- **Hours**: 10:00 AM - 6:00 PM, Monday - Saturday

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## 📝 Future Enhancements

- [ ] Payment gateway integration (Stripe, PayPal)
- [ ] Product review and rating system
- [ ] Wishlist functionality
- [ ] Advanced product filtering and sorting
- [ ] Email notifications for orders
- [ ] Admin dashboard for inventory management
- [ ] Multi-language support
- [ ] Currency conversion
- [ ] Live chat support
- [ ] Virtual try-on feature using AR

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Developer

Created by **takioo8**

- GitHub: [@takioo8](https://github.com/takioo8)
- Repository: [Webproject](https://github.com/takioo8/Webproject)

## 🙏 Acknowledgments

- Font Awesome for the icon library
- Product images and design inspiration from modern fashion e-commerce platforms
- Backend API team for providing robust endpoints

---

**Happy Shopping! 🛍️**

For questions or support, please open an issue on GitHub or contact us through the website's contact page.
