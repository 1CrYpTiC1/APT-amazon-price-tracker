# APT-amazon-price-tracker

**STILL A WORK IN PROGRESS!!!**

A lightweight, privacy-friendly Amazon.in price tracker that runs on your PC.

---

## Features

- Tracks product prices and alerts you with discord webhook support when they drop below your target. [1]  
- Interactive price history plots for each item (generated using Plotly). [2]  
- Minimalist Tkinter GUI with dark mode, live search, editable product list, and more. [3]  
- Fully local: no cloud syncing, no ads, no data collection.

---

## Planned Features (Coming Soon)

- **Edit or Remove Products**  
  Modify product names, prices, or remove tracked items directly from the GUI.

- **Import / Export Product Lists**  
  Easily share or back up your tracked products as .json files.

- **Price Trend Summary Dropdown**  
  View highest, lowest, and average prices alongside each product—with an inline graph button.

- **Sort & Filter Options**  
  Sort products by name, current price, or distance from target price.

- **Settings Panel**  
  Adjust scan interval and toggle Discord alerts without editing code.

- **Autostart & Background Mode (Windows)**  
  Run the bot silently at system startup with no manual intervention.

- **Optional Flask Web UI / Android Control**  
  Control the tracker from a local browser or smartphone (experimental phase).

---

## Notes

[1] Needs discord webhook of the channel to be notified in.  
[2] Needs to check values every time the gui is reopened to be able to see plots, even if plot is previously generated.  
[3] Work in progress.
