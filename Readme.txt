# Thriveright Health Foundation Website

A responsive, accessible, and clean website developed for **Thriveright Health Foundation** — a non-profit organization dedicated to creating awareness and providing outreach programs on **sickle cell disorder**, especially within schools and communities.

## 📌 Project Overview

This website is a **static site** built using **HTML**, **CSS**, and **Bootstrap 5.3.3**. It is designed to be fast, minimal, and mobile-friendly, serving as an online presence for the foundation’s outreach efforts and educational mission.

The website includes:
- Homepage with mission and vision
- About section describing the foundation
- Gallery showcasing outreach images from school visits
- Blog/News section (optional)
- Contact page with an active form
- Social media and WhatsApp chat integration

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- **Bootstrap 5.3.3**
- **Font Awesome / Bootstrap Icons**

## 🔍 Features

- 💻 Fully responsive design
- 🎨 Clean, minimalistic interface
- 📸 Gallery section renamed as **Outreach Gallery** to reflect school-based awareness efforts
- 🧬 Sickle Cell Disorder awareness content and mission representation
- 📞 Contact form with proper HTML structure and field validation
- 📷 Lightbox-enabled image and video display
- 🧭 Accessible navigation and semantic layout

## 🧱 Folder Structure

    C:.
    │   index.html
    │   Readme.txt
    │
    ├───assets
    │   ├───css
    │   │       main.css
    │   │
    │   ├───img
    │   │   │   apple-touch-icon.png
    │   │   │   contact-bg.png
    │   │   │   favicon.ico
    │   │   │   favicon.jpg
    │   │   │   favicon.png
    │   │   │   hero-img.jpg
    │   │   │   hero-img.png
    │   │   │   logo.png
    │   │   │   services-1.jpg
    │   │   │   services-2.jpg
    │   │   │   services-3.jpg
    │   │   │   services-4.jpg
    │   │   │   services.jpg
    │   │   │   stats-img.svg
    │   │   │
    │   │   ├───portfolio
    │   │   │       app-1.jpg
    │   │   │       app-2.jpg
    │   │   │       app-3.jpg
    │   │   │       app-4.jpg
    │   │   │       app-5.jpg
    │   │   │       app-6.jpg
    │   │   │       books-1.jpg
    │   │   │       books-2.jpg
    │   │   │       books-3.jpg
    │   │   │       branding-1.jpg
    │   │   │       branding-2.jpg
    │   │   │       branding-3.jpg
    │   │   │       product-1.jpg
    │   │   │       product-2.jpg
    │   │   │       product-3.jpg
    │   │   │       video-1.jpg
    │   │   │
    │   │   ├───team
    │   │   │       team-1.jpg
    │   │   │       team-2.jpg
    │   │   │       team-3.jpg
    │   │   │       team-4.jpg
    │   │   │
    │   │   └───testimonials
    │   │           testimonials-1.jpg
    │   │           testimonials-2.jpg
    │   │           testimonials-3.jpg
    │   │           testimonials-4.jpg
    │   │           testimonials-5.jpg
    │   │
    │   ├───js
    │   │       main.js
    │   │
    │   ├───scss
    │   │       Readme.txt
    │   │
    │   ├───vendor
    │   │   ├───aos
    │   │   │       aos.cjs.js
    │   │   │       aos.css
    │   │   │       aos.esm.js
    │   │   │       aos.js
    │   │   │       aos.js.map
    │   │   │
    │   │   ├───bootstrap
    │   │   │   ├───css
    │   │   │   │       bootstrap-grid.css
    │   │   │   │       bootstrap-grid.css.map
    │   │   │   │       bootstrap-grid.min.css
    │   │   │   │       bootstrap-grid.min.css.map
    │   │   │   │       bootstrap-grid.rtl.css
    │   │   │   │       bootstrap-grid.rtl.css.map
    │   │   │   │       bootstrap-grid.rtl.min.css
    │   │   │   │       bootstrap-grid.rtl.min.css.map
    │   │   │   │       bootstrap-reboot.css
    │   │   │   │       bootstrap-reboot.css.map
    │   │   │   │       bootstrap-reboot.min.css
    │   │   │   │       bootstrap-reboot.min.css.map
    │   │   │   │       bootstrap-reboot.rtl.css
    │   │   │   │       bootstrap-reboot.rtl.css.map
    │   │   │   │       bootstrap-reboot.rtl.min.css
    │   │   │   │       bootstrap-reboot.rtl.min.css.map
    │   │   │   │       bootstrap-utilities.css
    │   │   │   │       bootstrap-utilities.css.map
    │   │   │   │       bootstrap-utilities.min.css
    │   │   │   │       bootstrap-utilities.min.css.map
    │   │   │   │       bootstrap-utilities.rtl.css
    │   │   │   │       bootstrap-utilities.rtl.css.map
    │   │   │   │       bootstrap-utilities.rtl.min.css
    │   │   │   │       bootstrap-utilities.rtl.min.css.map
    │   │   │   │       bootstrap.css
    │   │   │   │       bootstrap.css.map
    │   │   │   │       bootstrap.min.css
    │   │   │   │       bootstrap.min.css.map
    │   │   │   │       bootstrap.rtl.css
    │   │   │   │       bootstrap.rtl.css.map
    │   │   │   │       bootstrap.rtl.min.css
    │   │   │   │       bootstrap.rtl.min.css.map
    │   │   │   │
    │   │   │   └───js
    │   │   │           bootstrap.bundle.js
    │   │   │           bootstrap.bundle.js.map
    │   │   │           bootstrap.bundle.min.js
    │   │   │           bootstrap.bundle.min.js.map
    │   │   │           bootstrap.esm.js
    │   │   │           bootstrap.esm.js.map
    │   │   │           bootstrap.esm.min.js
    │   │   │           bootstrap.esm.min.js.map
    │   │   │           bootstrap.js
    │   │   │           bootstrap.js.map
    │   │   │           bootstrap.min.js
    │   │   │           bootstrap.min.js.map
    │   │   │
    │   │   ├───bootstrap-icons
    │   │   │   │   bootstrap-icons.css
    │   │   │   │   bootstrap-icons.json
    │   │   │   │   bootstrap-icons.min.css
    │   │   │   │   bootstrap-icons.scss
    │   │   │   │
    │   │   │   └───fonts
    │   │   │           bootstrap-icons.woff
    │   │   │           bootstrap-icons.woff2
    │   │   │
    │   │   ├───glightbox
    │   │   │   ├───css
    │   │   │   │       glightbox.css
    │   │   │   │       glightbox.min.css
    │   │   │   │
    │   │   │   └───js
    │   │   │           glightbox.js
    │   │   │           glightbox.min.js
    │   │   │
    │   │   ├───imagesloaded
    │   │   │       imagesloaded.pkgd.min.js
    │   │   │
    │   │   ├───isotope-layout
    │   │   │       isotope.pkgd.js
    │   │   │       isotope.pkgd.min.js
    │   │   │
    │   │   ├───php-email-form
    │   │   │       validate.js
    │   │   │
    │   │   ├───purecounter
    │   │   │       purecounter_vanilla.js
    │   │   │       purecounter_vanilla.js.map
    │   │   │
    │   │   └───swiper
    │   │           swiper-bundle.min.css
    │   │           swiper-bundle.min.js
    │   │           swiper-bundle.min.js.map
    │   │
    │   └───Videos
    │           video-1.mp4
    │           video-2.mp4
    │           video-3.mp4
    │
    └───forms
            contact.php