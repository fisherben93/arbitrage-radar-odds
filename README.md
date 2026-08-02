# Arbitrage Radar - Arbitrage Betting Scanner 2026

> **Arbitrage Radar is a browser-based surebet scanner that watches Polymarket markets, optionally compares proxy odds, and surfaces potential cross-book arbitrage through a live dashboard.**

[![Platform](https://img.shields.io/badge/Platform-Web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/fisherben93/arbitrage-radar-odds?style=flat-square)](https://github.com/fisherben93/arbitrage-radar-odds)

---

<p align="center">
  <a href="https://fisherben93.github.io/arbitrage-radar-odds/">
    <img src="https://img.shields.io/badge/Download-Arbitrage%20Radar%20Latest-brightgreen?style=for-the-badge" alt="Download Arbitrage Radar">
  </a>
</p>

> **[Download Arbitrage Radar](https://fisherben93.github.io/arbitrage-radar-odds/)**

---

[Download Latest Build](https://fisherben93.github.io/arbitrage-radar-odds/)

---

## Overview

Arbitrage Radar provides a browser-based workspace for examining sports betting arbitrage and prediction-market pricing. It retrieves live Polymarket data, works out two-way arbitrage percentages, and displays potential opportunities in a sortable dashboard.

The scanner is designed for comparing pricing between Polymarket and, when enabled, Orbit Broker or Betfair proxy odds. It can also calculate indicative stake amounts and outcome distributions. Market checks and any betting decisions remain under the user's manual control.

---

## What It Offers

- Pulls up-to-date Polymarket market information directly in the browser
- Computes two-way arbitrage percentages from available pricing
- Can include Orbit Broker and Betfair proxy odds as optional sources
- Provides a demo mode using simulated odds
- Calculates suggested total-stake splits for each outcome
- Supports category choices, filtering, and sortable result views
- Sends sound and desktop notifications when opportunities are detected
- Links to associated markets for manual inspection and betting
- Keeps scanning as long as the browser tab stays open

---

## Getting Started

### Open the hosted version

Use a modern web browser to open the current hosted application:

[Launch Arbitrage Radar](https://fisherben93.github.io/arbitrage-radar-odds/)

### Start a local copy

Fetch the repository and move into its project directory:

```bash
git clone https://github.com/fisherben93/arbitrage-radar-odds.git
cd REPO
```

Run the files through any local static web server. Python's built-in server can be used as follows:

```bash
python -m http.server 8000
```

Then browse to `http://localhost:8000`. Keep that page open whenever you want the scanner to continue monitoring.

---

## Using the Scanner

1. Load Arbitrage Radar in a web browser.
2. Use live data, or turn on demo mode to work with simulated odds.
3. Choose the categories you want to examine and set any filters.
4. Inspect the arbitrage percentage shown for each result.
5. Provide a planned total stake to see the recommended amount for every outcome.
6. Compare the listed sources and open the associated markets for manual review.
7. Turn on sound or desktop notifications to be alerted about newly found opportunities.
8. Leave the application tab open during live monitoring.

---

## Settings and Data Sources

The application uses its on-screen controls instead of requiring a configuration file. Available controls can vary by build and may cover data sources, categories, filters, sorting, notification behavior, and demo mode.

Orbit Broker and Betfair proxy odds are optional and can be switched on when those sources are available. Desktop alerts may require permission from the browser.

---

## Requirements

- A modern browser with JavaScript turned on
- Internet connectivity to retrieve live Polymarket data
- An open browser tab for ongoing scans
- Browser permission for desktop notifications
- A local static web server for running a checked-out copy
- Available proxy data when Orbit Broker or Betfair odds are selected

---

## Frequently Asked Questions

### Is Arbitrage Radar a desktop program?

No. Arbitrage Radar operates in the browser, and scanning continues only while its application tab is open.

### Is there a way to try it without live data?

Yes. Enable demo mode to use simulated odds and explore the scanner's interface and workflow.

### What sources can the scanner use?

Polymarket is supported directly. Orbit Broker and Betfair proxy odds can be added optionally when available.

### How does the tool determine the suggested stakes?

Enter a total stake, and the scanner uses the available odds together with the calculated two-way arbitrage figures to suggest an amount for each outcome.

### What should I check if the results list is empty?

Review the active categories and filters, make sure live data is available, and confirm that the application tab is still open. When proxy odds are enabled, also check that the selected proxy source is available.

### What can prevent desktop notifications from appearing?

Confirm that the browser allows notifications for the application and that desktop notifications are permitted by the operating system. Sound notifications can additionally be affected by browser media permissions.

### How can I get the latest version?

Open the hosted build at [https://fisherben93.github.io/arbitrage-radar-odds/](https://fisherben93.github.io/arbitrage-radar-odds/) or pull the latest changes into your local repository checkout.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
