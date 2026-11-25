# Ed's Movies Dashboard

A lightweight, single-file interactive dashboard for tracking and visualizing movies watched in theaters. Built with vanilla HTML, CSS, JavaScript, and **Plotly.js**, it pulls live data directly from a published Google Sheet and is designed to be hosted effortlessly on **GitHub Pages**.

## Features

* **Live Google Sheets Integration:** Fetches and parses data client-side via [PapaParse](https://www.papaparse.com/)—no backend or build step required.
* **Interactive Filtering:** Filter visualizations by one or multiple years, with a built-in **Select All / Clear All** toggle.
* **Custom Attribution Tags:** Switch the chart watermark/tag on the fly between Twitter, Facebook/LinkedIn, and Bluesky handles for easy sharing.
* **Summary Stats & Rewatch Tracker:** Automatically calculates total movies seen, total time spent in theaters (minutes, hours, and days), and generates a table of movies seen more than once.
* **8 Interactive Visualizations:**
  * **Monthly & Weekly Views:** Grouped bar charts showing movie counts by month and day of the week.
  * **Content & Location Breakdowns:** Treemaps for Genres and Theater Chains.
  * **Release Type & Distributor Analysis:** Donut chart for New vs. Re-Releases and a Distributor treemap.
  * **Genre Deep Dives:** Genre Affinity heatmap across top theater chains and a Runtime Distribution box plot sorted by median length.

## Project Structure

```text
.
├── index.html   # Complete dashboard (HTML, CSS, and Plotly.js logic)
└── README.md    # Project documentation
```