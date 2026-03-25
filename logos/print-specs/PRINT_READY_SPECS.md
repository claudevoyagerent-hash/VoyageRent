# Surprice x Voyage — Print-Ready Specifications

## Color System

### Primary Colors

| Color | Hex | RGB | CMYK (approx) | Pantone | Usage |
|-------|-----|-----|----------------|---------|-------|
| Surprice Red | `#C8102E` | 200, 16, 46 | 0, 100, 85, 5 | 186 C | "Sur" text, icon flame |
| Surprice Navy | `#1B2A4A` | 27, 42, 74 | 90, 70, 30, 60 | 289 C | Icon bottom, dark text |
| Voyage Orange | `#F47920` | 244, 121, 32 | 0, 60, 95, 0 | 151 C | "VOYAGE" text |
| Near Black BG | `#0C0C0F` | 12, 12, 15 | 0, 0, 0, 97 | Black 6 C | Primary background |

### Secondary Colors

| Color | Hex | Usage |
|-------|-----|-------|
| White | `#FFFFFF` | "price" text on dark, taglines |
| Dark Orange | `#E06B10` | "VOYAGE" on white backgrounds |
| Light Red | `#E8312A` | Icon highlight, dark bg red |
| Deep Navy | `#12213D` | Icon shadow area |

### Transition Colors (center divider)
- Red to Orange gradient: `#C8102E` → `#E05520` → `#F47920`
- Used only on divider element, never on text

---

## Typography

### Primary Font: Nunito
- Weight: 900 (Black) — brand names
- Weight: 700 (Bold) — "RENT" subtext
- Weight: 600 (SemiBold) — taglines
- Weight: 500 (Medium) — descriptors

**Download:** https://fonts.google.com/specimen/Nunito

### Fallback Stack
`Nunito, Varela Round, Arial Rounded MT Bold, Montserrat, sans-serif`

### Text Specifications

| Element | Size Ratio | Weight | Color (dark bg) | Color (light bg) | Letter-spacing |
|---------|-----------|--------|-----------------|-------------------|---------------|
| "Sur" | 1.0x | 900 | #C8102E | #C8102E | -3px |
| "price" | 1.0x | 900 | #FFFFFF | #1B2A4A | -3px |
| "Empowering mobility" | 0.23x | 600 | white 55% | navy 60% | +2.5px |
| "VOYAGE" | 0.93x | 900 | #F47920 | #E06B10 | +3px |
| "RENT" | 0.29x | 700 | white 65% | navy 60% | +8px |
| "CAR RENTAL PARTNER" | 0.15x | 500 | white 35% | navy 35% | +5px |

---

## Safe Zone / Clear Space

```
Minimum clear space = 10% of total logo height on ALL sides

┌──────────────────────────────────────┐
│          10% clear zone              │
│   ┌──────────────────────────────┐   │
│   │                              │   │
│   │  Surprice  |  VOYAGE         │   │
│   │                              │   │
│   └──────────────────────────────┘   │
│          10% clear zone              │
└──────────────────────────────────────┘
```

- No other logos, text, or graphics within the safe zone
- Background must be uniform within safe zone (no patterns, photos)

---

## Minimum Sizes

| Application | Minimum Width | File Variant |
|-------------|--------------|--------------|
| Business card | 60mm | compact |
| Web / email | 300px | compact |
| Office signage | 80cm | variant-a-signage |
| Outdoor signage | 120cm+ | variant-a-signage |
| Fascia panel | 200cm+ | variant-a-signage |
| Car sticker (rear) | 60cm | car-sticker-rear |
| T-shirt (chest) | 25cm | variant-c-merch |
| T-shirt (back) | 30cm | variant-c-merch |
| Desk sign | 50cm | variant-a-signage |
| Wall interior | 100cm+ | variant-stacked-vertical |

---

## Background Rules

### Preferred: Near-Black (#0C0C0F)
- Primary application for all franchise materials
- Use for: signage, stickers, merch, digital

### Allowed: Pure White (#FFFFFF)
- Use `variant-a-white-bg` files
- "price" becomes navy (#1B2A4A)
- "VOYAGE" becomes darker orange (#E06B10)

### NOT Allowed:
- Colored backgrounds (blue, red, green, etc.)
- Photographs as background
- Gradient backgrounds
- Transparent background without containment box
- Light gray backgrounds (reduces contrast)

---

## Application-Specific Dimensions

### 1. Outdoor Signage (above office)
- **File:** `variant-a-signage.svg`
- **Recommended size:** 250cm x 70cm (horizontal)
- **Material:** Dibond aluminum composite or acrylic with LED backlight
- **Background:** Near-black, matte finish
- **Text:** Vinyl cut or UV print
- **Illumination:** Backlit or front-lit LED, white 5000K

### 2. Fascia Panel (building front)
- **File:** `variant-a-signage.svg` or `variant-stacked-vertical.svg`
- **Recommended size:** 300cm x 85cm (H) or 150cm x 200cm (V)
- **Material:** ACM panel with vinyl wrap or direct UV print
- **Finish:** Matte or semi-gloss lamination

### 3. T-Shirt Print
- **File:** `variant-c-merch.svg`
- **Chest:** 28cm x 7cm
- **Back:** 32cm x 8cm
- **Method:** DTG (Direct to Garment) or screen print
- **Fabric:** Black only (dark garments)
- **For white shirts:** Use variant-a-white-bg (adapt to merch layout)

### 4. Interior Desk / Counter Sign
- **File:** `variant-a-signage.svg`
- **Recommended size:** 80cm x 22cm
- **Material:** Acrylic or forex board
- **Finish:** Gloss lamination for premium look
- **Mount:** L-bracket stand or easel back

### 5. Car Rear Sticker
- **File:** `variant-car-sticker-rear.svg`
- **Recommended size:** 70cm x 18cm
- **Material:** Vinyl (3M or Avery), gloss or matte
- **Application:** Rear bumper or trunk lid
- **Die-cut:** Follow rounded corners (25px radius at scale)
- **Lamination:** UV-resistant clear laminate

### 6. Wall Sign (Interior)
- **File:** `variant-stacked-vertical.svg`
- **Recommended size:** 80cm x 100cm
- **Material:** Foam board, acrylic, or canvas
- **Mount:** French cleat or standoff pins

---

## File Format Reference

| Format | Use Case | Notes |
|--------|----------|-------|
| SVG | Print, signage, fabrication | **Always use for professional print** — infinite scaling |
| PNG 4x | High-quality digital / proofing | 7200x2000px (signage variants) |
| PNG 2x | Web, social media, presentations | 3600x1000px |
| PNG 1x | Email signatures, thumbnails | 1800x500px |

---

## DO NOT

- Rotate the logo
- Change the aspect ratio (stretch/compress)
- Rearrange the elements
- Change the font
- Add drop shadows or outer glow effects
- Place on busy/patterned backgrounds
- Use the Surprice icon without the full lockup
- Modify the color values
- Add borders or outlines to the text
- Change the divider style
