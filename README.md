# European Social Survey (ESS) 2016/17: Climate Change Attitudes in Europe

## Overview

In this project, I examined European attitudes towards climate change using data from the European Social Survey (ESS) Round 8 (2016/17). As a data journalist, I sought to understand the prevailing concerns regarding climate change across different European countries. The analysis is presented through an interactive dashboard built in Tableau, showcasing key findings on public opinions about climate change, energy sources, and cross-country comparisons.

```/European-Climate-Change-Attitudes
│
├── /data/
│   └── Climate Data Clean.xlsx      # Cleaned dataset for the analysis
│
├── /visualizations/
│   └── Climate_Change_Dashboard.twbx # File .twbx of Tableau with the dashboard
│
├── /documentation/
│   └── ESS Documentation.pdf        # Complete ESS survey documentation
│
└── README.md                        # Project overview and instructions
```
## The Dataset

The dataset used for this analysis comes from the ESS Round 8 Full Data with over 40,000 respondents across 23 countries. The variables of interest were extracted from the Climate Change section of the survey, with pre-cleaned data provided in the file `Climate Data Clean.xlsx`. These questions focus on several aspects of climate change, including:

- How worried Europeans are about climate change
- Preferences for various energy sources (e.g., solar, wind, coal)
- Differences in opinions across countries

## Questions Explored

During the course of the analysis, I aimed to answer the following questions:

1. What was the general opinion of Europe on climate change?
2. How worried were Europeans about the potential impacts of climate change?
3. What were European preferences towards different energy sources (solar, wind, coal, etc.)?
4. How did these opinions differ between European countries?

These questions guided my analysis and visualization, leading to the creation of an interactive dashboard in Tableau, which enables users to explore European perspectives on climate change in 2016-17.

## Methodology

### Data Preparation

The data was partially cleaned in the provided file. Missing value codes (e.g., 55, 66, 77) were replaced with NA to facilitate a smooth analysis. Further cleaning steps involved filtering the dataset to focus on relevant variables for climate change and energy preferences.

### Visualization and Analysis

Using Tableau, I created visualizations that adhere to the principles of Graphical Excellence. The dashboard allows users to:

- Explore public sentiment towards climate change.
- Visualize preferences for different energy sources across European countries.
- Compare attitudes across countries using geographic maps and bar charts.

Key features of the dashboard include dynamic filters, color-coded heatmaps, and clear labels to enhance user interaction and understanding. The choices for visualizations were grounded in best practices, ensuring that the data is represented clearly and meaningfully.

## Insights from the Data

Here are some key insights gathered from the dashboard:

1. **General Opinion on Climate Change**: A significant majority of Europeans believe that climate change is real and poses a threat, although the level of concern varies between countries.

2. **Worry About Climate Change**: While countries like Sweden and Germany express higher levels of concern, countries like Poland and Hungary showed relatively lower levels of worry about climate change.

3. **Energy Preferences**: There was strong support for renewable energy sources such as wind and solar across Europe. Countries like Germany and Denmark expressed high preferences for these sources, while reliance on coal and natural gas was less favored, though opinions varied between regions.

4. **Country Differences**: Notable differences were found in attitudes across countries, with Southern European nations showing greater concern for energy prices, while Northern European nations were more focused on the environmental impact.

## Dashboard

The final dashboard was built with user experience in mind, allowing for easy exploration of climate attitudes across countries. Users can filter by country, energy source, and concern level. The dashboard is available in the Tableau workbook `Climate_Change_Dashboard.twbx`.

## Conclusion

This analysis highlights the diverse perspectives on climate change across Europe and underscores the importance of renewable energy sources in shaping future policies. By presenting these findings through an interactive Tableau dashboard, I aimed to make the data accessible and engaging for a broad audience, from policymakers to the general public.

## Files

- [`Climate_Change_Dashboard.twbx`](visualizations/Climate_Change_Dashboard.twbx): Tableau workbook containing the dashboard.
- [`Climate Data Clean.xlsx`](data/Climate%20Data%20Clean.xlsx): The cleaned dataset used for this analysis.
- [`ESS Documentation.pdf`](documentation/ESS%20Documentation.pdf): Documentation of the full ESS survey.


## How to Run the Dashboard

1. Download Tableau Desktop (if you don't already have it).
2. Open the `Climate_Change_Dashboard.twbx` file.
3. Explore the data interactively by filtering for specific countries or energy preferences.
