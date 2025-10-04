# Basic Guide to Data Preprocessing

<p style="text-align: justify;"></p>

## Introduction to Data Preprocessing

<p style="text-align: justify"> </p>

### What's involves in Data Preprocessing?
<p style="text-align: justify"> </p>

### What's the purpose of Data Preprocessing?
<p style="text-align: justify"> </p>

## Types of Data Preprocessing

<p style="text-align: justify"> </p>

### Transformation

#### Log Transformation
- Compresses large values more strongly.
- Best when data is right-skewed with extreme outliers <br> (e.g., income, durations, counts).
- Example: Track duration → most songs are 3–5 mins, but some are 20+ mins → log brings long songs closer to the rest.

#### Square Root Transformation
- Less aggressive than log.
- Useful for moderately skewed data (not too many extreme values).
- Works well for count-like features (e.g., number of events, likelihood scores).

<p style="text-align:justify"> Line Graph is a visualization used to display quantitative values across a continuous interval or over time. It shows trends and how data changes over a period. </p>

<div style="display: flex; justify-content: center">
<!-- <img src="https://datavizcatalogue.com/methods/images/anatomy/line_graph.png" alt="Line Chart Graph"> -->
</div>

#### How to Read
Data points are plotted on a Cartesian coordinate grid and connected with lines.
- X-axis: usually a timescale or sequence of intervals.
- Y-axis: represents the quantitative values (can include negative values below the axis).

- Trends:
    - Upward slope = increasing values
    - Downward slope = decreasing values

- Patterns formed by the line can reveal trends in the dataset.

#### Tips
- Use to show changes or trends over time.
- Limit to 3–4 lines per chart to avoid clutter.
- If more comparisons are needed, use small multiples (separate charts for each series).

### Bar Charts
<p style="text-align: justify"> A bar chart uses horizontal or vertical bars to compare numerical values across categories. </p>

<div style="display: flex; justify-content: center">
<!-- <img src="https://datavizcatalogue.com/methods/images/anatomy/bar_chart.png"> -->
</div>

#### How to Read
- X-axis / Y-axis: one shows categories, the other shows numerical values.
- The length/height of each bar represents the value for that category.
- Used to answer “how many?” in each category.

#### Tips
- Best for <b>categorical</b> (discrete) data, not continuous intervals.
- Do not confuse with histograms (which show continuous distributions).
- Choose between horizontal vs. vertical bars depending on readability.

### Histogram
A histogram is a chart that shows the distribution of data over a continuous interval. It groups values into intervals (bins) and uses bars to represent the frequency of data within each bin.

#### How to Read
- X-axis: the continuous intervals (bins).
- Y-axis: frequency (how many values fall into each bin).
- Bar height = frequency of data in that interval.
- Helps identify where values are concentrated, extremes, gaps, or unusual values.

#### Tips

### Pie Charts

### Scatter Plots

### Heatmaps
<p style="text-align: justify"></p>


## Principles of Effective Visualization

## Tools and Libraries

## Step-by-step Examples

## Common Pitfails

## Best Practices
