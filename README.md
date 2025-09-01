# Niyantri Cafe - Five Page Website

This project implements a five-page coffee shop site with a PayPal sandbox integration for cart checkout:

Pages:
- index.html (Home)
- menu.html (Menu)
- cart.html (Cart with PayPal checkout)
- about.html (About)
- contact.html (Contact)

Key Features:
- Tailwind CSS for styling with a warm coffee color theme
- Responsive mobile navigation with a hamburger menu
- Shared header and footer across all pages
- Static 8-item menu with INR pricing and Add to Cart functionality (localStorage)
- Cart page with itemized list, total, and a PayPal button (sandbox) for payment
- Testimonials on Home page
- Semantic HTML5 structure and accessible alt attributes
- Placeholder address: Telangana, Hyderabad, India on the Contact page
- Embedded inline SVG icons
- Simple image carousel using Swiper.js on Home page

Usage:
- Open the pages in a browser. The cart persists in localStorage. You can add items from the Menu page and view them in the Cart page. Use PayPal sandbox to simulate payment.

Notes:
- The PayPal integration uses client-id=sb for sandbox.
- The current year is set to 2025 for the footer.