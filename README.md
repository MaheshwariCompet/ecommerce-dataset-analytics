# E-commerce dataset analytics to the FCRA framework using Pandas and Matplotlib.

An end-to-end evaluation dashboard mapping an **India E-commerce dataset** to the operational **FCRA**  framework using Python, Pandas, and Matplotlib.

---

## 🏛️ Framework Architecture & Data Mapping

To bridge the gap between theoretical evaluation metrics and practical enterprise logs, this project maps real-world e-commerce variables to the four core lifecycle pillars:

| FCRA Pillar | Pipeline Operation | E-commerce Log Proxy | Operational Definition |
| :--- | :--- | :--- | :--- |
| **🔍 Find** | Data Ingestion & Indexing | `region` mapping | Evaluates if the system successfully discovered inventory allocated to the customer's spatial region. |
| **✂️ Chunk** | Context Chunking & Routing | `courier_partner` allocation | Represents data packet splitting and optimization across mainstream data ingestion routing pipelines. |
| **🤖 Retrieve** | Context Retrieval Latency | `is_late_delivery` flags | Measures if the vector database successfully fetched available real-time contexts within optimal shipping parameters. |
| **💬 Answer** | LLM Output Quality Check | `review_rating` metrics | Validates the accuracy of the final generated prompt layout. High ratings mean perfect answers; low ratings represent hallucinations. |

---

## 📊 Dashboard Visualizations

The generated Python script processes thousands of dataset transactions to render a dual-visualization evaluation window:
1. **Grouped Bar Graph (Left):** Side-by-side comparison of **System Pass vs. System Fail** counts across each independent FCRA operational step. Text labels use automatic multi-line wrapping (`\n`) for clean horizontal legibility.
2. **Pie Chart (Right):** A percentage-based compositional breakdown tracking the foundational **Geographic Workload Share** across major Indian territories to highlight processing density clusters.

---

## 🚀 Getting Started

### 📦 Prerequisites
Ensure you have Python 3.10+ installed and the required data science libraries configured:
```bash
pip install pandas matplotlib
```

### 📂 Directory Structure
Place your dataset and the script in the same working directory:
```text
📂 ecommerce-dataset-analytics/
 ├── 📊 india_ecommerce_orders_returns.csv  <- Dataset file
 ├── 🐍 Ecommerce.py                             <- Execution script
 └── 📝 README.md                           <- Documentation
```

### 💻 Running the Dashboard
Run the Python script directly from your terminal or click the **Play Button (▶)** inside Visual Studio Code:
```powershell
python Ecommerce.py
```
*(Note: If the chart window opens hidden, check your system taskbar for the running plotting canvas icon.)*
