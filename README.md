# Bookly Caffee: Bookstore & Café Website

A front-end website for a bookstore café: a landing page, a book details page, a shopping cart and a checkout form.

**Live demo:** [samehranneh.github.io/bookstore-cafe-website](https://samehranneh.github.io/bookstore-cafe-website/)

![Home page](docs/index.png)

## Pages

| Page | What it does |
|---|---|
| `index.html` | Landing page: hero, services, book categories, featured books, blog, reviews, login panel and slide-out cart |
| `book_info.html` | Single book details with add-to-cart |
| `store_cart.html` | Store grid with a working cart: add items, change quantities, remove items, live total |
| `checkout.html` | Billing and payment form |

## Built with

- HTML5 and CSS3, with a separate stylesheet per page
- Bootstrap 5 for layout and components
- Vanilla JavaScript for the navbar toggles, login and cart panels (`js/script.js`) and the cart logic (`js/store.js`)
- Font Awesome icons

## Run locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server
```
