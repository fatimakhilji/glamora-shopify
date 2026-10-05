# Glamora - Luxury Beauty Shopify Theme (Online Store 2.0)

Ye theme **Glamora Beauty** store ke liye customize ki gayi hai jo 100% Shopify Online Store 2.0 standard ke mutabiq hai. Is mein har section, har block, har snippet, aur separate templates tayyar hain jisko aap direct **GitHub** par upload kar ke **Shopify** se connect kar sakte hain.

---

## 📁 Directory Structure (Theme Architecture)

```
shopify/
├── assets/
│   ├── glamora-base.css          # Core luxury stylesheet (typography, colors, grid, responsive)
│   ├── glamora-cart.js           # Live cart actions, quantities, removal, free shipping tracker
│   ├── glamora-countdown.js      # Flash deals live timer (02 : 14 : 36)
│   ├── glamora-slider.js         # Hero slider banner logic
│   └── glamora-product.js        # Product gallery switcher, swatches, accordions
├── config/
│   ├── settings_schema.json      # Shopify Theme Customizer color & typography options
│   └── settings_data.json        # Pre-configured default color palette & store values
├── layout/
│   └── theme.liquid              # Master layout file
├── locales/
│   └── en.default.json           # Language & translation strings
├── sections/
│   ├── header.liquid             # Logo, search bar, wishlist, account, cart badge
│   ├── hero-slider.liquid        # Hero banner with slide blocks & trust tags
│   ├── category-bubbles.liquid   # Round category icons with blocks
│   ├── promo-banner.liquid       # Flat 30% OFF banner with product showcase
│   ├── flash-deals.liquid        # ⚡ Flash Deals with live countdown & product blocks
│   ├── best-sellers.liquid       # Ranked #1-#4 cards with stars & wishlist
│   ├── just-for-you.liquid       # Personalized grid with '+ Add' pill buttons
│   ├── trust-features.liquid     # 4 bottom value-prop badges
│   ├── sidebar-cart.liquid       # Sticky right-side cart with items, cross-sells, promo, rewards
│   ├── main-product.liquid       # Complete luxury product detail page section
│   ├── product-recommendations.liquid # Related cross-sell products
│   ├── product-reviews.liquid    # Verified buyer reviews & rating breakdown
│   └── footer.liquid             # Newsletter, quick links, policies, payment badges
├── snippets/
│   ├── product-card.liquid       # Modular reusable product card
│   ├── cart-item.liquid          # Reusable cart row with quantity stepper
│   ├── price.liquid              # Formatted price & discount badge
│   ├── icon-search.liquid        # SVG icons
│   ├── icon-cart.liquid
│   ├── icon-heart.liquid
│   ├── icon-user.liquid
│   ├── icon-truck.liquid
│   ├── icon-shield.liquid
│   ├── icon-return.liquid
│   ├── icon-lock.liquid
│   ├── icon-arrow-right.liquid
│   └── icon-close.liquid
├── templates/
│   ├── index.json                # Home Page template (Screenshot layout)
│   ├── product.json              # Dedicated Product Page template
│   └── cart.json                 # Standalone Cart Page template
├── preview.html                  # Double-click to preview both pages instantly in your browser!
└── .gitignore                    # Git ignore file
```

---

## 🚀 GitHub par Upload karne ka Tarika (Step-by-Step)

Apne computer mein terminal ya VS Code terminal open karein aur ye commands run karein:

```bash
# 1. Git initialize karein
git init

# 2. Tamam files stage karein
git add .

# 3. Commit karein
git commit -m "Glamora Luxury Beauty Shopify Theme OS 2.0"

# 4. Main branch set karein
git branch -M main

# 5. Apna GitHub repository link karein (apna username aur repo name replace karein)
git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPO_NAME>.git

# 6. Push karein
git push -u origin main
```

---

## 🛍️ Shopify par Theme Upload karne ke 2 Asaan Tarike

### Tarika 1: Direct Zip File Upload (Sab se Asaan - 1 Click)
1. **Shopify Admin** (`admin.shopify.com`) login karein.
2. Left sidebar se **Online Store** -> **Themes** par jayein.
3. **Add theme** button par click karein aur **Upload zip file** select karein.
4. Folder se **`glamora-shopify-theme.zip`** file select kar ke upload karein.
5. Upload hote hi **Publish** ya **Customize** par click karein!

---

### Tarika 2: GitHub se Connect karna (Auto-Sync)
1. Pehle code ko GitHub par push karein (upar diye gaye commands ke zariye).
2. **Shopify Admin** -> **Online Store** -> **Themes** par jayein.
3. **Add theme** -> **Connect from GitHub** select karein.
4. Apna repository aur `main` branch select kar ke **Connect** par click karein.
5. Shopify theme ko GitHub ke sath link kar dega, aur jab bhi aap GitHub par changes push kareinge, Shopify khud update ho jayega!

---

## 💻 Local Live Preview Dekhne ka Tarika

Agar aap Shopify par upload karne se pehle design check karna chahte hain:
- Simply `preview.html` file par double click karein ya browser mein open karein.
- Top bar mein aap **Home Page** aur **Product Page** ke darmiyan click kar ke switch kar sakte hain.
- Cart quantity increase/decrease karke, countdown timer dekh ke, aur variant swatches test kar sakte hain.

---

## 📦 Products CSV File Import karne ka Tarika

Aapke store ke tamam products (Flash Deals, Best Sellers, Just For You, Cart items, Cross-sells) ki official CSV file **`glamora_products_import.csv`** tayyar hai:

1. **Shopify Admin** (`admin.shopify.com`) login karein.
2. Left sidebar se **Products** par click karein.
3. Top right par **Import** button par click karein.
4. **Add file** par click karein aur **`glamora_products_import.csv`** file choose karein.
5. **Upload and continue** -> Phir **Import products** par click karein.
6. Chand seconds mein tamam 18 products unki images, prices (Rs.), compare prices, variants, aur tags ke sath aapke store mein live ho jayeinge!
