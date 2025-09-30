# Step 1: 📈 COVID-19 Confirmed Cases Visualization:
This notebook loads global COVID-19 case data from [Our World in Data](https://github.com/datasets/covid-19) and visualizes confirmed cases over time for six key countries using Plotly.
🔧 Workflow Overview:
- Loads daily case counts from a public CSV and parses dates.
- Reshapes the data to compare countries side-by-side.
- Converts to long format for Plotly compatibility.
- Generates an interactive line chart with hover, zoom, and legend toggle features.
An interactive time-series chart showing the progression of confirmed COVID-19 cases across selected countries.
Ideal for exploring trends, teaching time-series visualization, or integrating into dashboards.

# Step 2: COVID-19 Cases by Country (Pie Chart)
This section visualizes the most recent confirmed COVID-19 case totals across selected countries using an interactive pie chart.

- Extracts the latest row from the time-series dataset (`df_regional`) to get current case counts.
- Prepares country names (`activities`) and their corresponding case totals (`slices`) for plotting.
- Uses Plotly’s `go.Pie` to create a colorful, interactive pie chart showing each country’s share.
- Includes hover tooltips with exact values and percentages, and a slight "pull" effect to separate slices visually.

> This chart offers a quick snapshot of how total cases are distributed among the selected countries.
