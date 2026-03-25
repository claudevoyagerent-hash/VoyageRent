# Surprice x Voyage — Brand Usage Sheet

## Co-Brand Identity

**Franchise:** Surprice Car Rental (International)
**Partner:** Voyage Rent (Local Operator)
**Co-Brand Model:** Surprice x Voyage — Official Franchise Point

---

## Logo Variants

### Variant A — Signage (Primary)
**File:** `variants/variant-a-signage.svg`
**Use:** Main brand lockup. Outdoor signage, fascia panels, desk signs, digital headers.
**Style:** Clean, strict, no effects. Premium airport franchise look.
**Background:** Near-black `#0C0C0F`

### Variant B — Glow (Premium)
**File:** `variants/variant-b-glow.svg`
**Use:** Hero banners, presentations, premium printed materials, backlit signs.
**Style:** Subtle ambient glow between brands. Red-to-orange gradient on divider.
**Background:** Near-black with soft ambient radial glows.

### Variant C — Merch (Simplified)
**File:** `variants/variant-c-merch.svg`
**Use:** T-shirts, caps, uniforms, pens, small merch items.
**Style:** Text-only, no icon. Compact single-line layout.
**Background:** Black fabric or dark surfaces.

### Additional Variants

| File | Use |
|------|-----|
| `variant-a-white-bg.svg` | Print on white paper, light backgrounds |
| `variant-compact.svg` | Business cards, email signatures, app badges |
| `variant-stacked-vertical.svg` | Wall panels, desk fronts, tall/square spaces |
| `variant-car-sticker-rear.svg` | Vinyl sticker for vehicle rear (die-cut) |

---

## Color Palette

### On Dark Background (Primary)

| Element | Color | Hex |
|---------|-------|-----|
| Background | Near Black | `#0C0C0F` |
| "Sur" | Surprice Red | `#C8102E` |
| "price" | White | `#FFFFFF` |
| VOYAGE | Franchise Orange | `#F47920` |
| RENT | White 65% | `rgba(255,255,255,0.65)` |
| Taglines | White 40-55% | `rgba(255,255,255,0.45)` |
| Divider | White 12% or gradient | See specs |
| Icon top | Red gradient | `#E8312A` → `#8B1A1A` |
| Icon bottom | Navy gradient | `#1F3460` → `#12213D` |

### On White Background

| Element | Color | Hex |
|---------|-------|-----|
| "Sur" | Surprice Red | `#C8102E` |
| "price" | Surprice Navy | `#1B2A4A` |
| VOYAGE | Dark Orange | `#E06B10` |
| RENT | Navy 60% | `rgba(27,42,74,0.60)` |
| Divider | Navy 12% | `rgba(27,42,74,0.12)` |

---

## File Inventory

### SVG (Vector — for print/fabrication)
```
variants/
├── variant-a-signage.svg          ← MAIN LOCKUP
├── variant-a-white-bg.svg         ← Light background version
├── variant-b-glow.svg             ← Premium/presentation
├── variant-c-merch.svg            ← T-shirt/merch
├── variant-compact.svg            ← Small applications
├── variant-stacked-vertical.svg   ← Vertical/square
└── variant-car-sticker-rear.svg   ← Vehicle sticker
```

### PNG (Raster — for digital)
```
png/
├── variant-a-signage-{1x,2x,4x}.png
├── variant-a-white-bg-{1x,2x,4x}.png
├── variant-b-glow-{1x,2x,4x}.png
├── variant-c-merch-{1x,2x,4x}.png
├── variant-compact-{1x,2x,4x}.png
├── variant-stacked-vertical-{1x,2x,4x}.png
├── variant-car-sticker-rear-{1x,2x,4x}.png
├── mockup-outdoor-signage.png
├── mockup-tshirt.png
├── mockup-rental-desk.png
└── mockup-wall-sign.png
```

### Mockups
```
mockups/
├── mockup-outdoor-signage.svg     ← Building fascia
├── mockup-tshirt.svg              ← Black t-shirt chest
├── mockup-rental-desk.svg         ← Airport/rental counter
└── mockup-wall-sign.svg           ← Interior wall panel
```

### Print Specifications
```
print-specs/
└── PRINT_READY_SPECS.md           ← Full print guide
```

---

## Application Quick Reference

| Application | Variant | Recommended Size | Material |
|-------------|---------|-----------------|----------|
| Office signage (outdoor) | A-signage | 250 x 70 cm | Dibond + LED backlight |
| Fascia panel | A-signage | 300 x 85 cm | ACM + UV print |
| Airport/rental desk | A-signage | 80 x 22 cm | Acrylic, gloss |
| Wall sign (interior) | Stacked-vertical | 80 x 100 cm | Acrylic + standoffs |
| T-shirt (chest) | C-merch | 28 x 7 cm | DTG on black |
| T-shirt (back) | C-merch | 32 x 8 cm | DTG on black |
| Car sticker (rear) | Car-sticker-rear | 70 x 18 cm | 3M vinyl + UV laminate |
| Business card | Compact | Full width | Offset print |
| Email signature | Compact PNG 1x | 400px wide | Digital |
| Social media header | A-signage PNG 2x | 1500 x 500px | Digital |
| Social media avatar | Stacked PNG crop | 400 x 400px | Digital |

---

## Rules

### DO
- Always use provided files — do not recreate
- Maintain the exact proportions
- Use on approved backgrounds only (near-black or white)
- Keep the safe zone (10% of height on all sides)
- Use SVG for all physical print/fabrication

### DO NOT
- Rotate, skew, or distort
- Change colors or fonts
- Add shadows, outlines, or effects not in the original
- Place on colored, gradient, or photo backgrounds
- Use the Surprice icon without the full lockup
- Separate "Surprice" from "VOYAGE" — always use together
- Scale below minimum sizes (see print specs)

---

## Font Installation

For SVG files to render correctly, install **Nunito** font:
https://fonts.google.com/specimen/Nunito

When sending to print shops, either:
1. Ensure they have Nunito installed, OR
2. Convert text to outlines/paths in Illustrator/Inkscape before sending
