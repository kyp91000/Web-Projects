# 🛒 E-Commerce Store (WooCommerce)

## Overview
A fully functional e-commerce store frontend featuring 9 products, a filter sidebar,
a live cart system with add/remove/quantity, wishlist, category navigation, hero banner,
and checkout flow. Built as a standalone HTML/CSS/JS site with full WooCommerce deployment guide.

## Features
- Top announcement bar (offers, support)
- Sticky navigation with search, wishlist, cart icon + item count badge
- Category navigation bar (8 categories)
- Hero deal banner with discount price display
- Product filter sidebar (category, price range, rating, brand)
- 9 product cards with discount badges, wishlist toggle, ratings
- Live cart sidebar: add, remove, change quantity, view total
- "Add to Cart" success animation
- Checkout confirmation popup
- Trust features bar (shipping, returns, payment, support)
- Mobile responsive

## Technologies Used
| Tool | Purpose |
|------|---------|
| HTML5 | Structure |
| CSS3 | Grid, Flexbox, animations |
| JavaScript (Vanilla) | Cart logic, filter UI, wishlist |
| WordPress | CMS |
| WooCommerce | Product catalog, checkout, payment |
| Elementor | Page design |

## Project Structure
```
09_ecommerce_store/
│
├── index.html     ← Complete standalone store frontend
└── README.md
```

## How to Run

### Standalone (Demo)
```
Double-click index.html in any browser.
```

### WordPress + WooCommerce Deployment
1. Install WordPress on hosting (cPanel → Softaculous)
2. Install **WooCommerce** plugin:
   - Set up store currency (INR), country (India)
   - Add products: Title, images, price, sale price, category, SKU
   - Configure Shipping zones & flat rate
   - Set up tax rates (GST 18% for electronics)
3. **Payment Gateways:**
   - Install **Razorpay for WooCommerce** plugin (UPI, Cards, NetBanking)
   - Or use **PayU** / **CCAvenue** plugin
   - Enable COD (Cash on Delivery) as fallback
4. Install **Elementor** for homepage design:
   - Build hero banner with countdown timer
   - Product grid using WooCommerce shortcodes:
     - `[products limit="9" columns="3"]`
     - `[sale_products]` for deal products
5. Install **YITH WooCommerce Wishlist** for wishlist feature
6. Install **WooCommerce PDF Invoices** for order emails
7. Enable transactional emails in WooCommerce → Settings → Emails

## WooCommerce Shortcodes
```
[products limit="12" columns="3" category="laptops"]
[product_category category="smartphones" limit="6"]
[sale_products limit="8"]
[featured_products limit="4"]
```

## Payment Setup (India)
| Gateway | Plugin |
|---------|--------|
| Razorpay | razorpay-woocommerce |
| PayU | payu-india-for-woocommerce |
| Instamojo | instamojo-payment-gateway |
| COD | Built into WooCommerce |
