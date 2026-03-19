# Dynamic Theme Dashboard — Light & Dark Mode (Power BI)

> *A fully functional Light/Dark mode toggle built entirely with native Power BI features — no custom visuals, no code, just smart use of Bookmarks and Selection Pane.*

---

## Overview

This project demonstrates **advanced UI/UX design principles** in Power BI by implementing a seamless **Light and Dark mode toggle** — a feature typically associated with modern web and mobile applications, now brought natively into a BI report.

Using a combination of **Bookmarks** and the **Selection Pane**, users can switch between visual themes instantly without losing their current filter or slicer state — delivering a polished, app-like experience inside Power BI.

---

##  Objectives

-  Implement a **dual-theme interface** (Light & Dark) using native Power BI features
-  Preserve **filter and data state** across theme switches
-  Apply **modern UI/UX design patterns** — card layouts, shadow effects, icon-driven navigation
-  Demonstrate advanced use of **Bookmarks, Selection Pane, and transparent overlay buttons**

---

##  Tools & Technologies

| Tool / Feature | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development and design |
| **Bookmarks** | Capturing and switching between Light and Dark UI states |
| **Selection Pane** | Managing layer visibility for each theme |
| **Transparent Buttons** | Overlay triggers for Sun/Moon icon interactions |
| **DAX** | KPI measures for Sales, Profit, and Customer metrics |

---

##  Key Features

###  1. Dual-Theme Interface
- **Dark Mode** — high-contrast dark background with vibrant accents for low-light environments
- **Light Mode** — clean, bright layout optimized for standard office and presentation settings
- Both themes are **fully designed and maintained** — not just a background color swap

### 2. Custom Theme Toggle Navigation
- **Sun icon** triggers the switch to Light Mode
- **Moon icon** triggers the switch to Dark Mode
- Toggle buttons use **transparent overlays** placed over the icons — keeping the visual design clean while enabling click interactions

### 3. KPI Tracking
High-level business metrics visible across both themes:

| KPI | Value |
|---|---|
|  **Total Sales** | $29.3M |
|  **Total Profit** | $12.1M |
|  **Total Customers** | Tracked across all regions |

### 4. Categorical Analysis
- **Sales distribution by Occupation** — identifying which customer segments drive the most revenue
- **Profit margins by Product Category** — Bikes, Accessories, and Clothing compared side by side

### 5. Regional Insights
- **Customer density breakdown** across global sales territories
- Highlights dominant and underperforming regions at a glance

---

## Technical Implementation

### Step 1 — Bookmark States
Two bookmarks are created, each capturing a different visibility configuration:

| Bookmark | Visible Layers | Hidden Layers |
|---|---|---|
| **Dark Mode** | Dark theme visuals | Light theme visuals |
| **Light Mode** | Light theme visuals | Dark theme visuals |

### Step 2 — Selection Pane Layer Management
All visual elements are organized into **named groups** within the Selection Pane:
- `Dark_Layer` — contains all dark-themed backgrounds, cards, and text elements
- `Light_Layer` — contains all light-themed equivalents

Toggling visibility of these groups via bookmarks produces the full theme switch.

### Step 3 — Transparent Overlay Buttons

```
Sun / Moon Icon Image
        ↓
Transparent Button (same size, placed on top)
        ↓
Button Action → Trigger Bookmark
        ↓
Theme Switches Instantly
```

This keeps the design clean — no visible buttons cluttering the layout, just intuitive icon interactions.

### Step 4 — Visual Consistency Across Themes
- Chart colors (blue sales bars, donut segments) remain **legible and professional** on both backgrounds
- Color palette tested for **contrast and readability** in both modes
- **No data or filter state is lost** during the theme transition — bookmarks are scoped to appearance only

### Step 5 — Card Layout with Shadow Effects
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
- Using **transparent overlay buttons** to create clean, icon-driven interactions
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
