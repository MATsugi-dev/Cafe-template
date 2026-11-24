# Cafe Template — Customization Guide

This guide walks you through personalizing the cafe website. You only need to edit `index.html`—the settings and menu data are near the bottom of the file.

## 1. Change the cafe name and business details

Find the `BUSINESS` object in the JavaScript near the bottom:

```js
const BUSINESS = {
  name: "Bean & Bloom",
  whatsapp: "639XXXXXXXXX",
  address: "123 Your Street, Your City, Philippines",
  email: "hello@example.com",
  // ...
};
```

Update the example values. The WhatsApp number should include the country code, without `+`, spaces, or punctuation. For a Philippine number, it starts with `63`.

## 2. Update the cafe text

Within `BUSINESS`, personalize the eyebrow text, hero title, description, story heading, and story paragraphs. Keep `heroTitleHtml`'s simple HTML structure (the `<br>` and `<span>` tags) if you want the title to wrap and highlight like the demo.

## 3. Change the photos

Replace `heroImage` and `storyImage` URLs in `BUSINESS`, and the `image` URL for each menu item.

- Use photos you own or have permission to use.
- Check that each image link opens correctly.
- Prefer reasonably sized images for faster loading.

## 4. Edit menu products

Find the `PRODUCTS` array:

```js
const PRODUCTS = [
  {
    id: 1,
    name: "Iced Latte",
    category: "Coffee",
    price: 140,
    description: "Espresso, chilled milk, and a refreshing smooth finish.",
    image: "https://example.com/photo.jpg"
  }
];
```

Every product needs:
- `id`: unique number—do not repeat IDs
- `name`: item name
- `category`: category name (filters are created automatically)
- `price`: number only; do not include `₱` or commas
- `description`: short description
- `image`: valid image URL

Copy a product object to add another item. Remove a product object to delete it. Keep commas between objects and make sure the array ends with `];`.

## 5. Change colors and styles

At the top of the CSS, look for `:root`. The variables control the overall theme:

```css
:root {
  --paper: #f6f2ea;
  --card: #fffdf9;
  --ink: #24231f;
  --muted: #77746b;
  --line: #e7e0d5;
  --accent: #9b5c3b;
  --accent-hover: #78442b;
  --forest: #263d32;
}
```

Replace color values with your own hex colors. If you are new to CSS, change one value at a time and refresh the browser to see the result.

## 6. Update opening hours

Edit the `hours` array inside `BUSINESS`. Each entry is a pair: the day label and the opening-hours text.

```js
hours: [
  ["Monday – Friday", "7 AM – 7 PM"],
  ["Saturday", "8 AM – 8 PM"],
  ["Sunday", "8 AM – 5 PM"]
]
```

## 7. Test before sharing or delivering

- [ ] Cafe name, contact details, and address are correct.
- [ ] WhatsApp number is correct and has the country code.
- [ ] Menu item names, categories, prices, and images are correct.
- [ ] Category filter buttons work.
- [ ] Add items, change quantities, remove items, and check the total.
- [ ] WhatsApp opens with the correct order summary.
- [ ] Mobile navigation opens and closes.
- [ ] Layout looks good on phone and desktop.
- [ ] Replace any demo photos/text and check third-party asset permissions.

## What the order feature does (and doesn't do)

This is a front-end template. The cart prepares a message and opens WhatsApp. It does not process payment, save orders to a database, confirm stock, or arrange delivery. The cafe confirms the order with the customer directly.

Enjoy customizing your cafe site! ☕
