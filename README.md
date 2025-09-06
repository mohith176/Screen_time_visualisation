# Screen Time Visualizations 📱📊

- This project effectively combines data science with interactive web design to provide meaningful insights into modern digital behavior patterns.

- This is a comprehensive data visualization project that analyzes global screen time patterns and their relationship with happiness levels. The project creates an interactive dashboard with multiple visualization types to explore different aspects of digital device usage across various demographics and geographic regions.



## [Usage Guide](https://youtu.be/mxZurvgmbfA?feature=shared)

### Navigation
- Use the navigation bar to switch between the three main visualizations
- Toggle between light and dark themes using the theme switcher
- Each visualization section has its own interactive controls

### Interaction Features
- **Hover Effects**: Hover over map regions, chart elements, or heatmap cells for detailed information
- **Filtering**: Use dropdown menus and buttons to filter data by age groups, time periods, or countries
- **Toggle Views**: Switch between different chart types within visualizations 1 and 2
- **Responsive Design**: Works seamlessly across desktop, tablet, and mobile devices

## Features

### Visualization 1: Global Analysis
- **Choropleth Map (vis1a.html)**: Interactive world map showing happiness levels and screen time by country
  - Toggle between happiness scores and average screen time
  - Age group filtering (Under 18, 18-24, 24-36, 36-48, 48-64, 64+)
  - Country-specific tooltips with detailed statistics
  - Dynamic color-coded legend

- **Correlation Analysis (vis1b.html)**: Scatter plot examining the relationship between screen time and happiness
  - Interactive age group selection
  - Correlation trend lines
  - Statistical insights

### Visualization 2: Individual Usage Patterns  
- **Radar Chart (vis2a.html)**: Multi-dimensional analysis of screen time distribution
  - Interactive age group selection
  - Device category breakdown (Mobile, Laptop, TV)
  - Monthly insights and statistics
  - Animated transitions and hover effects

- **Pie Chart (vis2b.html)**: Device usage distribution
  - Proportional representation of screen time by device type
  - Interactive slice selection
  - Smooth animations and transitions

### Visualization 3: Time-Based Analysis
- **Heatmap (vis3.html)**: Peak usage times analysis
  - 24-hour x 7-day usage pattern visualization
  - Week-by-week filtering (Weeks 1-4)
  - Age group segmentation (10-20, 21-30, 31-40, 41-50 years)
  - Intensity-based color coding
  - Interactive tooltips showing exact usage hours

## Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Visualization Library**: D3.js v7
- **Styling**: Tailwind CSS
- **Animations**: GSAP (GreenSock)
- **Data Format**: CSV
- **Deployment**: GitHub Pages

## Data Sources

The visualizations utilize multiple datasets:

1. **Global Happiness & Screen Time Data** (`final_data_with_iso.csv`)
   - 150+ countries with happiness scores and screen time averages
   - Age-segmented data (6 age groups)
   - ISO country codes for map integration

2. **Detailed Usage Patterns** (`finaldata.csv`, `screen_time_3_months.csv`)
   - Hourly usage patterns across days of the week
   - Multi-week tracking data
   - Age group demographics
   - Device-specific usage statistics

3. **Geographical Data** (`world.geojson`)
   - World map boundaries for choropleth visualization
   - Country polygons with proper projections

## Key Insights

The visualizations reveal several interesting patterns:

1. **Geographic Variations**: Nordic countries show high happiness levels with moderate screen time
2. **Age-Related Trends**: Younger demographics tend to have higher screen time usage
3. **Temporal Patterns**: Peak usage typically occurs during evening hours (7-10 PM)
4. **Device Distribution**: Mobile devices dominate screen time across most age groups
5. **Weekly Patterns**: Usage peaks on weekends and mid-week periods


