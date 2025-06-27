
# Golden Building L.L.C - Technical Services Website

Welcome to the official website repository of **Golden Building L.L.C**, a professional technical services company based in Dubai.

This site includes bilingual support (English and Arabic), a contact form, and a WhatsApp integration. It is hosted using GitHub Pages and fully responsive.

## 🌍 Live Site

👉 [Visit the Website](https://goldenbuilding1986.github.io/goldenbuilding/)

## 📂 Features

- ✅ Bilingual (English + Arabic)
- ✅ Mobile-friendly layout
- ✅ Contact form using Formspree (no backend needed)
- ✅ WhatsApp floating button for quick contact

## 🧰 Technologies Used

- HTML5 & CSS3
- JavaScript for language toggle
- Google Fonts (Cairo)
- GitHub Pages for hosting

## 📬 Contact Form Setup (Formspree)

To activate the contact form:

1. Go to [https://formspree.io](https://formspree.io) and sign up for free.
2. Create a new form, then copy the **Form ID** it gives you (example: `xyz123`).
3. In `index.html`, find the form section and replace:

```html
<form action="https://formspree.io/f/your_form_id" method="POST">
```

With your actual form ID:

```html
<form action="https://formspree.io/f/xyz123" method="POST">
```

4. Save and commit the file.

## 📞 WhatsApp Integration

To use the WhatsApp button, replace the number in the URL:

```html
<a href="https://wa.me/971551234567" target="_blank">💬</a>
```

With your actual WhatsApp number in international format (e.g., `+97150XXXXXXX`).

---

© 2025 Golden Building L.L.C — All rights reserved.
