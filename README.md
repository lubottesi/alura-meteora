# Meteora

A responsive fashion e-commerce landing page - image carousel, category browsing, featured products, a store-perks section (Pix discount, free returns, sustainability) and a newsletter signup.

Built while practicing Bootstrap at Alura.

## Stack

- HTML5
- [Bootstrap](https://getbootstrap.com/) 5.3 (grid, navbar, carousel, cards) via CDN
- [Bootstrap Icons](https://icons.getbootstrap.com/) via CDN
- Custom CSS (`estilos.css`)

Each image (banners, categories, products) has separate mobile/tablet/desktop versions swapped in via Bootstrap's responsive display utilities.

## Running locally

No build step — open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then go to http://localhost:8000.

## Structure

```
index.html
estilos.css
assets/
  Mobile/
  Tablet/
  Desktop/
```
