# Stitches by Tia - Handmade Crochet Business Website

A mobile-first showcase website for **Stitches by Tia**, a Mumbai-based handmade crochet brand. The site presents curated crochet products, highlights custom-order availability, and provides direct ordering/contact paths through Instagram and WhatsApp.

## Features

- 100% handmade crochet products
- Custom orders available
- Product showcase with carousels for:
  - **Keychains & Charms**
  - **Plushies & Stuffed Toys**
- Lightbox image viewer for product detail preview
- Mobile-responsive layout optimized for **max-width: 430px**
- Direct contact via Instagram and WhatsApp

## Project Structure

- `index.html` - main HTML document with all page content and embedded base64 product images
- `styles.css` - external stylesheet containing all design, layout, animation, and responsive rules
- Base64 embedded images are used directly inside `index.html` for product/media content

## Technologies Used

- **HTML5**
- **CSS3**
  - CSS custom properties (variables)
  - Flexbox
  - Grid
  - Transitions/animations
- **Google Fonts**
  - Cormorant Garamond
  - DM Sans
- No framework/build pipeline required
- No JavaScript required for static display (interactive enhancements are lightweight and embedded in the page)

## Color Palette (CSS Variables)

Defined in `:root` inside `styles.css`:

- `--bg: #100c10` - primary dark purple/brown background
- `--bg2: #1a1520` - secondary dark section background
- `--pink: #f472a8` - primary pink accent (CTAs/highlights)
- `--pink-lt: #f9aace` - softer pink accent for decorative text
- `--pink-pale: #fce8f3` - pale pink background accent
- `--cream: #fdf4f0` - warm neutral accent
- `--ink: #1a0a08` - primary dark text
- `--ink-mid: #7a5a54` - medium text tone
- `--ink-faint: #b89890` - subtle text/meta tone
- `--white: #ffffff` and `--card: #ffffff` - card/surface text and backgrounds

## How to Use

1. Clone or download this repository.
2. Open `index.html` in any modern browser.

### Browser Compatibility

- Recommended: latest Chrome, Edge, Safari, and Firefox
- Uses modern CSS features (custom properties, flexbox, grid), supported by all current evergreen browsers

### Responsive Behavior

- Mobile-first design
- Main page container capped at `430px` width for phone-focused presentation

## Product Categories

- **Keychains & Charms**
- **Plushies & Stuffed Toys**

All products are available for inquiries/orders through Instagram DM or WhatsApp.

## Contact Information

- **Instagram:** [@stitches.bytia](https://instagram.com/stitches.bytia)
- **WhatsApp:** link available directly on the page CTA
- **Location:** Mumbai, India

## Design Notes

- Mobile-optimized visual system (430px max-width layout)
- Dark theme foundation with pink accents
- Smooth hover and transition effects
- Lightbox interaction for enlarged product image viewing

## File Size & Performance Notes

- Product images are embedded as base64 in `index.html` for single-file portability of media assets
- A single external stylesheet (`styles.css`) keeps styling centralized and efficient to maintain
