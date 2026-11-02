# Serial Dilution Calculator

Single-file browser calculator for serial dilutions of cells, proteins, drugs or any stock.

- Enter the stock (concentration + volume available) and the targets you need (concentration + volume each).
- A target can also be a dilution of the row above, e.g. `1:2`, `1:10` (row 1 is relative to the stock); 1:10 = 1 part + 9 parts diluent.
- Export / Import: save a series as a `.json` file and load it again later.
- Units: cells/mL (accepts `1,5x10^6`, `1.5e6`, `2,5×10⁵`), ng/µg/mg per mL, pM–M, U/mL, %, fold.
- **Serial** mode: tubes are made from highest to lowest concentration, each tube sized to supply the next.
- **Direct** mode: every tube is made straight from the stock.
- Visual scheme (tubes or wells) with transfer and diluent volumes, protocol table, copy/print, warnings for
  insufficient stock or pipetting volumes below your minimum.
- Decimal comma or point; "Pipetting reserve" tickbox (default 10 %) adds extra to every tube on top of what it gives out, so the series does not run dry.

Open `index.html` in any browser, or use the GitHub Pages site. All data stays in the browser (localStorage).
