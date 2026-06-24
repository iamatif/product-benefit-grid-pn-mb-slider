---

# 🎡 Product Benefits Slider Section

A specialized feature/benefit slider designed for Product and Collection pages. It features a unique "Hybrid Content" logic that prioritizes manual input but falls back to Metafields automatically.

## 🚀 Slider Features

- **Hybrid Content Logic:** 
    1. Checks for **Manual Block Settings** (Priority 1).
    2. Falls back to **Product Metafields** (Priority 2).
    3. Falls back to **Collection Metafields** (Priority 3).
- **Tactical Design:**
    - Black and Neon (`#D5FE3E`) color scheme.
    - Interactive "Highlight" state for featured cards.
    - Smooth SVG icon support with stroke-animation on hover.
- **Dynamic Swiper Integration:**
    - Mobile: 1.2 slides (peek effect to encourage scrolling).
    - Tablet: 2 slides.
    - Desktop: 4 slides.
- **Metafield Integration:** Specifically mapped for up to 4 benefit boxes.

## 🛠️ Metafields Structure

To use the automated fallback feature, create the following metafields (Namespace: `custom`):

| Metafield Key | Type | Description |
| :--- | :--- | :--- |
| `benefit_1st_box_heading` | Single line text | Heading for the 1st card |
| `benefit_1st_box_description` | Multi-line text / Rich text | Description for the 1st card |
| `benefit_2nd_box_heading` | Single line text | Heading for the 2nd card |
| `benefit_2nd_box_description` | Multi-line text / Rich text | Description for the 2nd card |
| *(Repeat for 3rd and 4th boxes)* | | |

## 📂 Usage Instructions

1. **Manual Entry:** Add a "Feature Card" block and type your title/text. This will override everything else.
2. **Metafield Entry:** Leave the "Title" field in the block empty. The section will automatically look for the metafields you've added to that specific Product or Collection.
3. **SVG Icons:** Paste any raw SVG code into the "SVG Code" box for sharp, scalable icons.

## 🎨 Styling Details

- **Transition:** Uses `cubic-bezier(0.25, 1, 0.5, 1)` for premium feel.
- **Hover Effect:** Cards lift up (-10px) and swap colors between black and neon.
- **Fonts:** Optimized for `Quantico` (Headings) and standard sans-serif (Body).

## ⚙️ Schema Options
- **Adjustable Spacing:** Independent padding controls for Mobile and Desktop.
- **Highlight Toggle:** Specific checkbox per block to make a card stand out (Neon background by default).