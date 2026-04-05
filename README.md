# Streak egy - Simplified Version

This is a simplified, high-performance version of the **Streak egy** website.

## Key Improvements
- **No Dependencies**: This project does not require Node.js, NPM, or any complex build tools.
- **Zero Installation**: Just open `index.html` in any web browser to see it working.
- **CDN Powered**: Uses industry-standard libraries directly from CDNs:
  - **Tailwind CSS**: For modern, responsive styling.
  - **Alpine.js**: For lightweight interactivity (Cart, Modals, Language Switching).
  - **Lucide Icons**: For clean, professional iconography.

## Features
- **Full Product Catalog**: All products and categories are included in `data.js`.
- **Functional Shopping Cart**: Add items, adjust quantities, and see your total (persists even if you close the tab).
- **WhatsApp Checkout**: Place orders directly through WhatsApp with a pre-filled message.
- **Multi-language Support**: Easily switch between English and Arabic.
- **Responsive Design**: Works perfectly on mobile, tablet, and desktop.

## Project Structure
- `index.html`: Home page with hero, features, and collections.
- `shop.html`: Full product listing with filtering and quick view.
- `about.html`: Brand story and mission.
- `contact.html`: Contact information and social links.
- `data.js`: Centralized data store for products and configuration.
- `logo.png`: Official brand logo.

## How to Modify
- **Add Products**: Edit the `products` array in `data.js`.
- **Change Colors/Styles**: Edit the Tailwind configuration in the `<head>` of each HTML file.
- **Update Logic**: Interactivity is handled via `Alpine.js` scripts at the bottom of each page.

Enjoy your new, lightweight website!
