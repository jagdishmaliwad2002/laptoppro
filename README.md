# LaptopPro – Laptop Store Homepage

A modern, responsive homepage for a premium laptop and electronics store, built with plain HTML, CSS and JavaScript in a single file.

**Created by Jagdish Maliwad**

---

## Preview

The page includes:

- Top info bar (address, free shipping, phone, track order, help center)
- Header with logo, search bar, compare, wishlist, cart and sign-in
- Main navigation with a "Shop by Category" button
- Hero section with headline, call-to-action buttons, 25% offer badge and trust icons
- Shop by Category slider (Ultrabooks, Gaming, Business, 2-in-1, Student, Workstations)
- "Best Deals on Top Brands" banner (Dell, HP, Lenovo, ASUS, Acer, MSI)
- Popular Laptops product cards with price, old price and ratings
- "Why Choose LaptopPro?" benefits strip
- Newsletter signup and full footer with payment methods

## Getting Started

1. Download `index.html`.
2. Double-click it to open in any modern browser (Chrome, Edge, Firefox, Safari).

No build tools, packages or server are needed.

## Project Structure

```
.
├── index.html   # Complete website (HTML + CSS + JS)
└── README.md    # Project documentation
```

## Features

- **Fully responsive:** desktop, tablet and mobile layouts
- **Interactive elements:**
  - Add to cart buttons update the cart badge
  - Wishlist icon toggles on and off
  - Category slider scrolls with the arrow button
  - Newsletter form validates the email address
- **No image files:** laptops, icons and logos are inline SVG, so the page loads fast
- **Accessible basics:** keyboard focus outlines, ARIA labels and reduced-motion support

## Customization

| What to change | Where |
| --- | --- |
| Brand colors | CSS variables at the top of `<style>` (`--blue`, `--navy`, etc.) |
| Store name, address, phone | Top bar, header and footer sections in the HTML |
| Products | The `products` array in the `<script>` at the bottom |
| Categories | The `categories` array in the `<script>` at the bottom |
| Product images | Replace the `svg` value of an item with an `<img>` tag |

## Tech Stack

- HTML5
- CSS3 (Grid, Flexbox, custom properties)
- Vanilla JavaScript
- [Inter](https://fonts.google.com/specimen/Inter) font from Google Fonts (falls back to system fonts offline)

## Author

**Jagdish Maliwad**

## License

Free to use and modify for personal and commercial projects. Please keep the credit to the author.
