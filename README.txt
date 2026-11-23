HE GOT FADED — PWA starter
==========================

Files:
- index.html: agenda interface
- manifest.webmanifest: installable app metadata
- sw.js: service worker for app-shell caching/offline shell
- icon-192.png / icon-512.png: app icons
- icon.svg: vector icon

Important:
This is a PWA starter package, not yet a production booking service.
The current agenda stores bookings in the visitor's browser localStorage.
It does NOT yet sync bookings between customers and your phone, provide secure
server-side admin authentication, or send remote push notifications.

To make it production-ready, the next step is to deploy this package over HTTPS
and connect a real backend/database plus authenticated admin access and Web Push.
Do not publish this localStorage-only version as a live booking link.
