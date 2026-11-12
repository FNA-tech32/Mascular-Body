# Mascular Body — Fitness &amp; Gymnasium Website

![Mascular Body](img/logo.svg)

A modern, high-performance, and fully responsive website template created for **Mascular Body**, a premier fitness club, gymnasium, and bodybuilding training center. Designed with an aggressive athletic aesthetic, dynamic interactive carousels, responsive navigation, and comprehensive membership showcases.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [Website Sections](#-website-sections)
- [Contact Details](#-contact-details)
- [Color Palette &amp; Typography](#-color-palette--typography)
- [Tech Stack &amp; Dependencies](#-tech-stack--dependencies)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Customization Guide](#-customization-guide)
- [License &amp; Credits](#-license--credits)

---

## 🏋️ Overview

**Mascular Body** provides visitors and gym prospects with a seamless, engaging digital experience. Built on modern web standards, it showcases workout programs, world-class training facilities, certified personal trainers, transparent membership pricing plans, and real member testimonials.

---

## ✨ Key Features

- **Responsive Design:** Optimized for desktops, tablets, laptops, and mobile screens.
- **Dynamic Hero Slider:** Fullscreen auto-playing hero banner powered by Slick Carousel with bold call-to-action buttons.
- **Interactive Video Modal:** Lightbox video integration powered by VenoBox for facility tour videos.
- **Animated Milestone Counters:** Real-time animated statistic counters for gym members, classes, and awards.
- **Mobile MeanMenu:** Smooth touch-friendly mobile drawer menu.
- **Multi-Channel Contact Integration:** Primary and alternative physical addresses, phone lines, and email addresses with direct `tel:` and `mailto:` action links.
- **Optimized SEO Metadata:** Descriptive titles, semantic HTML5 headings, meta keywords, and open-graph ready tags.

---

## 📑 Website Sections

1. **Header &amp; Navigation (`#navigation`):**
   - Distinctive angled brand badge displaying the **Mascular Body** SVG emblem.
   - Smooth anchor navigation linking to Home, About Us, Plans, Team, Gallery, Testimonials, and Contact.

2. **Hero Carousel (`#slider-area`):**
   - Three high-impact slides highlighting training motivation, power building, and personal goals.
   - Direct CTA links to membership plans and gym overview.

3. **About Section (`#about-area`):**
   - Club mission statement, training philosophy, and popup facility walkthrough video.

4. **Gallery Showcase (`#gallery-area`):**
   - Grid presentation of state-of-the-art workout areas, free weights, and cardio equipment.

5. **Trainers &amp; Coaches (`#team-area`):**
   - Carousel of certified fitness coaches, personal trainers, and bodybuilding mentors with social links.

6. **Testimonials (`#testimonial-area`):**
   - Carousel of member transformations, reviews, and client ratings.

7. **Membership Plans (`#membership-area`):**
   - Tiered membership pricing cards (Basic, Standard, Pro/Elite) with included perks.

8. **Milestones &amp; Statistics (`#counter-area`):**
   - Animated statistics tracking active members, workouts completed, and fitness programs.

9. **Class Schedules (`#classes-area`):**
   - Detailed schedule cards for CrossFit, Cardio, Strength Conditioning, and Yoga.

10. **Partner / Sponsor Brands (`#client-area`):**
    - Sleek continuous carousel of affiliate fitness brands and nutrition partners.

11. **Footer &amp; Contact Hub (`#footer-area`):**
    - Centered brand emblem.
    - Weekly operating schedule (Mon–Sat: 5:00 AM – 11:00 PM, Sunday: Closed).
    - Latest gym updates and announcements feed.
    - Photo stream grid.
    - Primary and alternative contact details with interactive links.
    - Social media icon handles (Facebook, Twitter, LinkedIn, Instagram, Behance).
    - Copyright and rights management statement.

---

## 📞 Contact Details

The website is configured with comprehensive primary and alternative contact channels:

| Channel | Primary Detail | Alternative Detail |
| :--- | :--- | :--- |
| **Location** | 742 Fitness Blvd, Suite 100, New York, NY 10001 | 88 Muscle Street, Brooklyn, NY 11201 |
| **Phone** | [+1 (800) 555-0199](tel:+18005550199) | [+1 (555) 345-6789](tel:+15553456789) |
| **Email** | [info@mascularbody.com](mailto:info@mascularbody.com) | [support@mascularbody.com](mailto:support@mascularbody.com) |
| **Hours** | Mon - Sat: 5:00 AM - 11:00 PM | Sun &amp; Holidays: Closed |

---

## 🎨 Color Palette &amp; Typography

### Brand Colors
- **Gym Accent Red:** `#e23e38` — Calls to action, accents, hover highlights, active borders
- **Dark Theme Background:** `#242424` / `#1f1f1f` — Brand emblem badge and section backgrounds
- **Charcoal Text:** `#353535` — Section titles and dark typography
- **Light Text &amp; Contrast:** `#ffffff` / `#f1f1f1` — Headings on dark overlays and banners

### Typography
- **Headings (`h1` - `h6`):** `'Oswald', sans-serif` (Bold, athletic display font)
- **Body Text (`p`, `span`, `li`):** `'Open Sans', sans-serif` (Clean, legible sans-serif)

---

## 🛠️ Tech Stack &amp; Dependencies

| Layer | Technology |
| :--- | :--- |
| **Markup** | HTML5 Semantic Architecture |
| **Styling** | Vanilla CSS3, [Bootstrap 4](https://getbootstrap.com/), Custom responsive rules |
| **Icons** | [Font Awesome](https://fontawesome.com/), Flaticon, Themify Icons |
| **Interactivity** | jQuery v1.12.4, Modernizr v3.6.0, Popper.js |
| **Sliders / Carousels** | [Slick Carousel](https://kenwheeler.github.io/slick/) |
| **Lightbox / Video** | [VenoBox](https://veno.es/venobox/) |
| **Counters &amp; Scroll** | Waypoints.js &amp; CounterUp.js |
| **Mobile Menu** | jQuery MeanMenu |

---

## 📂 Project Structure

```text
Mascular-Body/
├── css/
│   ├── bootstrap.min.css    # Bootstrap 4 grid & base framework
│   ├── default.css          # Common base resets and utilities
│   ├── font-awesome.min.css # Font Awesome icon library
│   ├── meanmenu.css         # Mobile responsive navigation styling
│   ├── responsive.css       # Breakpoint media queries
│   ├── slick.css            # Carousel slide styles
│   ├── style.css            # Core custom site theme and styling
│   ├── themify-icons.css    # Themify icon set
│   └── venobox.css          # Lightbox video modal styles
├── fonts/                   # Flaticon and web font files
├── img/
│   ├── logo.svg             # Mascular Body vector logo emblem
│   ├── logo.png             # Original raster logo asset
│   ├── area-img.png         # Section divider graphical ornament
│   ├── counter-bg.jpg       # Counter section parallax background
│   ├── slider1.jpg          # Hero slider background 1
│   ├── slider2.jpg          # Hero slider background 2
│   ├── video.jpg            # Video preview banner
│   ├── footer/              # Footer thumbnail gallery
│   ├── gallery/             # Gym gallery photos
│   ├── membership/          # Membership tier graphics
│   ├── sister-concern/      # Partner & client logos
│   ├── team/                # Fitness trainer photos
│   └── testimonial/         # Member testimonial avatars
├── js/
│   ├── bootstrap.min.js     # Bootstrap components
│   ├── jquery.counterup.min.js # Statistics counter animation
│   ├── jquery.meanmenu.min.js  # Mobile navigation drawer
│   ├── main.js              # Custom slider and plugin initializations
│   ├── plugins.js           # Console safeguards and helpers
│   ├── popper.min.js        # Tooltip/popover positioning
│   ├── slick.min.js         # Carousel slider library
│   ├── vendor/              # jQuery 1.12.4 & Modernizr
│   ├── venobox.min.js       # Video lightbox modal plugin
│   └── waypoint.js          # Scroll trigger listener
├── index.html               # Main landing page
└── README.md                # Project documentation
```

---

## 🚀 Getting Started

This is a static HTML/CSS/JavaScript web application requiring no complex build setup or compilation step.

### Option 1: Direct File Launch
Simply double-click [`index.html`](index.html) or open it with your favorite browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local HTTP Server (Recommended)
Using a lightweight local server ensures all local assets, fonts, and video links load smoothly without cross-origin file restrictions.

**Using Node.js (`npx`):**
```bash
npx serve .
```

**Using Python 3:**
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

**Using VS Code Live Server:**
Right-click on `index.html` inside VS Code and choose **"Open with Live Server"**.

---

## ⚙️ Customization Guide

### 1. Updating Brand Name &amp; Logo
- The primary brand mark is in [`img/logo.svg`](img/logo.svg). You can edit colors, tagline, or typography directly inside the SVG.
- In [`index.html`](index.html), search for `Mascular Body` to adjust titles, alt tags, and banner headings.

### 2. Updating Contact Information
Navigate to the footer section in [`index.html`](index.html) under `<ul class="contact">`:
```html
<ul class="contact">
  <li>
    <i class="fa fa-map-marker"></i>
    <span><strong>Primary Location:</strong> 742 Fitness Blvd...</span>
  </li>
  <li>
    <i class="fa fa-phone"></i>
    <span><a href="tel:+18005550199">+1 (800) 555-0199</a></span>
  </li>
  <li>
    <i class="fa fa-envelope-o"></i>
    <span><a href="mailto:info@mascularbody.com">info@mascularbody.com</a></span>
  </li>
</ul>
```

### 3. Modifying Carousel Timings
Open [`js/main.js`](js/main.js) to configure autoplay speed, dots, arrows, or slide counts for any Slick instance:
```javascript
$('.slider-active').slick({
  infinite: true,
  slidesToShow: 1,
  slidesToScroll: 1,
  arrows: false,
  dots: true,
  autoplay: true,
  autoplaySpeed: 4000
});
```

---

## 📄 License &amp; Credits

- **Template Design:** Customized and branded for **Mascular Body**.
- **Images:** Royalty-free fitness photography assets for demonstration purposes.
- **Fonts:** [Google Fonts](https://fonts.google.com/) (Oswald &amp; Open Sans).
