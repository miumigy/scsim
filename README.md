# Simple Suppy Chain Simulator

A self-contained, browser-based Supply Chain Simulator for educational and practical use.  
This tool visualizes end-to-end supply chain flows, cost structures, and PSI (Production, Sales, Inventory) balance, helping users understand trade-offs and optimize decision-making in SCM.

## Demo

https://github.com/user-attachments/assets/870472c3-01d1-4424-9c01-fad0f26a2ecb

## Features

- **One-file HTML/JavaScript:** No build or installation required. Just copy & run in any modern browser (including mobile).
- **Flexible Supply Chain Configuration:** Easily define stock points (Raw, Factory, Warehouse, Store), flows, and costs in JSON.
- **PSI Conservation:** Strict consistency of inventory and flow across all stock points.
- **Cost Breakdown Visualization:** See fixed/variable costs by flow, stock, and product in real-time.
- **Interactive Dashboard:** Track cash flows, product profit/loss, PSI tables, and operational logs.
- **Scenario Simulation:** Adjust demand, lead times, capacities, and costs; simulate multi-turn scenarios.
- **Educational Design:** Suitable for supply chain training, business games, or as a learning aid for new staff.
- **Mobile-friendly:** Responsive layout for tablets and smartphones.

## Usage

1. **Download:** Get the latest `index.html` from this repository.
2. **Open:** Launch the file directly in your browser—no server needed.
3. **Edit Config:** Use the built-in JSON editor to define products, stocks, flows, and cost parameters.
4. **Simulate:** Click "Run Turn" to progress the simulation, or "Reset" to restart.
5. **Analyze:** Use dashboards and tables to compare results, costs, and stock flows.
6. **Export/Import:** Copy JSON config and results for further analysis or sharing.

## Architecture & Philosophy

- **Transparency:** All cost and flow logic is visible and modifiable by users.
- **Extensibility:** Abstracted structure allows easy addition of new flows, products, or cost types.
- **No Dependencies:** All logic is pure JavaScript/CSS/HTML, ensuring maximum portability and future-proofing.
- **Designed for Learning:** UI and code are intentionally readable to help bridge business and digital skills.

## Limitations

- Not designed for real-time, enterprise-grade planning or multi-user scenarios.
- Simulation is single-threaded; performance may degrade with very large scenarios.
- Intended for educational, demonstration, and prototyping purposes.

## License

MIT License.

---

## Author & Contact

Questions or suggestions?  
Feel free to open an issue or contact the author via GitHub.
