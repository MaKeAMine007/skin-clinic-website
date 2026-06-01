# Skin Clinic Website

A clean, production-ready dermatology clinic website based on the Dermal HTML template.

## Pages

| File | URL | Description |
|------|-----|-------------|
| `index.html` | `/` | Home Page |
| `about.html` | `/about.html` | About Us |
| `services.html` | `/services.html` | Services Listing |
| `service-detail.html` | `/service-detail.html` | Single Service Detail |
| `blog.html` | `/blog.html` | Blog Listing |
| `blog-detail.html` | `/blog-detail.html` | Single Blog Post |
| `contact.html` | `/contact.html` | Contact Us |

## Folder Structure

```
skin-clinic-website/
├── index.html
├── about.html
├── services.html
├── service-detail.html
├── blog.html
├── blog-detail.html
├── contact.html
│
├── assets/
│   ├── css/          ← Bootstrap, Swiper, custom styles
│   ├── js/           ← jQuery, Bootstrap, Swiper, animations
│   ├── images/       ← All image assets
│   ├── fonts/        ← Font Awesome webfonts
│   └── vendor/       ← Reserved for future third-party libs
│
├── partials/
│   ├── header.html   ← Reusable header extract
│   ├── footer.html   ← Reusable footer extract
│   └── navbar.html   ← Reusable navigation extract
│
└── README.md
```

## Book Appointment

All "Book Appointment" buttons call the clinic directly:

```html
<a href="tel:+919999999999">Book Appointment</a>
```

Replace `+919999999999` with the actual clinic phone number before going live.

## Deployment

Static HTML — deploy to any host (Vercel, Netlify, Apache, Nginx).

No build step required. Open `index.html` directly in a browser for local preview.
