# EV Charging Location

[![Downloads](https://img.shields.io/github/downloads/aimms/ev-charging-locations/total?style=for-the-badge&logo=github&labelColor=000081&color=1847c9)](https://github.com/aimms/ev-charging-locations/releases)
![AIMMS Version](https://img.shields.io/badge/AIMMS-24.5-white?style=for-the-badge&labelColor=009B00&color=00D400)
![WebUI Version](https://img.shields.io/badge/WebUI-24.12.4.2-white?style=for-the-badge&labelColor=009B00&color=00D400)
![WebUI Version](https://img.shields.io/badge/DEX-24.5.1.1-white?style=for-the-badge&labelColor=009B00&color=00D400)

This repository contains a functional AIMMS example for optimizing the **placement and sizing of electric vehicle (EV) charging stations**. It demonstrates how to solve a capacitated facility location problem (CFLP) within a geospatial context using metaheuristic optimization.

## 🎯 Business Problem

As EV adoption grows, urban planners face the challenge of building accessible and cost-effective infrastructure. This model helps address:
- **Minimize Infrastructure Costs:** Balancing construction and maintenance expenses.
- **Reduce Range Anxiety:** Positioning stations to ensure vehicles can reach them within their battery limits.
- **Demand Fulfillment:** Matching station capacity (number of chargers) with expected vehicle visit probabilities.
- **Accessibility:** Maximizing the reach of the charging network in continuous urban spaces.

## 📖 How to Use This Example

To get the most out of this model, we highly recommend reading our detailed step-by-step guide on the AIMMS Community:

👉 **[Read the Full Article: EV Charging Location Guide](https://how-to.aimms.com/Articles/655/655-ev-location.html)**

### Prerequisites
- **AIMMS:** You will need AIMMS installed to run the model. [Download the Free Academic Edition here](https://www.aimms.com/support/licensing/).
- **WebUI:** This application makes extensive use of the Map Widget and data-dependent CSS styling to visualize the "swarm" of potential solutions.

### Technical Highlights
- **Particle Swarm Optimization (PSO):** Implements the Vulture algorithm to navigate non-linear, non-convex search spaces.
- **Geospatial Optimization:** Uses real-time adjustments of "particles" (stations) as they converge toward an optimal configuration.
- **Capacity Constraints:** Manages complex limits, such as a maximum of eight chargers per station and vehicle range decay functions.



## 🚀 Getting Started

1. **Download the Release:** Go to the [Releases](https://github.com/aimms/ev-charging-locations/releases) page and download the `.zip` file.
2. **Open the Project:** Launch the `.aimms` file.
3. **Run the PSO:** Use the WebUI workflow to initialize the problem and watch the algorithm iterate through generations on the map.
4. **Compare Scenarios:** Adjust maintenance costs or vehicle ranges using sliders to see how the optimal layout shifts.

## 🤝 Support & Feedback

This example is maintained by the **AIMMS User Support Team**.
- Found an issue? [Open an issue](https://github.com/aimms/ev-charging-locations/issues).
- Questions? Reach out via the [AIMMS Community](https://community.aimms.com).

---
*Maintained by the AIMMS User Support Team. We optimize the way you build optimization.*
