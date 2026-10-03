# MEIHUA TEA

Soft romantic gothic tea-boutique e-commerce prototype using **HTML5 + CSS3 + Vanilla JavaScript only**.

## Run
1. Open this folder in VS Code.
2. Open `index.html` with Live Server, or open the file directly in a modern browser.
3. No PHP, MySQL, Node, React, Vue, Bootstrap, Tailwind, or build system is needed.

## Structure
```text
Meihua-Tea/
├── index.html
├── style.css
├── app.js
├── README.md
└── assets/
    ├── images/
    │   ├── meihua-tea-collection.png
    │   └── default-avatar.svg
    ├── audio/
    │   ├── morning-tea.mp3
    │   ├── rainy-afternoon.mp3
    │   ├── gothic-rose.wav
    │   ├── reading-tea.wav
    │   ├── candlelight.wav
    │   └── midnight-tea.wav
    └── icons/
```

## Included functionality
- Home navigation and feature cards
- Tea Shop search/filter/sort
- Product detail + quantity
- Wishlist with localStorage
- Cart with quantity/remove/total
- Register/login/logout simulation
- Editable profile + profile photo upload
- Tea Finder scoring quiz with varying results
- Custom Tea Blend + save + add to cart
- Tea Radio with real HTML audio controls, playlist switching, previous/next, progress, volume
- Reviews and ratings saved to localStorage
- Checkout validation + simulated order confirmation
- Order history
- Responsive desktop/tablet/mobile layout

## Prototype note
Authentication and checkout are intentionally simulations for a school project. User data is stored in the browser's localStorage and is **not secure production authentication**. No real payment is processed.

## Tea Radio audio
The six WAV files are short original test ambience tones so the player can be tested without commercial music. Replace them with your own royalty-free audio if desired, and update the six file paths in `app.js`.

## localStorage keys
`meihua_users`, `meihua_current_user`, `meihua_cart`, `meihua_wishlist`, `meihua_blends`, `meihua_reviews`, `meihua_orders`, `meihua_profile`, `meihua_finder`.

## Reset demo
Open DevTools Console and run:
```js
localStorage.clear(); location.reload();
```

### Tea Shop additions
The Tea Shop now includes eight pure "Only" variants: Only Green Tea, Only Black Tea, Only White Tea, Only Rose Tea, Only Matcha Tea, Only Rooibos Tea, Only Herbal Tea, and Only Oolong Tea.
