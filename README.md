<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,55:1c1d20,100:0c63e7&height=170&section=header&text=Furniture%20Store&fontSize=48&fontColor=fcfaf8&fontAlignY=38&desc=E-commerce%20in%20vanilla%20JavaScript&descAlignY=60&descSize=16" width="100%" alt="Furniture Store" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

## ✨ About

A furniture storefront built with **plain HTML, CSS and JavaScript**, with no frameworks. Products load from a JSON file, and the shopping cart is saved in `localStorage` so it's still there after a reload.

## 🔋 Features

- 🛋️ Product grid loaded with `fetch()` from `products.json`
- 🛒 Slide-in cart: add items, change quantities, remove items, clear the cart
- 💰 Live cart total and item count
- 💾 Cart and products saved to `localStorage`
- 📱 Responsive layout

## 🛠️ Tech stack

HTML5 · CSS3 · JavaScript (ES6 classes, Fetch API, localStorage)

## 🚀 Getting started

No build step. Because products load with `fetch()`, serve the folder with a local server:

```bash
git clone https://github.com/ahmadtahir1399/vanilla-js-ecommerce-store.git
cd vanilla-js-ecommerce-store
npx serve .
```

Or open it with the VS Code **Live Server** extension.

## 📁 Project structure

```
index.html      layout: navbar, banner, products, cart
app.js          Product / UI / Storage classes
products.json   product catalog
style.css, main.css
images/
```

## 👤 Author

**Muhammad Ahmad Tahir** · [Portfolio](https://ahmadverse.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/ahmad-ai-fullstack-engineer/) · [GitHub](https://github.com/ahmadtahir1399)
