# GeoKal Dev - Personal Portfolio Website

Welcome to the personal portfolio of **George Kalikotsis**, a frontend & backend web developer and designer based in Athens, Greece.

This website showcases George’s web development skills, featured projects, and provides a way for potential clients or collaborators to get in touch.

---

## 🖥️ Live Demo

🔗 [Visit Site](https://geokal21.github.io/)

---

## 📂 Project Structure

GeoKal-Dev/
│
├── images/ # Icons and image assets
├── styles.css # Custom styling
├── index.html # Main HTML page
└── README.md # Project overview (this file)


---

## 🚀 Features

- **Responsive Design** using Bootstrap 5
- **Sticky Header** with smooth navigation
- **About Section** introducing the developer
- **Skills Section** highlighting expertise in frontend, backend, and design
- **Projects Section** with live links and descriptions
- **Contact Form** using [EmailJS](https://www.emailjs.com/) for message submissions
- **Custom Icons** and SVGs for a clean UI
- **Accessible & SEO-Friendly HTML structure**

---

## 🛠️ Tech Stack

- HTML5
- CSS3 / Bootstrap 5.3
- JavaScript
- EmailJS (for handling contact form emails)
- [GitHub Pages](https://pages.github.com/) (for deployment)

---

## 📧 Contact Form Setup (EmailJS)

To get the contact form working:

1. Create an account on [EmailJS](https://www.emailjs.com/)
2. Create an Email Service and a Template
3. Replace the following in `index.html`:

```js
emailjs.init("YOUR_PUBLIC_KEY");
emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', this)

