## 📘 View the Notebook

If GitHub fails to render the notebook properly, you can view it via NBViewer:

👉 [Click to view notebook in NBViewer](https://nbviewer.org/github/abhinav-77000/SA_Capstone/blob/main/SA_CAPSTONE.ipynb)

# 🚗 Smart Parking Dynamic Pricing System (Pathway + Bokeh)

## 📌 Overview

This project simulates a real-time dynamic pricing system for smart parking lots using streaming data. It leverages Pathway to process parking occupancy data in real time and Bokeh to visualize pricing behavior over time. 

The pricing adapts based on demand indicators like occupancy, queue length, traffic conditions, and special days.

---

## 🧰 Tech Stack

| Tool        | Purpose                        |
|-------------|--------------------------------|
| **Python**  | Core programming language      |
| **Pathway** | Real-time data stream processing |
| **Bokeh**   | Interactive visualizations     |
| **Panel**   | Embedding Bokeh into apps      |
| **Pandas**  | Preprocessing CSV files        |
| **Google Colab** / Jupyter | Development & Testing |

---

## 🏗️ Architecture Diagram

```mermaid
graph TD
    A[CSV Data Input] --> B[Preprocessing with Pandas]
    B --> C[Pathway Streaming Engine]
    C --> D[30-min Tumbling Window]
    D --> E[Demand Calculation]
    E --> F[Price Computation]
    F --> G[Bokeh Plot]
    G --> H[Panel Web App]




