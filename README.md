
# 🚗 Automobile Sales Statistics Dashboard*  
> An interactive data visualization dashboard built with Python, Dash, and Plotly


## 📊 Project Overview

This project is part of the **IBM Data Analyst Professional Certificate** on Coursera. The goal was to analyze automobile sales data and build an interactive dashboard that visualizes how sales were affected during **recession periods** and across **yearly statistics**.

The dashboard allows users to switch between two report types:
- 📉 **Recession Period Statistics** — Analyzes sales trends during economic downturns
- 📈 **Yearly Statistics** — Explores annual sales performance by year

---

## 🖥️ Dashboard Preview

### Recession Period Statistics
![Recession Dashboard](screenshots/recession_dashboard.png.png)

### Yearly Statistics (Year: 1980)
![Yearly Dashboard](screenshots/yearly_dashboard.png)

---

## 📌 Features

- **Interactive Dropdowns** — Select report type and filter by year
- **4 Dynamic Charts per View** — Line charts, bar charts, and pie charts
- **Recession Report Charts:**
  - Average automobile sales fluctuation over recession years (Line Chart)
  - Average vehicles sold by vehicle type (Bar Chart)
  - Total advertising expenditure share by vehicle type (Pie Chart)
  - Effect of unemployment rate on vehicle type and sales (Bar Chart)
- **Yearly Report Charts:**
  - Yearly automobile sales trend across all years (Line Chart)
  - Total monthly automobile sales for selected year (Line Chart)
  - Average vehicles sold by vehicle type in selected year (Bar Chart)
  - Total advertising expenditure per vehicle type (Pie Chart)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python 3 | Core programming language |
| Dash | Web application framework |
| Plotly | Interactive chart library |
| Pandas | Data manipulation and analysis |
| HTML/CSS (via Dash) | Layout and styling |

---

## 📁 Project Structure

```
automobile-sales-dashboard/
│
├── DV0101EN-Final-Assign-Part-2-Questions.py   # Main dashboard application
├── screenshots/
│   ├── recession_dashboard.png
│   └── yearly_dashboard.png
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.7+ installed.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/automobile-sales-dashboard.git
   cd automobile-sales-dashboard
   ```

2. **Install dependencies**
   ```bash
   pip install dash pandas plotly more-itertools
   ```

3. **Run the app**
   ```bash
   python DV0101EN-Final-Assign-Part-2-Questions.py
   ```

4. **Open in browser**
   ```
   http://127.0.0.1:8050/
   ```

---

## 📂 Dataset

The dataset is automatically loaded from IBM's Cloud Object Storage:

```
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/d51iMGfp_t0QpO30Lym-dw/automobile-sales.csv
```

**Key columns used:**
- `Year` — Year of the record
- `Month` — Month of the record
- `Automobile_Sales` — Number of automobiles sold
- `Vehicle_Type` — Category of vehicle (e.g., ExecutiveCar, Sports, SuperMiniCar)
- `Advertising_Expenditure` — Ad spend for that period
- `unemployment_rate` — Unemployment rate at the time
- `Recession` — Binary flag (1 = recession period, 0 = normal)

---

## 📸 How to Use

1. Launch the app and open it in your browser
2. Use the **"Select Report Type"** dropdown to choose between:
   - `Yearly Statistics`
   - `Recession Period Statistics`
3. If **Yearly Statistics** is selected, use the **year dropdown** to filter by a specific year
4. The year dropdown is **automatically disabled** when viewing Recession Period Statistics

---

## 🎓 Course Information

| Detail | Info |
|--------|------|
| Course | IBM Data Analyst Professional Certificate |
| Module | Data Visualization with Python |
| Course Code | DV0101EN |
| Platform | Coursera / IBM Skills Network |
| Assignment | Final Project — Part 2 |


## 📄 License

This project is for educational purposes as part of the IBM Data Analyst Professional Certificate program.

---

⭐ *If you found this project helpful, feel free to give it a star!*
