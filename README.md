# GharSewa — Home Services Landing Page

A mobile-responsive, single-page website for a home services platform based in Kathmandu and Lalitpur. It features standardized fixed pricing menus and an instant verification pipeline that routes bookings directly to WhatsApp.

## 🚀 Features
* **Zero Dependencies:** Pure HTML, CSS, and vanilla JS.
* **Frictionless Booking:** Frontend validation that formats and sends requests to WhatsApp.
* **Optimized Design:** Lightweight CSS grid layout with smooth scroll reveal animations.

## 🔧 Setup & Configuration
To update the receiving WhatsApp number or brand name, simply change the variables at the top of the `<script>` tag in `index.html`:

```javascript
const WHATSAPP_NUMBER = "9779824556800"; 
const BUSINESS_NAME = "GharSewa";
