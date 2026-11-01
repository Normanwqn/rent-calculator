# Rent Calculator

A single-page, dependency-free calculator for splitting pro-rated rent with a roommate,
with one-click PDF invoice export.

**Use it:** https://normanwqn.github.io/rent-calculator/

- Each line item is `Quantity × Unit Price`. Quantity is the roommate's share of that bill:
  `1/2` of a monthly bill, `1/6` of a quarterly bill, `1/24` of an annual bill.
- `Total = sum of costs × Num Days ÷ Days in Month`.
- Values are remembered in your browser as you type. **Save as defaults** stores the current
  items and invoice details so **Reset to defaults** brings them back next month.
- Browser storage is per device and can be cleared, so **Copy setup link** gives you a URL with
  your defaults embedded (bookmark it or send it to your phone; opening it restores them), and
  **Export file** / **Import file** move the same defaults as a JSON file.
- **Export PDF** draws the invoice in the browser with [jsPDF](https://github.com/parallax/jsPDF),
  fetched from jsDelivr on first use. Nothing is sent to a server; all data stays in your browser.

Everything is in `index.html`. To develop, open the file in a browser; to publish, push to `main`.
