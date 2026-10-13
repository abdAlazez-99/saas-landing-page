# Whitepace SaaS Landing Page - Design System & CSS Guide

## 1. Typography
- **Font Family:** `Inter` (Google Fonts)
- **Import Link:** `<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">`
- **Hero Heading (H1):** `64px` | Line-height: `76px` | Weight: `700`
- **Section Title (H2):** `52px` | Line-height: `60px` | Weight: `700`
- **Subheading (H3):** `24px` - `30px` | Weight: `600`
- **Body Text:** `18px` | Line-height: `30px` | Weight: `400`
- **Buttons / Links:** `16px` | Weight: `500`

## 2. Color Palette (CSS Variables)
```css
:root {
  --primary-deep-blue: #043873;
  --primary-bright-blue: #4F9CF9;
  --accent-yellow: #FFE492;
  --text-dark: #212529;
  --text-muted: #5B5B5B;
  --bg-light: #F4F5F7;
  --bg-white: #FFFFFF;
  --border-color: #DFE3E8;
}
```

## 3. Layout & Spacing
- **Container Max-Width:** `1200px` to `1320px` (`margin: 0 auto`, `padding: 0 32px`)
- **Navbar Height:** `92px`
- **Section Vertical Padding:** Desktop `120px` | Mobile `60px`
- **Border Radius:** Buttons/Cards `8px - 12px` | Images/Mockups `16px`

## 4. Image & Mockup Specs
- **Hero Main Image (Right):** ~`824px × 549px` (~`3:2` ratio)
- **Feature Cards Images:** ~`600px × 450px`
- **Fallback:** Use high-quality Unsplash placeholders.

## 5. Quick Code Blueprint (CSS/HTML)
- **Structure:** Use semantic tags (`<header>`, `<section>`, `<footer>`).
- **Navbar & Hero:** Use **Flexbox** (`display: flex; align-items: center; justify-content: space-between;`).
- **Feature Grids:** Use **CSS Grid** (`grid-template-columns: repeat(3, 1fr);`).
- **Hover Effects:** Add `transition: all 0.3s ease-in-out;` and `transform: translateY(-5px);` for cards.