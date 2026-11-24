# Buyer Customization Guide

## 1. Rename the cafe
In `index.html`, locate the `BUSINESS` object and update the `name` value. The website uses this name for the title, logo, footer, and WhatsApp message.

## 2. Add your WhatsApp number
Set `whatsapp` to your full country-code number without `+`, spaces, or dashes. For example, a Philippine number should begin with `63`.

## 3. Update the menu
Edit the `PRODUCTS` array:
- Give every product a unique `id`.
- Set its `name`, `category`, `price`, `description`, and `image`.
- Price is a number, not a formatted string.
- Categories automatically become menu filter buttons.

## 4. Replace the photos
Use image URLs you own or have permission to use. Confirm they work on mobile and are appropriately sized.

## 5. Change colors
Edit CSS variables under `:root` at the top of the file.

## 6. Test the website
- Open on phone and desktop sizes.
- Try each category filter.
- Add multiple items and adjust quantities.
- Remove items and verify the total.
- Test WhatsApp with a real configured number.
- Check your location, hours, prices, and contact info.

## Notes
This is a front-end template only. Orders are handed off through WhatsApp and are not automatically paid, saved, or confirmed.
