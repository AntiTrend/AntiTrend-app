## AntiTrend

AntiTrend is a Chrome extension that filters fast-fashion, mass-market retailers, and sponsored results from Google search and shopping.

**Search the internet on your terms.**

## Now Live

Available on Chrome Web Store (v1.7.1):

Install AntiTrend￼

No account required. Works instantly.

## What's New in v1.8.0

### 🆕 Feedback Banner (Lightweight + Non-Intrusive)

AntiTrend now includes a subtle feedback banner to help improve the product based on real user experience — without interrupting your browsing.

**How it works:**
- Appears at the **bottom of the page**
- Only shows when AntiTrend has **filtered at least one result**
- Displays **once per day** per user
- Includes a **“Share feedback”** link to a Google Form
- Can be dismissed with an **✕ close button**

**Under the hood:**
- Triggered inside `filterResults()` when `blockedCount > 0`
- Uses `localStorage` to track the last shown date
- Prevents duplicate banners with `getElementById`
- Delayed by **2 seconds** using `setTimeout` to allow search results to fully render before displaying

This keeps the experience clean while giving users an easy way to provide feedback when it matters most.

## Latest Update (v1.7.1)

AntiTrend v1.7.1 improves filtering reliability and expands user control.
- Expanded control over filtered brands and keywords
- Improved accuracy across Google search and shopping results
- UI improvements to the extension popup
- Performance and stability improvements

**Early traction:** 40+ installs in early release, growing steadily.

## Previous Update (v1.6)
- Improved visibility into what retailers are being filtered
- Early customization controls added
- General performance improvements

AntiTrend v1.6 introduced:
- Visible blocked brand list
- Toggle controls for preset brands
- Custom domain filtering
- Custom keyword filtering

🌐 Website: https://antitrend.org

🧩 [Install AntiTrend](https://chromewebstore.google.com/detail/antitrend-filter/idonkhogbeapeekaklegfnbcknbpbpin)

Currently available for Chrome desktop browsers.

## What AntiTrend does
- Filters fast fashion retailers and marketplaces
- Removes sponsored and low-quality results
- Gives you control over what appears in your search

## Early Stage Release

This is the first public version of AntiTrend and it will continue to evolve with real user feedback.
