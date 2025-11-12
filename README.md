# Frontend Mentor - E-commerce product page solution

This is my solution to the [E-commerce product page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/ecommerce-product-page-UPsZ9MJp6).  
Frontend Mentor challenges help you improve your front-end skills by building realistic projects.

## 🧭 Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for all interactive elements
- Open a lightbox gallery by clicking on the main product image
- Switch the main image by selecting thumbnails
- Add items to the cart
- View and remove items from the cart

### 📸 Screenshot

![Desktop preview](./images/image-desktop.png)

### 🔗 Links

- Solution URL: [https://www.frontendmentor.io/solutions/ecommerce-product-page-tailwindcss-js](#)
- Live Site URL: [https://ambroise.neocities.org/ecommerce](#)

---

## 🛠️ My process

### Built with

- Semantic **HTML5** markup
- **TailwindCSS** for responsive and modern styling
- **Font Awesome** for icons
- **Flexbox**
- **Vanilla JavaScript** for interactivity
- **Mobile-first workflow**

---

### 💡 What I learned

This challenge helped me strengthen my understanding of:

- DOM manipulation with JavaScript
- Managing dynamic states (like cart updates)
- Building responsive layouts with Tailwind’s utility classes
- Creating overlays and modals for image previews

Here’s a snippet I’m proud of:

```js
let index = 1;

function incremente() {
  if (index < 4) {
    index++;
    popupImg.src = `images/image-product-${index}.jpg`;
    imagePop.src = `images/image-product-${index}.jpg`;
    nextBtn.style.cursor = "pointer";
    prevBtn.style.cursor = "pointer";
  }
  if (index === 4) {
    nextBtn.style.cursor = "not-allowed";
  }
}

function decremente() {
  if (index > 1) {
    index--;
    popupImg.src = `images/image-product-${index}.jpg`;
    imagePop.src = `images/image-product-${index}.jpg`;
    prevBtn.style.cursor = "pointer";
    nextBtn.style.cursor = "pointer";
  }
  if (index === 1) {
    prevBtn.style.cursor = "not-allowed";
  }
}
```
### Continued development

sidebar toggling with smooth transitions

## Author

- Website - [Ambroise Smiler 😉](https://www.ambroise.neocities.org)
- Frontend Mentor - [@smiler00](https://www.frontendmentor.io/profile/smiler00)
- Twitter - [@smle1254](https://www.twitter.com/smle1254)

