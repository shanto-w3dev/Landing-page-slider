# Simple HTML & CSS Image Slider 🖼️

This project showcases a lightweight and straightforward image slider created using only **HTML** and **CSS**. It utilizes CSS animations to cycle through a set of background images, providing a clean, script-free sliding effect.

## 🚀 Features

* **Pure CSS:** No JavaScript is used, making it very lightweight.
* **CSS Animations:** Leverages `@keyframes` for smooth image transitions.
* **Simple Structure:** Easy-to-understand HTML markup.
* **Customizable:** Easily change images, transition timings, and appearance by modifying the CSS.

---

## 🛠️ How it Works

The slider's functionality is achieved through these steps:

1.  **HTML Structure (`slider.html`):**
    * A single `div` element with the class `main-slider` is defined. This `div` serves as the container and the viewing area for the slider.

2.  **CSS Styling & Animation (`style.css`):**
    * The `.main-slider` class is styled to define its size (`width: 70%`, `height: 400px`), centered (`margin: 0 auto;`), and given an initial background image (`background-image: url("images/walle.jpg");`).
    * Crucially, it's assigned a CSS animation named `slider`. This animation is set to run for `9` seconds, repeat `infinite`ly, and progress `linear`ly.
    * The `@keyframes slider` rule dictates the animation's flow. It changes the `background-image` property at specific points in the animation cycle:
        * At **0%**, the image is `images/walle.jpg`.
        * At **35%**, it transitions to `images/up.jpg`.
        * At **75%**, it changes to `images/nemo.jpg`.
    * The browser smoothly transitions between these background images based on these keyframes.

---

## ⚙️ How to Use

Follow these steps to set up and customize the slider:

1.  **Download/Clone:** Get the `slider.html` and `style.css` files.
2.  **Image Folder:** Get the `images` folder. it consist 3 images `walle.jpg`, `up.jpg`, and `nemo.jpg`.
3.  **Customize (Optional):**
    * Open `style.css`.
    * In the `@keyframes slider` rule, change the `url(...)` values to match your image names.
    * Adjust the percentages (`0%`, `35%`, `75%`) to control when images change.
    * Modify the `animation: slider 9s infinite linear;` line in the `.main-slider` class to change the total duration (`9s`), timing function (`linear`), or iteration count (`infinite`).
4.  **View:** Open `slider.html` in your web browser.

---

## 📁 Files

* `slider.html`: Contains the basic HTML structure for the slider container.
* `style.css`: Holds all the styling information, including the layout and the keyframe animation for the slider effect.
* `images`: This folder holds all the images that used in the slider.

Enjoy this simple demonstration of CSS-only animation power!
