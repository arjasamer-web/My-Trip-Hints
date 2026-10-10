# MyTripHints Web Portal

Official web portals and landing pages for **MyTripHints** — Explore • Eat • Meet • Chat.

---

## 📁 Repository Structure

```text
├── index.html            # Main Landing & Coming Soon page with App Store / Google Play download cards & QR codes
├── assets/               # Branding assets, photography, and generated QR codes
│   └── images/
│       ├── logo.png
│       ├── travel_collage_bg.jpg
│       ├── qr_apple.png
│       └── qr_google.png
├── admin/                # Compiled Flutter Web Admin Portal (accessible via /admin/)
└── reset-password/       # Standalone Supabase Password Reset page (accessible via /reset-password/)
    └── index.html
```

---

## 🚀 Features

- **Coming Soon Landing Page (`/`)**:
  - High-resolution cinematic background collage with dark overlay.
  - App Store & Google Play download badges with interactive QR codes for scanning directly from mobile cameras.
  - Full bilingual support (English & Arabic with instant RTL/LTR switching).
  - Configurable download URLs in `index.html` (`window.APP_CONFIG`).

- **Admin Portal (`/admin/`)**:
  - Flutter Web Admin Panel build with pre-configured `<base href="/admin/">`.

- **Password Reset (`/reset-password/`)**:
  - Supabase Auth integrated password reset with password strength validation and token expiration handling.
  - Bilingual support (English & Arabic).

---

## 🌐 Deployment

This project is fully static and ready for direct deployment on:
- **GitHub Pages**
- **Cloudflare Pages**
- **Vercel / Netlify**
- **Any standard HTTP Web Server (Nginx, Apache, Caddy)**

---

© 2026 MyTripHints. All rights reserved.
