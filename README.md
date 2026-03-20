📖 WOTLdaily - GitHub Integration Bridge

Welcome to the official GitHub repository of WOTLdaily. This repository serves as the central integration hub and data bridge for the main WOTL project hosted on your external infrastructure.

🔗 Project Role & Purpose

This repository functions as the primary connector for the WOTL ecosystem:

Centralized Logic Hosting: It hosts the logic.js file, ensuring that all script updates happen in one place and sync across all platforms.

API Data Bridge: The logic here connects your website to the Catholic Readings API (for liturgical references) and Bible-API.com (for full KJV scripture texts).

Cross-Platform Delivery: It ensures that the "Daily Bread" is consistently formatted and delivered, whether accessed via a browser or a mobile view.

⚙️ Technical Integration (The Bridge)

To use this repository as the source for your website, reference the JavaScript directly from your GitHub Pages or a CDN:

1. Direct Script Injection

Include the bridge in your HTML by referencing your logic.js file:

<!-- Load the Gospel & Psalm logic from your GitHub -->
<script src="[https://your-username.github.io/wotldaily/logic.js](https://your-username.github.io/wotldaily/logic.js)"></script>


2. Implementation Target

The logic.js file automatically detects and populates the following elements on your site:

gospel-date: Displays the current date in English.

gospel-content: Injects the daily Gospel reference and text.

psalm-content: Injects the daily Responsorial Psalm reference and text.

✨ Key Features

Daily Liturgy: Automatically synchronized with the Catholic liturgical calendar.

KJV Translation: Provides the classic King James Version for English-speaking users.

Responsive Injection: Content is injected with smooth fade-in animations and Tailwind CSS styling.

Fail-safe Logic: Includes error handling for cases where API data might be temporarily unavailable.

🚀 Technologies Used

Logic: Vanilla JavaScript (ES6+ Async/Await)

Data Sources:

Catholic Readings API - Liturgical calendar data.

Bible-API.com - Real-time KJV scripture retrieval.

Frontend Integration: Tailwind CSS & Font Awesome.

Hosting: GitHub Pages (serving as the logic provider).

🛠️ How to Maintain

Edit logic.js: Any changes made to the logic here will immediately reflect on wotl.infinityfree.me.

Deployment: Simply push your changes to the main branch. GitHub Pages will handle the rest.

📱 Connect with Us

Stay updated with daily reflections on our YouTube channel:
@WOTLdaily

"Man shall not live by bread alone, but by every word that proceedeth out of the mouth of God." - Matthew 4:4
