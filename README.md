# Responsive Stock Comparison Page

![Project Screenshot](placeholder-screenshot.png) <!-- Optional: Replace with an actual screenshot URL or path -->

A responsive web page designed to visually compare key metrics, performance data, and qualitative information for two stocks (using Apple (AAPL) and Amazon (AMZN) as examples). Built with modern frontend technologies focusing on clean UI, data visualization, and responsiveness.

**Live Demo:** [Link to your live demo if available] <!-- Optional: Add link to live demo -->
**Code Repository:** [Link to your GitHub repo if different from where this README resides] <!-- Optional -->

---

## ✨ Features

*   **Side-by-Side Comparison:** Clear layout for comparing two stocks directly.
*   **Company Information:** Displays logos, company names, and tickers.
*   **Interactive Price Performance Chart:** Line chart visualizing normalized historical price growth using Chart.js. Includes tooltips on hover.
*   **Key Metrics Snapshot Chart:** Bar chart comparing essential financial metrics (e.g., Market Cap, P/E Ratio, Revenue Growth) using Chart.js.
*   **Detailed Data Tables:**
    *   Annual Returns comparison table.
    *   Recent Monthly Returns comparison table.
    *   Pros & Cons summary table.
*   **Responsive Design:** Fully adaptable layout for optimal viewing on desktop, tablet, and mobile devices.
    *   Includes a collapsible mobile navigation menu.
    *   Tables adjust for smaller screens (e.g., stacking content vertically).
*   **Modern Styling:** Clean and professional UI built entirely with Tailwind CSS utility classes and theme customization.
*   **Subtle UI Enhancements:** Includes hover effects (`hover-lift`) and fade-in animations for a smoother user experience.

---

## 🛠️ Technologies Used

*   **HTML5:** Semantic structure for the web page content.
*   **CSS3:** Base styling principles.
*   **Tailwind CSS:** Utility-first CSS framework for rapid UI development and styling.
    *   Includes custom theme configuration (`tailwind.config`).
*   **JavaScript (ES6+):** For interactivity, mobile menu toggle, and Chart.js integration.
*   **Chart.js:** JavaScript library for creating interactive and visually appealing charts.

---

## 🚀 Setup and Usage

This project uses CDN links for Tailwind CSS and Chart.js, so no complex build setup is required.

1.  **Clone the repository (optional):**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```
2.  **Open the HTML file:**
    Simply open the `index.html` file (or the main HTML file if named differently) in your web browser.

    *   On most systems, you can just double-click the `index.html` file.
    *   Alternatively, right-click and choose "Open With" your preferred browser.

---

## 💡 Potential Future Enhancements

*   Integrate a financial data API (e.g., Alpha Vantage, Finnhub) to fetch real-time or historical data.
*   Allow users to dynamically select and compare different stock tickers.
*   Add more chart types or financial metrics for comparison.
*   Implement date range selection for performance charts.
*   Refactor JavaScript into modules for better organization.
*   Add unit or end-to-end tests.

---

## 📄 License

<!-- Optional: Specify your license, e.g., MIT -->
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details (if you add one).

---

<!-- Optional: Add contact info or contribution guidelines if applicable -->