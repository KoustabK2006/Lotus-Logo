# 🪷 LOTUS Logo

An animated LOTUS logo built with **pure HTML & CSS**, no JavaScript required.

Hover over the logo to watch the petals and leaves open while the text lifts away. Click it to reveal your social media links in a circular menu.

## ✨ Features

- **Pure CSS animation**: no JavaScript, no frameworks
- **Hover effect**: petals and leaves spread open, the "L O T U S" text slides up, and a soft glow appears
- **Click effect**: the logo morphs into a circle and reveals four social links (YouTube, Instagram, Facebook, X)
- **Brand-coloured hover states** on each social icon
- **Easy to customize**: blur, shadow and scale can be adjusted from a single line each

## 🚀 Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/KoustabK2006/Lotus-Logo.git
    ```

2. Open `index.html` in any browser.

## 🧩 Using the Logo in Your Own Project

1. Copy the `@import` section from `logo-style.css` into your stylesheet.
2. Add the Font Awesome link to your HTML `<head>`:
    ```html
    <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"
    />
    ```
3. Copy the `<button class="logo">...</button>` block from `index.html` into your page body.
4. Copy the rest of the CSS into your stylesheet (after the imports).
5. Make sure your `body` has these properties so the logo centers properly:
    ```css
    display: flex;
    justify-content: center;
    align-items: center;
    ```

## 🎨 Customization

| What to change | CSS selector              | Property             |
| -------------- | ------------------------- | -------------------- |
| Backdrop blur  | `.logo`                   | `backdrop-filter`    |
| Logo size      | `.logo`                   | `transform: scale()` |
| Glow / shadow  | `.logo`, `.logo:hover`    | `box-shadow`         |
| Social links   | `.status` section in HTML | `href` attributes    |

## 📁 Project Structure

```
Lotus-Logo/
├── index.html       # Logo markup
├── logo-style.css   # All styles and animations
└── README.md
```

## 🛠️ Built With

- HTML5
- CSS3 (transitions, transforms, gradients)
- [Font Awesome](https://fontawesome.com/) for social icons
- [Google Fonts](https://fonts.google.com/): Varela Round & Josefin Sans

## 📸 Preview

> Add a screenshot or GIF of the hover and click effects here.

## 📄 License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify it, and credit is appreciated.

## 👤 Author

Designed by **Koustab Koley**, 2023.
