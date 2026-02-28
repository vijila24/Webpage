# ☕ Coffee Shop Website

A beautiful, fully functional single-page coffee shop website with menu ordering and Amazon ingredient links.

---

## 📁 Project Structure

```
shop/
├── index.html       ← Complete website (single file, no dependencies)
└── README.md        ← This file
```

> **Note:** The logo is embedded directly inside `index.html` as Base64 — no separate image file needed.

---

## 🌟 Features

### 🏠 Home / Hero Section
- Animated logo with spinning golden ring
- "Order Now" button linking to menu
- Smooth scroll navigation

### 📖 Our Story Section
- Coffee shop background and history
- Stats: 12+ Years, 30+ Origins, 50K+ Happy Guests

### ☕ Menu Section (15 Items)
- Filter tabs: All / Hot Drinks / Cold Drinks / Specials / Food
- Click any menu card → Detail panel opens

### 🛒 Item Detail Panel
- Full item description
- Size selector (Small / Regular / Large)
- Extras selector (Sugar / Syrup / Flavour)
- Quantity +/− counter with live price update
- **ADD TO CART** button

### 🛍️ Cart Sidebar
- All added items with size and extras
- Remove individual items
- **Amazon ingredient links** for each cart item
- Coffee essentials banner (Amazon.in)
- Live total price
- **PLACE ORDER** → success popup with order number

### 📍 Visit Us Section
- Address, opening hours, contact info
- Map placeholder

### ✅ Order Success Popup
- Unique order number generated
- Order summary shown

---

## 🍽️ Menu Items

### ☕ Hot Drinks
| Item | Price |
|------|-------|
| Espresso | ₹120 |
| Cappuccino | ₹150 |
| Flat White | ₹160 |
| Latte | ₹155 |
| Chai Latte | ₹140 |
| Americano | ₹130 |

### 🧊 Cold Drinks
| Item | Price |
|------|-------|
| Cold Brew | ₹170 |
| Iced Latte | ₹165 |
| Matcha Latte | ₹180 |
| Frappe | ₹190 |

### ✨ Specials
| Item | Price |
|------|-------|
| Affogato | ₹200 |

### 🥐 Food & Bites
| Item | Price |
|------|-------|
| Butter Croissant | ₹80 |
| Banana Bread | ₹90 |
| Avocado Toast | ₹180 |
| Chocolate Muffin | ₹70 |

---

## 🛒 Amazon Ingredient Links

Each cart item shows Amazon.in links to buy its ingredients at home:

| Menu Item | Amazon Links |
|-----------|-------------|
| Espresso | Espresso Beans, Espresso Machine, Coffee Grinder |
| Cappuccino | Coffee Beans, Milk Frother, Cappuccino Cups |
| Flat White | Ristretto Pods, Milk Frother, Coffee Beans |
| Latte | Latte Coffee Beans, Milk Steamer, Latte Glasses |
| Chai Latte | Masala Chai Tea, Chai Spice Mix, Milk Frother |
| Americano | Arabica Beans, Pour Over Kettle, Coffee Mug |
| Cold Brew | Cold Brew Kit, Coarse Ground Coffee, Cold Brew Jar |
| Iced Latte | Espresso Beans, Ice Cube Tray, Iced Coffee Cups |
| Matcha Latte | Ceremonial Matcha, Matcha Whisk, Oat Milk |
| Frappe | Instant Coffee, Vanilla Ice Cream, Blender |
| Affogato | Espresso Beans, Vanilla Gelato, Dessert Glasses |
| Croissant | Croissant Dough Mix, Butter, Almond Paste |
| Banana Bread | Bread Mix, Walnuts, Cinnamon Powder |
| Avocado Toast | Sourdough Bread, Avocado, Chili Flakes |
| Chocolate Muffin | Dark Chocolate Chips, Muffin Mix, Muffin Tray |

---

## 🎨 Design

| Property | Value |
|----------|-------|
| Theme | Dark Espresso / Luxury |
| Primary Color | `#1a0f0a` (Espresso) |
| Accent Color | `#d4a853` (Gold) |
| Fonts | Playfair Display, Cormorant Garamond, Cinzel |
| Style | Artisan / Refined / Premium |

---

## 🛠️ How to Customize

### Change Shop Name
Search for `COFFEE SHOP` in `index.html` and replace with your shop name.

### Change Prices
Search for the item name (e.g. `"espresso"`) in the `ITEMS` object in the `<script>` section and update the `price` value.

### Change Address / Hours / Phone
Find the **Visit Us** section in the HTML and update the text directly.

### Change Colors
Update the CSS variables at the top of the `<style>` section:
```css
:root {
  --bg: #1a0f0a;      /* Background */
  --gold: #d4a853;    /* Accent color */
  --cream: #f5ead8;   /* Text color */
}
```

### Add New Menu Items
Add a new entry to the `ITEMS` object and the `AMAZON` object in the script section, then add a new card in the `#menuGrid` div.

---

## 📱 Responsive Design

| Screen | Layout |
|--------|--------|
| Desktop | 3-column menu grid, side-by-side hero |
| Tablet | 2-column menu grid |
| Mobile | Single column, hidden hero logo |

---

## 📦 Technologies Used

- **HTML5** — Structure
- **CSS3** — Styling, animations, grid layout
- **Vanilla JavaScript** — Cart logic, filtering, modals
- **Google Fonts** — Playfair Display, Cormorant Garamond, Cinzel
- **Amazon.in** — Ingredient shopping links

---

## 📞 Contact Info (Update These)

| Field | Value |
|-------|-------|
| Address | 12 Brew Lane, Coffee Street |
| Phone | +91 98765 43210 |
| Email | hello@coffeeshop.in |
| Hours | Mon–Fri 7AM–10PM, Sat–Sun 8AM–11PM |

---

*Built with ☕ and love · Coffee Shop © 2026*
