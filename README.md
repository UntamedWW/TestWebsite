```md
<a href="https://flutter.dev/">
  <h1 align="center">
    <picture>
      <img alt="Website" src="\https://github.com/user-attachments/assets/40f6f9ee-8301-4710-95e2-fc290d29e468">
    </picture>
  </h1>
</a>!


# Euphoria – Fashion Store Landing Page

Static website prototype built while learning **HTML5 & CSS3**.  
The goal was to recreate a modern e-commerce landing page with navigation, hero banner, product sections and feedback cards.

---

## Preview  

![Homepage screenshot](docs/euphoria_home.png)

---

## Features

* **Responsive navigation bar** with links for Shop, Men, Women, Combos, Joggers and a search field.  
* **Hero banner** (“Summer Value Pack”) including a “Shop Now” button.  
* Themed **deal tiles**, **new-arrival gallery**, **big-saving-zone** grid and brand logos.  
* Basic **feedback carousel** placeholder (static for now).  
* Images and icons stored under `Pictures/` for easy replacement.  

All interactions are pure HTML/CSS; no JavaScript yet, except for the (future) slider task marker in the banner.

---

## Folder layout  

```

Euphoria/
├── Main-Euphoria.html     # landing page (longer version)
├── Shop.html
├── Men.html
├── Women.html
├── Combos.html
├── Joggers.html
├── style.css              # central stylesheet
└── Pictures/              # logos, banners, product shots, icons

```

> **Note**: a shorter testing file `index.html` is included with only the header for quick experiments.

---

## Running locally

Just open **`Main-Euphoria.html`** (or any other page) in a browser; no build step or server is required.

```

# macOS / Linux

open Main-Euphoria.html

# Windows

start Main-Euphoria.html

```

---

## Things to improve

* Convert the static hero banner into a real **image slider**.  
* Add **JavaScript filtering** for the product galleries.  
* Implement a lightweight cart preview and favourite-items storage with LocalStorage.  
* Refactor repeated HTML into reusable components once a framework (React, Vue, etc.) is introduced.

---

### Technology

| Stack   | Usage                          |
|---------|--------------------------------|
| **HTML5** | Semantic structure of pages |
| **CSS3**  | Layout (Flexbox, Grid), colours, fonts (`Google Fonts – Montserrat, REM`) |
| (planned) **JS** | Slider & interactivity |

---

Created as an early exercise in web development — contributions or suggestions are welcome!
```
