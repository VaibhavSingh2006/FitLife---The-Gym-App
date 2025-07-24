# 💪 Fitlife – Work Hard To Get Better Life

**Fitlife** is a modern, responsive fitness website designed for fitness enthusiasts, gyms, and personal trainers. Built using HTML, CSS, and JavaScript, it provides an interactive and engaging interface with dynamic elements like a responsive navbar, scroll effects, class sections, blog highlights, and a scroll-to-top button.

🧡 This project is being contributed as part of **GirlScript Summer of Code 2025 (GSSoC'25)**.

---

## 🌐 Live Demo

🔗 [Live Website](https://github.com/VaibhavSingh2006/FitLife---The-Gym-App.git)  


---

## 📸 Preview

![Fitlife Preview](./assets/images/about-banner.png) ![alt text](assets/images/blog-1.jpg)  


---

## 🚀 Features

- 📱 Fully responsive for all screen sizes  
- 📌 Sticky header activation on scroll  
- 📂 Toggle-able navigation menu for mobile  
- 🧘 Class showcase with icons and descriptions  
- 🎬 Embedded video teaser section  
- 📝 Blog section to share updates/tips  
- 🔝 Scroll-to-top button  
- ✉️ Newsletter form (UI)  
- 🌍 Contact & social media footer  
- ⚡ Smooth JavaScript interactions  

---

## 🛠️ Tech Stack

- HTML5  
- CSS3  
- JavaScript (Vanilla)  
- Ionicons  
- Google Fonts  

---

## 📂 Folder Structure

```
FitLife---The-Gym-App/
├── assets/
│   ├── images/   
├── index.html
├── style.css
├── script.js
|- README.md
```

---

## 📜 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/VaibhavSingh2006/FitLife---The-Gym-App.git
   ```
2. Navigate into the project:
   ```bash
   cd FitLife---The-Gym-App.git
   ```
3. Open `index.html` in your browser.

> ✅ No build tools or server setup required — it's all static!

---

## 📘 Code Highlights

### `script.js` includes:

- ✅ Reusable event handler function  
- ✅ Toggle navigation bar visibility on click  
- ✅ Add/remove header and back-to-top button visibility based on scroll position

```js
const addEventOnElem = function (elem, type, callback) {
  if (elem.length > 1) {
    for (let i = 0; i < elem.length; i++) {
      elem[i].addEventListener(type, callback);
    }
  } else {
    elem.addEventListener(type, callback);
  }
};
```

---

## ✨ Contributing

We welcome contributions! If you're participating in **GSSoC'25**, feel free to raise issues, submit PRs, or enhance features.

> Don’t forget to ⭐ the repo if you find it helpful!

---

## 🧑‍💻 Author

**Vaibhav Singh**  
GitHub: [@VaibhavSingh2006](https://github.com/VaibhavSingh2006)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙏 Original Source / Credits

This project is adapted from the open-source fitness website template by **codewithsadee**  
🔗 [Original Repository](https://github.com/VaibhavSingh2006/FitLife---The-Gym-App.git)

All rights and credits go to the original creator.  
Modifications were made by **Vaibhav Singh** as part of **GSSoC'25**.

---

## 🙌 Acknowledgements

- [GSSoC](https://gssoc.girlscript.tech/) – GirlScript Summer of Code  
- [Ionicons](https://ionic.io/ionicons)  
- [Google Fonts](https://fonts.google.com/)  
- Designed with love ❤️ to inspire a healthy lifestyle.
<!-- Temporary change for testing update -->
