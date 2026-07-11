# 🌤️ Dynamic Weather Radar Dashboard

A modern, responsive, single-page weather dashboard built with clean glassmorphism UI aesthetics. This project was developed as a hands-on implementation to learn asynchronous API consumption, JSON payload handling, and dynamic DOM manipulation using pure client-side web technologies.

---

## 🚀 Features

*   **Real-Time Metrics:** Fetches up-to-date ambient metrics including current temperature, perceived ("feels like") temperature, humidity levels, wind speed, and the current UV index.
*   **Asynchronous UX Flow:** Built using modern JavaScript `async/await` patterns with the native Fetch API to fetch data behind the scenes without refreshing the page.
*   **Intuitive Error State Handling:** Automatically intercepts invalid search input, displaying structural error indicators while keeping the UI aligned.
*   **Glassmorphic Interface:** A visually striking layout utilizing CSS custom properties, backdrop filters (`blur`), flexbox configurations, and CSS grid alignments.

---

## 🛠️ Tech Stack

*   **Structure:** HTML5 Semantic Markup
*   **Styling:** CSS3 (Variables, Backdrop Blur Filter, Flexbox, Custom Grid)
*   **Core Logic:** JavaScript (ES6+, Fetch API, Event Handlers)
*   **Data Provider:** WeatherAPI (Free Tier)

---

## ⚙️ How to Run the Project Locally

Because this application relies entirely on pure client-side technologies, it requires zero environment setups, compilers, or local software installations:

**Download or Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Weather-Dashboard.git](https://github.com/YOUR_USERNAME/Weather-Dashboard.git)
   cd Weather-Dashboard
   ```

---

# Launch the Code:

Simply double-click your index.html file to run it natively inside any modern web browser.

Alternatively, right-click the file inside VS Code and select Open with Live Server to see your changes refresh instantly as you modify the code.

---

# 🔑 Managing Your API Key & Expiration
The dashboard initializes using a shared, free access tier credential from WeatherAPI. Because public free keys frequently experience rate limits or expiration over time, you can quickly plug in your own personal key to ensure uninterrupted performance:

Go to WeatherAPI.com and register a free developer account.

Access your account profile dashboard and copy your freshly generated API Key.

Open your index.html file, scroll down into the <script> tag at the bottom, and update the value of the apiKey variable:

**JavaScript**
```// Replace the placeholder string with your personal token
const apiKey = "PASTE_YOUR_NEW_FREE_API_KEY_HERE";
```

---

