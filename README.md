#  CarbCal WebApp

<p align="center">
  <img src="CarbCal.png" alt="CarbCal Logo" width="150"/>
</p>

<h3 align="center">A modern, feature-rich web application for carbohydrate calculation and tracking.</h3>

<p align="center">
  Built with pure HTML, CSS, and vanilla JavaScript, CarbCal offers a responsive, user-friendly interface with light/dark modes, online food search capabilities, and persistent local data storage.
</p>

---

## ✨ Key Features

- **📱 Responsive Design:** A fluid and adaptive UI that works seamlessly on desktops, tablets, and smartphones.
- **🌗 Light & Dark Mode:** Switch between themes for optimal viewing comfort, with your preference saved across sessions.
- **🧮 Accurate Carb Calculator:** Quickly calculate total carbohydrates based on the food's weight and its carbs-per-100g value.
- **💾 Persistent Saved Items:** Save your frequently used food items directly in your browser. Your list is always available, even after you close the tab.
- **🌐 Online Food Search:**
    - Instantly find nutrition data for a vast array of foods.
    - Utilizes the **Nutritionix API** for detailed, professional-grade data.
    - Automatic fallback to the **Open Food Facts API** if the primary service is unavailable, ensuring high availability.
- **📊 Detailed Nutrition Facts:** Click on any online search result to view a comprehensive breakdown of its nutritional information in a clean, modal view.
- **✍️ Custom Item Entry:** Manually add and save your own custom food items with specific serving sizes and carbohydrate counts.
- **🚀 Zero Dependencies:** Built with vanilla HTML, CSS, and JavaScript. No frameworks, no build steps. Just open `index.html` and go.
- **🎨 Modern UI & Animations:** Features a clean, card-based layout with subtle animations for a smooth and engaging user experience.

---

## 🚀 How to Use

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/LucaMurdoch/CarbCal.git
    ```
2.  **Navigate to the directory:**
    ```bash
    cd CarbCal/WebApp
    ```
3.  **Open the application:**
    Simply open the `index.html` file in your favorite web browser.

---

## 🔧 Technical Details

CarbCal is built from the ground up using core web technologies, demonstrating efficient and framework-free development.

-   **DOM Manipulation:** The dynamic and interactive UI is powered entirely by vanilla JavaScript, which handles everything from calculations and UI updates to creating and managing elements on the fly.
-   **Browser `localStorage`:** All user data, including the list of saved food items and the selected theme (light/dark), is stored and retrieved using the browser's `localStorage` API. This ensures data persistence across sessions without needing a backend.
-   **`fetch` API for Asynchronous Operations:** The online search feature uses the native `fetch` API to make asynchronous HTTP requests to the Nutritionix and Open Food Facts APIs.
-   **Robust API Fallback Logic:** The application is designed for resilience. It first attempts to fetch data from the Nutritionix API. If this fails for any reason (e.g., API limits, network errors), it automatically and seamlessly falls back to the Open Food Facts API, ensuring the user can still get results.
-   **CSS3 for Styling and Animations:** The application is styled with modern CSS, including Flexbox for layout, custom properties for theming (light/dark modes), and keyframe animations for subtle, meaningful UI transitions.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
