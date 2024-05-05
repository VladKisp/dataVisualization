# Data Visualization Library

This library provides functions for creating basic data visualizations in JavaScript. It currently supports the creation of bar charts, line charts, and pie charts.

## Installation

You can install the package via npm:

```bash
npm install data-visualization-js
```

## Usage

```javascript
const dataVisualization = require('data-visualization-js');

const barChartData = [10, 20, 30, 40, 50];
const barChartOptions = { title: 'My Bar Chart' };
dataVisualization.createBarChart(barChartData, barChartOptions);

const lineChartData = [5, 10, 15, 20, 25];
const lineChartOptions = { title: 'My Line Chart' };
dataVisualization.createLineChart(lineChartData, lineChartOptions);

const pieChartData = [30, 20, 50];
const pieChartOptions = { title: 'My Pie Chart' };
dataVisualization.createPieChart(pieChartData, pieChartOptions);
```

## API Reference

### `createBarChart(data, options)`

Creates a bar chart with the specified data and options.

- `data`: An array of numerical values representing the data points.
- `options`: An object containing chart configuration options (optional).

### `createLineChart(data, options)`

Creates a line chart with the specified data and options.

- `data`: An array of numerical values representing the data points.
- `options`: An object containing chart configuration options (optional).

### `createPieChart(data, options)`

Creates a pie chart with the specified data and options.

- `data`: An array of numerical values representing the data points.
- `options`: An object containing chart configuration options (optional).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
