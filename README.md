# DigiTaluq — Digital Marketing & Branding Agency

DigiTaluq is the official static website for **DigiTaluq Inc.**, a creative digital marketing and branding agency. The site showcases the agency's services, portfolio, editorial journal, client testimonials, awards, and provides a direct contact channel for prospective clients.

Built with plain **HTML5**, **CSS3**, **Bootstrap**, and **vanilla JavaScript** powered by a handful of well-known libraries (GSAP, Swiper, WOW, Odometer), the site is fully static — no build step, no backend — making it lightweight, fast, and easy to deploy anywhere.

---

## Live Site

🌐 **https://digitaluq.vercel.app**

---

## Features

- **Modern, animated landing page** with hero banner, smooth scroll effects, and GSAP-powered transitions.
- **Services showcase** covering Strategic Branding, Video Production, Print & Graphic Design, SEO, Content Creation, Production House, Amazon Services, AI-Driven Solutions, and Web Development.
- **Portfolio / Work gallery** with project case studies.
- **Editorial Journal** with category-specific posts (Design, Web, SEO, Branding, Marketing).
- **Client testimonials carousel** powered by Swiper.
- **Animated statistics counters** powered by Odometer.
- **Awards section** highlighting industry recognition.
- **Contact form** integrated with [Web3Forms](https://web3forms.com/) for serverless form submission.
- **Fully responsive** layout for desktop, tablet, and mobile.
- **SEO-ready** with Open Graph tags, JSON-LD structured data, canonical URLs, sitemap, and favicons.

---

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Homepage — hero, services, gallery, journal previews, testimonials, stats, awards |
| `about.html` | About the agency and contact form |
| `work.html` | Portfolio of completed projects |
| `single-work.html` | Single project / case study detail page |
| `journal.html` | Journal landing page (blog index) |
| `design-journal.html` | Article: Design That Speaks |
| `web-journal.html` | Article: The Future of Web Development |
| `seo-journal.html` | Article: Staying Ahead of Google's Algorithm |
| `branding-journal.html` | Article: Building Brand Identity |
| `marketing-journal.html` | Article: Online Marketing Strategy |
| `contact.html` | Standalone contact page |
| `sitemap.xml` | XML sitemap for search engines |

---

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom styles plus Bootstrap utilities
- **Bootstrap** — responsive grid and components
- **jQuery** — DOM utilities and plugin support
- **GSAP** (with `SplitText`, `ScrollTrigger`, `ScrollToPlugin`, `ScrollSmoother`) — high-performance animations
- **Swiper** — touch-friendly testimonial carousel
- **WOW.js** — on-scroll element reveal animations
- **Odometer** — animated number counters
- **Web3Forms** — backend-less contact form handling
- **Google Fonts** (Inter, Lora) — typography
- **Font Awesome** — iconography

---

## Project Structure

```
digitaluq/
├── assets/
│   ├── css/              # Bootstrap, style, responsive stylesheets
│   ├── fonts/            # Custom and icon fonts
│   ├── images/           # Logos, gallery, icons, favicons, manifest
│   └── js/               # jQuery, GSAP, Swiper, Odometer, custom script
├── index.html            # Homepage
├── about.html
├── work.html
├── single-work.html
├── journal.html
├── design-journal.html
├── web-journal.html
├── seo-journal.html
├── branding-journal.html
├── marketing-journal.html
├── contact.html
├── sitemap.xml
└── README.md
```

---

## Getting Started

### Run locally

Since the site is fully static, you can open it directly in a browser:

```bash
# Clone the repo
git clone https://github.com/<your-username>/digitaluq.git
cd digitaluq

# Option 1: open index.html directly in your browser
xdg-open index.html        # Linux
open index.html            # macOS
start index.html           # Windows
```

### Serve with a local web server (recommended)

A local server avoids CORS and path issues with some browsers.

```bash
# Python 3
python3 -m http.server 8000

# Node.js (with npx)
npx serve .

# PHP
php -S localhost:8000
```

Then visit **http://localhost:8000**.

---

## Deployment

The site is currently deployed on **Vercel** at [digitaluq.vercel.app](https://digitaluq.vercel.app).

Since it's fully static, it can be deployed to any static hosting provider:

- **Vercel** (current) — connect the repo, no build command needed, output directory is the project root.
- **GitHub Pages** — push the repo and enable Pages from the repository settings.
- **Netlify / Cloudflare Pages** — connect the repo, no build command needed, publish directory is the project root.
- **Traditional hosting** — upload all files to your web root via FTP/SFTP.

---

## Configuration

### Contact form

The form on `about.html` posts to Web3Forms. To use your own endpoint, replace the `access_key` value in the form:

```html
<input type="hidden" name="access_key" value="YOUR_WEB3FORMS_ACCESS_KEY">
```

Sign up at [web3forms.com](https://web3forms.com/) to obtain a key.

### SEO metadata

Update the `<meta>` tags, JSON-LD block, and `sitemap.xml` in each HTML file to reflect your domain and content.

---

## License

This project is released under the **MIT License**. It is adapted from an open-source template; all modifications are made in compliance with the original author's license terms.

---

## Contact

- **Live site:** [digitaluq.vercel.app](https://digitaluq.vercel.app)
- **Website:** [digitaluq.com](https://www.digitaluq.com)
- **Email:** [contact@digitaluq.com](mailto:contact@digitaluq.com)
- **WhatsApp:** [+92 329-4545154](https://wa.me/+923294545154)
- **LinkedIn:** [digitaluq-inc](https://www.linkedin.com/company/digitaluq-inc/)
- **Instagram:** [@digitaluq.co](https://www.instagram.com/digitaluq.co)
- **Facebook:** [digitaluqinc](https://facebook.com/digitaluqinc)

---

_© 2024 DigiTaluq — Powered by Usman._
