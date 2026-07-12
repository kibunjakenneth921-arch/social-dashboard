Solution Centre Analytics Dashboard

A lightweight, mobile‑friendly social media analytics dashboard that pulls live data from a Google Sheet and displays key performance metrics for three brands: Shunjaaz, Solution Center KE, and Step Forward KE.

Built with vanilla HTML, CSS, and JavaScript – no backend, no database, just a single static file hosted on GitHub Pages.
🚀 Live Demo

Once deployed, your dashboard will be available at:
https://kibunjakenneth921-arch.github.io/social-dashboard/
✨ Features

    6 KPI Cards – Total Reach, Followers, Engagement, DM Leads, Ad Spend, Engagement Rate (latest data from the Dashboard tab)

    3 Brand Summary Cards – Reach, Followers, Engagement, Growth %, and a status indicator (Growing/Declining/Stable)

    4 Interactive Charts (Chart.js):

        Follower Growth (Line chart)

        Reach Comparison (Bar chart)

        Platform Distribution (Pie chart)

        Monthly Growth (Area chart)

    Top Performing Posts – Table with Platform, Title, Reach, Engagement, and Date (from the Top Posts tab)

    Auto‑refresh every 60 seconds – data updates without reloading the page

    Dark mode toggle – remembers user preference

    Print dashboard – prints a clean, styled version

    Export charts as PNG – download the first chart as an image

    Fully responsive – works on desktop, tablet, and mobile

    Error handling – graceful fallback if the Google Sheet is unavailable

🛠️ Technology Stack

    Frontend: HTML5, CSS3, Vanilla JavaScript

    Charts: Chart.js (CDN)

    Icons: Font Awesome (CDN)

    Fonts: Google Fonts – Inter

    Data source: Google Sheets (read‑only via Google Visualization API)

    Hosting: GitHub Pages (free)

📋 Google Sheet Setup

The dashboard reads data from a single public Google Sheet with exactly 5 tabs. You must create these tabs and name them case‑sensitively:

    Dashboard – holds the latest overall metrics

    Shunjaaz – performance data for the Shunjaaz brand

    Solution Center KE – performance data for Solution Center KE

    Step Forward KE – performance data for Step Forward KE

    Top Posts – list of top performing posts

Column Headers (first row)
Dashboard
text

Date | Reach | Followers | Engagement | DM Leads | Spend | Engagement Rate

Shunjaaz, Solution Center KE, Step Forward KE
text

Date | Platform | Reach | Followers | Likes | Comments | Shares | Impressions | Clicks | DMs | Growth %

Top Posts
text

Platform | Title | Reach | Engagement | Date

    ⚠️ Important: The dashboard uses the last row of the Dashboard tab for KPI values, and the last row of each brand tab for the brand summary cards. Add new rows at the bottom with the latest data.
