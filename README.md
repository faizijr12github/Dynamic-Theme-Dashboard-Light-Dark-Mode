# Dynamic Theme Dashboard — Light & Dark Mode (Power BI)

> *A fully functional Light/Dark mode toggle built entirely with native Power BI features — no custom visuals, no code, just smart use of Icon Images with Action.*

---

## Overview

This project demonstrates **advanced UI/UX design principles** in Power BI by implementing a seamless **Light and Dark mode toggle** — a feature typically associated with modern web and mobile applications, now brought natively into a BI report.

Using a combination of **Icon Images with Action**, users can switch between visual themes instantly without losing their current filter or slicer state — delivering a polished, app-like experience inside Power BI.

---

##  Objectives

-  Implement a **dual-theme interface** (Light & Dark) using native Power BI features
-  Apply **modern UI/UX design patterns** — card layouts, shadow effects, icon-driven navigation
-  Demonstrate use of **Navigation buttons**

---

##  Tools & Technologies

| Tool / Feature | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development and design |
| **Navigation Buttons** | Overlay triggers for Sun/Moon icon interactions |

---

##  Key Features

###  1. Dual-Theme Interface
- **Dark Mode** — high-contrast dark background with vibrant accents for low-light environments
- **Light Mode** — clean, bright layout optimized for standard office and presentation settings
- Both themes are **fully designed and maintained** — not just a background color swap

### 2. Custom Theme Toggle Navigation
- **Sun icon** triggers the switch to Light Mode
- **Moon icon** triggers the switch to Dark Mode

```
Sun / Moon Icon Images with Action
        ↓
Theme Switches Instantly
```

This keeps the design clean — no visible buttons cluttering the layout, just intuitive icon interactions.

### Visual Consistency Across Themes
- Chart colors (blue sales bars, donut segments) remain **legible and professional** on both backgrounds
- Color palette tested for **contrast and readability** in both modes
- **No data or filter state is lost** during the theme transition — bookmarks are scoped to appearance only

### Card Layout with Shadow Effects
- Custom **shadow effects** applied to visual containers
- Creates a modern **"floating card"** aesthetic common in contemporary web and mobile UI
- Consistent corner rounding and spacing across all cards in both themes

---

## Benefits

| Benefit | Description |
|---|---|
|  **Modern Aesthetics** | Dashboard feels like a polished web application |
|  **Accessibility** | Dark mode reduces eye strain in low-light environments |
|  **Zero Data Disruption** | Filters and slicers remain active through theme changes |
|  **Native Implementation** | No third-party visuals or external tools required |
|  **Reusable Pattern** | The bookmark-based toggle can be applied to any Power BI report |

---

## Key Learnings

- Advanced **Bookmark management** — scoping bookmarks to visibility only (not filters or data)
- **Selection Pane layer organization** for complex multi-state dashboards
- Using **Image with Action** to create clean, icon-driven interactions
- Applying **UI/UX principles** — contrast, hierarchy, card depth — within Power BI's native canvas
- Maintaining **visual consistency and legibility** across multiple color themes

---

## Use Cases

This technique is ideal for:

-  **Executive dashboards** requiring a professional, polished appearance
-  Reports used across **different display environments** (bright rooms vs. dark presentation screens)
-  Any Power BI report where **modern UI/UX design** is a priority
-  **Portfolio projects** showcasing advanced Power BI design skills

---

## Outcome

-  Built a **fully functional Light/Dark theme toggle** using only native Power BI features
-  Delivered a dashboard that feels like a **modern web application**
-  Demonstrated that advanced UI/UX design is achievable **without custom visuals or external tools**

---

## Preview

### Light Mode
![Light Mode](https://github.com/user-attachments/assets/314fc32e-88e7-4e41-a7f8-78a6625c57fc)

*Clean, bright layout — optimized for standard office and presentation environments.*

---

### Dark Mode
![Dark Mode](https://github.com/user-attachments/assets/0dc4b796-a646-46cf-88aa-a88970b796a8)

*High-contrast dark theme — vibrant accents on a dark canvas, ideal for low-light settings.*

---

## Project Structure

```
 dynamic-theme-dashboard-powerbi
 ┣  DynamicTheme_Dashboard.pbix       # Main Power BI report file
 ┣  screenshots/
 ┃   ┣  light_mode.png
 ┃   └  dark_mode.png
 ┗  README.md                          # Project documentation
```

---

## Connect

If you found this project useful or have suggestions, feel free to open an **Issue** or submit a **Pull Request**.
