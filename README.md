## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

# About

- This is a Responsive Admin Dashboard displaying a Bar chart and styled with tailwind

# dependencies

- react-icons
- react-chartjs-2
- chart.js

# Explaing `BarChart.jsx`

**Imported Dependencies**

- Chart as ChartJS,
- Tooltip,
- Legend,
- LinearScale,
- BarElement,
- Title,
- CategoryScale,

**Rest of `BarChart.js` code**

- chartData: This state variable manages the data that will be displayed on the bar chart.
- chartOptions: This state variable manages the configuration options for the chart.
- The useEffect hook is used to set up the initial state of chartData and chartOptions. It runs once when the component is mounted (due to the empty dependency array []), initializing the chart data and options.
- In the useEffect function, chartData is set to an object containing labels "days of the week" and a single dataset. The dataset represents daily sales data.
- chartOptions is set to an object containing configuration options for the chart, including legend position, chart title, and responsiveness settings.
