# 🌍 CarbonWise 360 - EV vs Petrol Carbon Analysis

## ✨ Beautiful Space-Themed Dashboard

A stunning dark teal/emerald space-themed dashboard for analyzing carbon emissions between Electric Vehicles and Petrol vehicles over a 10-year projection.

---

## 🚀 Quick Start

```bash
npm install
npm start
```

Open **http://localhost:3000** and enjoy!

---

## 🎨 Design Features

- **Space Theme**: Dark teal/emerald gradient with animated stars and glowing orbs
- **Line Chart**: 10-year carbon projection comparing EV vs Petrol
- **Modern UI**: Glassmorphism effects with backdrop blur
- **Responsive**: Works on all screen sizes
- **All Indian States**: Complete list of 28 states + 8 union territories

---

## 📊 Dashboard Components

### Input Panel
- **State Selector**: All 36 Indian states and union territories
- **Daily KM**: Number input (1-500 km)
- **Years**: Projection period (1-20 years)
- **Run Analysis Button**: Generates the carbon projection

### Carbon Chart
- **10-Year Line Chart**: Shows EV (green) vs Petrol (red) emissions
- **Interactive**: Hover to see exact values
- **Smooth Animations**: Beautiful line transitions

### Insights Panel
- **Recommendation**: EV or Petrol based on total emissions
- **Break-even Year**: When EV becomes more economical
- **Total EV CO₂**: Cumulative emissions for EV
- **Total Petrol CO₂**: Cumulative emissions for Petrol

---

## 🎯 How It Works

1. **Select State**: Choose from all Indian states/UTs
2. **Enter Daily KM**: How many kilometers per day
3. **Set Years**: Projection period (default 10 years)
4. **Click "Run Analysis"**: See the magic happen!

The dashboard generates:
- 10-year carbon emission projections
- EV vs Petrol comparison line chart
- Smart recommendations
- Break-even analysis
- Total CO₂ calculations

---

## 🛠️ Tech Stack

- **React 19.2.4**: Latest React with hooks
- **Recharts 3.7.0**: Beautiful line charts
- **Tailwind CSS 4.2.0**: Modern styling
- **Glassmorphism**: Backdrop blur effects
- **CSS Animations**: Twinkling stars and glowing orbs

---

## 📁 Project Structure

```
src/
├── components/
│   ├── layout/
│   │   └── BackgroundAnimation.jsx  # Space theme with stars
│   ├── dashboard/
│   │   ├── InputPanel.jsx           # State, KM, Years inputs
│   │   ├── CarbonChart.jsx          # Line chart (EV vs Petrol)
│   │   └── InsightsPanel.jsx        # Recommendations & metrics
│   └── pages/
│       └── Dashboard.jsx            # Main page layout
├── App.jsx
├── index.js
└── index.css                        # Tailwind + animations
```

---

## 🎨 Color Scheme

- **Background**: Dark slate → Teal → Emerald gradient
- **EV Line**: Emerald green (#10b981)
- **Petrol Line**: Red (#ef4444)
- **Accents**: Teal (#14b8a6)
- **Text**: White with teal highlights
- **Borders**: Teal with transparency

---

## ✅ Features Checklist

- ✅ All 36 Indian states and union territories
- ✅ Space-themed background with animations
- ✅ Line chart with EV vs Petrol comparison
- ✅ 10-year carbon projection
- ✅ Smart recommendations
- ✅ Break-even year calculation
- ✅ Total CO₂ metrics
- ✅ Glassmorphism UI
- ✅ Responsive design
- ✅ No errors, production-ready

---

## 🎉 Ready to Run!

Just execute:
```bash
npm install && npm start
```

Your beautiful CarbonWise 360 dashboard will be live at **http://localhost:3000**

Enjoy the stunning space-themed carbon analysis experience! 🌍✨
