# Cafe Website Starter Kit ☕

A clean, responsive cafe website template built with **HTML, CSS, and vanilla JavaScript**. No framework, build tools, or installation required—just customize the details and open it in a browser.

<p align="center">
  <a href="https://matsugi-dev.github.io/Cafe-template/">☕ Live Demo</a>
  ·
  <a href="https://github.com/MATsugi-dev/Cafe-template">📂 Source Code</a>
</p>

## ✨ Features

- Responsive layout for mobile, tablet, and desktop
- Cafe menu with automatically generated category filters
- Product cards with photos, descriptions, and prices
- Cart drawer with add, remove, and quantity controls
- Automatic subtotal and total calculation
- WhatsApp order handoff with a pre-filled order summary
- Contact button for direct WhatsApp messaging
- Centralized cafe settings and menu data
- Easy-to-edit CSS theme variables
- Accessibility basics: keyboard focus indicators, labels, Escape-to-close, and reduced-motion support
- Beginner-friendly comments throughout the source

## 🧰 Built With

| Technology | Purpose |
| --- | --- |
| HTML5 | Page structure and content |
| CSS3 | Layout, responsive styling, and theme |
| JavaScript | Menu filters, cart, and WhatsApp links |

## 🚀 Quick Start

**Option 1 — Download**
1. Open this repository and select **Code → Download ZIP**.
2. Extract the ZIP file.
3. Open `index.html` in your browser.

**Option 2 — Clone**
```bash
git clone https://github.com/MATsugi-dev/Cafe-template.git
cd Cafe-template
```
Then open `index.html` in your browser.

## 🎨 Customize the Template

Most content is controlled in one place: the `BUSINESS` settings and `PRODUCTS` array near the bottom of `index.html`.

1. **Business details:** change the cafe name, WhatsApp number, address, email, opening hours, and text.
2. **Menu:** update product names, categories, descriptions, prices, and image links. Use a unique ID for every product.
3. **Images:** use photos you own or have permission to use. Replace the demo images before publishing for a real business.
4. **Colors:** edit the CSS variables in the `:root` block near the top.
5. **Test:** check the site on phone and desktop, try each filter, test cart quantities, and verify the WhatsApp number.

See **[CUSTOMIZATION.md](CUSTOMIZATION.md)** for a more detailed step-by-step guide.

## 📁 Project Structure

```text
Cafe-template/
├── index.html          # Main website, styles, settings, and functionality
├── README.md           # Project overview and instructions
├── CUSTOMIZATION.md    # Buyer-friendly customization checklist
└── LICENSE             # Template license
```

## 🌐 Live Demo

[Open the website](https://matsugi-dev.github.io/Cafe-template/)

To publish your own copy with GitHub Pages:
1. Fork or copy this repository.
2. In your repository, open **Settings → Pages**.
3. Select the branch you want to publish and the root folder.
4. Save and wait for GitHub Pages to publish your site.

## ⚠️ Important Notes

- This is a **front-end demo/template**. WhatsApp is used to hand off order details.
- It does not process payments, store orders, confirm stock, or provide delivery services.
- The cafe must confirm the order and payment arrangements directly with the customer.
- Replace sample contact details and images before using it for a real business.
- External photos and fonts have their own licensing terms. Confirm you have permission to use them in any commercial project.

## 📄 License

See [LICENSE](LICENSE) for the included template license. Review the terms and any third-party asset rights before selling, redistributing, or delivering the template.

---

Made with ☕ by **MATsugi-dev**.
