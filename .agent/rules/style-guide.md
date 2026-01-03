# Saram Consulting UI Style Guide

This document captures the design requirements and "look and feel" of the Saram Consulting website, which was 100% vibe coded using Antigravity. Use these guidelines to maintain consistency in future updates.

## Design Philosophy

- **Minimalist/Academic**: The site should feel clean, focused, and professional. Use "cream space" (off-white background) to provide breathing room.
- **Text-First**: Prioritize high-quality typography over heavy imagery or complex components.
- **Subtle Interactivity**: Avoid loud buttons or animations. Use subtle underlines and opacity shifts for interactive elements.

## Color Palette

| Element                | Hex / RGBA            | Role                              |
| :--------------------- | :-------------------- | :-------------------------------- |
| **Background**         | `#f5f4ef`             | Warm off-white / Cream background |
| **Primary Text**       | `#000000`             | All body and heading text         |
| **Underline (Soft)**   | `rgba(0, 0, 0, 0.15)` | Default link/interaction state    |
| **Underline (Active)** | `rgba(0, 0, 0, 0.4)`  | Hover or active link state        |

## Typography

The site uses two primary font families from Google Fonts:

1. **Serif**: `Playfair Display` (ital, wght@0,400..900; 1,400..900)
   - **Usage**: Logo, Footer, Blog Post Titles (H1).
   - **Size**: Logo (30px), Post Titles (32px / 24px on mobile).
2. **Monospace**: `Roboto Mono` (ital, wght@0,100..700; 1,100..700)
   - **Usage**: Body text, Navigation, Section Titles, Lists.
   - **Size**: 14px (Base size).

## Layout & Spacing

- **Stability**: Force a vertical scrollbar using `html { overflow-y: scroll; }` to prevent horizontal layout shifts when moving between pages of different lengths.
- **Container**: Site-wide max-width `900px`. Centered.
- **Padding**: `60px 40px` for desktop, `40px 20px` for mobile.
- **Header**: Flexbox with `justify-content: flex-start` and `gap: 60px` to keep the navigation close to the logo.
- **Section Spacing**:
  - `margin-bottom: 40px` (Main Header, standardized site-wide).
  - `gap: 24px` (Main content sections).
  - `margin-bottom: 8px` (Paragraphs).
  - `gap: 4px` (List items).
- **Line Height**: `1.6` for optimal readability.

## UI Components

### 1. Logo

- Serif font, 30px, plain text linking to `/`.

### 2. Navigation

- Monospaced, underlined with soft opacity. `32px` gap between links.
- **Sitemap**: Home (`/`), About (`/about.html`), Posts (`/posts`).

### 3. Lists (Services/Posts)

- Uses a custom dash prefix (`— `) with `0.6` opacity.
- List items are plain text or underlined links; never buttons.

### 4. Links

- Underline offset: `8px` (Nav) or `4px` (Body/List).
- Smooth transition: `0.2s ease` for text-decoration-color.

### 5. Signature Footer

- A subtle line at the bottom: `100% vibe coded using Antigravity`.
- Font-size: `10px`, Opacity: `0.4`, Margin-top: `80px`.

## Social Media & Imagery

- **OG Images**: High-end conceptual abstractions. Minimalist palette matching the `#f5f4ef` background.
- **Theme**: Intersection of Life Sciences (DNA/Biological) and Artificial Intelligence (Neural/Data).
- **Meta Tags**: Always include `og:title`, `og:description`, and `og:image` with relative paths where possible.

---

**Maintained by Antigravity**
