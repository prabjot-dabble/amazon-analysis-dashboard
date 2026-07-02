# Amazon Advertising Executive Dashboard 📈

An enterprise-grade, single-page application (SPA) designed for CEOs, VPs of Marketing, and business leadership to visualize and analyze Amazon Advertising performance. 

This dashboard transforms raw advertising data into actionable insights, featuring automated forecasting, campaign health scoring, and week-over-week performance tracking—all contained within a lightweight, vanilla web stack.

## ✨ Key Features

*   **Executive KPIs & Sparklines:** High-level metrics (Sales, Spend, ACOS, ROAS, CTR, etc.) with custom-drawn HTML5 canvas sparklines showing 4-week trends.
*   **Week-over-Week (WoW) Analysis:** Detailed performance comparisons across weeks, complete with a Sales Waterfall chart.
*   **Campaign Health Scoring:** A composite health metric driven by ROAS, ACOS, CTR, and Conversion Rate, visualized with custom radial gauges.
*   **ASIN Performance Deep Dive:** Product-level analysis featuring revenue contribution treemaps and ACOS vs. Sales scatter plots.
*   **Conversion Funnel:** Visual breakdown of the customer journey from Impressions to Revenue.
*   **Automated Insights & Alerts:** A threshold-driven logic engine that automatically generates "Wins," "Risks," and "Actions" based on metric fluctuations.
*   **Forecasting Engine:** Built-in linear regression algorithms to predict next week's performance with confidence intervals.
*   **Dynamic Executive Summary:** An auto-generated, text-based CEO brief summarizing the week's performance, key wins, risks, and recommended actions.

## 🛠️ Tech Stack

This project is built purely with vanilla web technologies, requiring no build tools or bundlers.

*   **HTML5:** Semantic structure for a multi-section, scroll-spied single-page layout.
*   **CSS3:** Custom design system utilizing CSS Variables (`:root`), Flexbox, and CSS Grid for a fully responsive experience without external frameworks (like Bootstrap or Tailwind).
*   **Vanilla JavaScript (ES6+):** Handles all state, logic, DOM manipulation, and dynamic metric calculations.
*   **Chart.js (v4.4.4):** Powers the complex data visualizations (Line, Bar, Radar, Scatter, Bubble, Waterfall).
*   **Chart.js Datalabels Plugin:** Renders inline data labels on charts for immediate readability.

## 🚀 Getting Started

Because this dashboard is a static, vanilla web application, setup is instant.

### Prerequisites
None! All you need is a modern web browser.

### Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/amazon-ads-dashboard.git](https://github.com/yourusername/amazon-ads-dashboard.git)
