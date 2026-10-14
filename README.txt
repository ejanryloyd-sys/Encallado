CECPRINTHUB PRINTING SERVICES — PYSCRIPT VERSION

This version uses Python via PyScript for the website interactions. The custom app.js file has been removed; app.py handles login, registration, navigation, orders, and admin actions.

HOW TO RUN
1. Extract this ZIP file.
2. Make sure you have an internet connection (PyScript is loaded from its CDN).
3. Open a terminal/command prompt inside this folder.
4. Run: python -m http.server 8000
5. Open http://localhost:8000 in your browser.
   (Serving over localhost is recommended; opening index.html directly may prevent PyScript from loading.)

DEFAULT DEMO ADMIN
Email: janry@gmail.com
Password: Encallado123

FEATURES
- Login, customer registration, and admin login
- Customer homepage and print service selection
- Order details, optional file-name capture, pickup date/time, checkout review
- Success toast: "Ordered Successfully, See you soon"
- Customer order history and admin order management
- Admin checkbox updates the customer's order status to "Your order is noted"
- About page, Google Maps store link, and pickup-only notice
- Back buttons on pages

IMPORTANT LIMITATIONS
This is a browser-based demo. User accounts and orders are saved in browser localStorage, not a shared server database. Admin/customer notifications are reflected when they access the same browser storage; real multi-device notifications require a secure backend/database. The demo stores passwords in browser storage and is not suitable for public production use without proper server-side authentication and security.


LATEST UPDATE
- Password visibility toggle on customer login, create account, and admin login.
- Customer print file is required before reviewing an order.
- Selected file is stored as a data URL in browser storage and can be opened/downloaded from the admin order card.
- File upload demo limit is 2 MB to reduce browser storage issues.
- Admin can delete an order after confirming: "Are you sure to delete this customer?"
- Admin footer hides About and Location links. The Back to top footer link has been removed.
- Customer About and Location cards are more prominent on the homepage.
- Logout asks for confirmation. OK logs out to the login screen; Cancel keeps the user on the current page.
Note: This is still a browser-only demo. Browser storage is not a secure shared database and file storage is not suitable for production.
