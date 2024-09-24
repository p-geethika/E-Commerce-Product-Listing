# E-commerce Product List Page

## Quick start
- Download the repo
- cd ecommerce-product-list-page
- npm i
- npm run dev
- open URL http://localhost:3000/ in browser


## Scalable Frontend Architecture
Codebase follows Atomic Design Pattern that allows scalable architecture.

```
.
├── README.md
├── package-lock.json
├── package.json
├── src
│   ├── Document.js
│   ├── assets
│   │   └── products
│   │       ├── placeholder.png
│   │       ├── product-1.jpg
│   │       ├── product-2.jpg
│   │       ├── product-3.jpg
│   │       ├── product-4.jpg
│   │       ├── product-5.jpg
│   │       ├── product-6.jpg
│   │       ├── product-7.jpg
│   │       └── product-8.jpg
│   ├── client.js
│   ├── components
│   │   ├── atoms
│   │   │   ├── Dropdown
│   │   │   │   └── Dropdown.js
│   │   │   ├── Image
│   │   │   │   └── Image.js
│   │   │   ├── Tag
│   │   │   │   └── Tag.js
│   │   │   └── index.js
│   │   ├── molecules
│   │   │   ├── Product
│   │   │   │   ├── Product.js
│   │   │   │   └── Product.style.js
│   │   │   ├── SizeFilter
│   │   │   │   └── SizeFilter.js
│   │   │   └── index.js
│   │   ├── organisms
│   │   │   ├── ProductsHeader
│   │   │   │   ├── ProductsHeader.js
│   │   │   │   └── ProductsHeader.style.js
│   │   │   ├── ProductsList
│   │   │   │   ├── ProductList.style.js
│   │   │   │   └── ProductsList.js
│   │   │   └── index.js
│   │   └── templates
│   │       ├── ListPage.js
│   │       └── ListPage.style.js
│   ├── global
│   │   ├── config.js
│   │   ├── index.js
│   │   ├── locale.js
│   │   ├── noop.js
│   │   ├── services.js
│   │   └── withStyle.js
│   ├── index.js
│   ├── routes.js
│   ├── server.js
│   └── styles
│       └── theme
│           └── color.js
├── static
│   └── products.json
└── yarn.lock
```