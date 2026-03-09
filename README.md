# 🚀 Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

---

## 🎬 Demo

![Animated preview demonstrating the responsive layout and interaction states](./docs/demo.gif)

---

## 🎯 The challenge

Users should be able to:

- See hover states for interactive elements

---

## 📸 Screenshots

### 📱 Mobile

![Mobile layout of order summary component](./docs/mobile-default.avif)

### 📲 Tablet

![Tablet layout of order summary component](./docs/tablet-default.avif)

### 🖥️ Desktop

![Desktop layout of order summary component](./docs/desktop-default.avif)

### 🖥️ Desktop interaction &ndash; `:hover` & `:focus-visible`

![This screenshot highlights the hover and focus-visible states for links and buttons](./docs/desktop-interaction.avif)

---

## Links

- 🌎 [Live site](https://vimpdev.github.io/fem-10-order-summary-component/)
- 👩‍💻 [View solution on Frontend Mentor](https://www.frontendmentor.io/solutions/order-summary-card-modern-css-with-layer-and-native-nesting-IujFZpT4S6)

---

## 🛠️ Built with

- Semantic HTML5
- Mobile-first workflow
- Modern CSS
- CSS custom properties
- Flexbox
- `@layer` for style architecture
- Native CSS Nesting
- Responsive design

---

## ♿ Accessibility improvements

Accessibility was an important focus in this project.

- Adjusted a color that triggered contrast warnings in accessibility tools
- Verified accessibility using **Lighthouse** and **WAVE**
- Added focus-visible states for interactive elements

---

## 🧠 What I learned

This project helped reinforce several modern CSS techniques and accessibility practices.

### 📌 Using `@layer` to organize CSS
```css
@layer reset, base, components, utilities;
```
This allows better control over **style cascade** and **architecture**.

### 📌 Native CSS nesting
```css
.button {
  background: var(--primary);

  &:hover {
    opacity: .9;
  }
}
```

Native nesting improves **readability** and **maintainability**.

---

## 📚 Useful resources

- 📰 [Regla `@layer` en CSS](https://lenguajecss.com/cascada-css/especificidad/regla-layer/)  by ManzDev.

- 📺 [CSS `@layer`](https://youtu.be/NDNRGW-_1EE) by Kevin Powell.

---

## 🤖 AI Collaboration

AI was used as a **technical assistant and reviewer**, not as an automatic generator.

- Reviewing semantic HTML structure
- Improving accessibility practices
- Refining metadata (SEO, Open Graph, Twitter cards)
- Improving README documentation

AI acted as a technical reviewer and brainstorming partner, while the implementation and decisions remained manual.

---

## 👤 Author

- Frontend Mentor – [@vimpdev](https://www.frontendmentor.io/profile/vimpdev)

---
