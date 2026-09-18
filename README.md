# Thala 7 – Sneaker Store (CSS Mini Project)

A 4-page sneaker store front-end built with plain HTML and CSS (no frameworks, no Bootstrap). Layout is done entirely with **Flexbox**.

## Pages

| File           | Section                 | Description                                                                    |
| -------------- | ----------------------- | ----------------------------------------------------------------------------- |
| `index.html`   | Landing Page            | Header/navbar, two-column hero section, full-width service overview stats bar |
| `product.html` | Product Display Page    | Breadcrumb, main product image + details panel, scrollable image gallery      |
| `cart.html`    | Shopping Cart Page      | Cart table with quantity steppers & remove, coupon card, order totals         |
| `payment.html` | Checkout / Payment Page | Contact details, payment method tabs (Card/Crypto/Bank), order summary        |


## Notes
- All styling is in a single shared `style.css`, so the header/navbar stays visually consistent across every page.
- **Pure HTML and CSS only — no Bootstrap, no JavaScript.** All layout uses CSS Flexbox.
- Google Fonts (Poppins) and Font Awesome icons are loaded via CDN `<link>` tags (fonts/icons only, not JS frameworks).
- Fully responsive: navbar, hero, product layout, cart, and checkout all reflow for tablet (≤900px) and mobile (≤600px) breakpoints.

## How to run
Open `index.html` directly in a browser.

## Author
Sai Kiran
