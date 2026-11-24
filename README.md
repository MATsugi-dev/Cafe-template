# Cafe Website Starter Kit ☕
A polished, responsive cafe website starter built with HTML, CSS, and vanilla JavaScript. Includes a menu filter, shopping cart, quantity controls, and WhatsApp order handoff—no build tools or framework required.

## Live Demo
[View the demo](https://matsugi-dev.github.io/Cafe-template/)

## Features
- Responsive layout for phones, tablets, and desktop
- Menu category filters generated automatically from menu data
- Add-to-cart flow with quantity controls and total calculation
- WhatsApp checkout with a pre-filled order summary
- Contact button that opens a WhatsApp message
- Business information and menu products configured in one place
- CSS theme variables for quick recoloring
- Accessibility basics: focus styles, labels, Escape-to-close cart, reduced-motion support
- Beginner-friendly comments

## Preview
Open `index.html` in a browser, or enable GitHub Pages to publish the site.

## Quick Start
1. Download the repository ZIP or clone it:
   ```bash
   git clone https://github.com/MATsugi-dev/Cafe-template.git
   ```
2. Open `index.html` in your browser.
3. Edit the `BUSINESS` settings and `PRODUCTS` list in the JavaScript near the bottom of the file.
4. Replace image URLs, business details, menu, and prices.
5. Set the WhatsApp number before testing checkout.

## Customize
### Business details
Find `const BUSINESS = { ... }` and update:
- `name`
- `whatsapp` (country code, no plus, spaces, or punctuation; Philippines: `63...`)
- `address`, `email`
- hero and story copy
- image URLs
- `hours`

### Menu
Find `const PRODUCTS = [ ... ]`. Each product has:
- `id` — unique number
- `name`
- `category` — categories are automatically used as filters
- `price` — number only
- `description`
- `image` — image URL

### Colors
Edit the CSS custom properties in `:root` near the beginning of the style section.

## Important
This is a front-end template. WhatsApp is used to hand off order details. It does **not** process payments, store orders, verify inventory, or provide a delivery system. The cafe must confirm orders and payment arrangements directly with customers.

## Files
```text
Cafe-template/
├── index.html
├── README.md
└── LICENSE
```

## License
See `LICENSE`. The license included in this starter kit is intended for a buyer-facing template license; review and customize it before selling or distributing this project.

---
Made by **MATsugi-dev**.
