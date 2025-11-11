# Setup and Usage Guide

This guide will help you set up and use the Data Science Jobs Salaries Dashboard in Tableau.

## Prerequisites

- **Tableau Desktop** (version 2020.1 or later recommended)
  - Download from: https://www.tableau.com/products/desktop
- Basic understanding of Tableau workbooks and data connections

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Muhammedthwaha/-Data-Science-Jobs-Salaries-Dashboard-Tableau-.git
cd -Data-Science-Jobs-Salaries-Dashboard-Tableau-
```

### 2. Explore the Data

The sample dataset is located in the `data/` directory:
- `ds_salaries_sample.csv` - Sample data with Data Science job salaries

Review the [Data Dictionary](DATA_DICTIONARY.md) to understand the fields and their meanings.

### 3. Open in Tableau

1. Launch Tableau Desktop
2. Click on "Connect" → "Text file"
3. Navigate to the `data/` directory and select `ds_salaries_sample.csv`
4. Tableau will load the data and show the Data Source tab

### 4. Creating Your Dashboard

You can create visualizations to explore:
- Salary trends by experience level
- Average salaries by job title
- Geographic distribution of salaries
- Remote work vs. on-site salary comparisons
- Company size impact on compensation
- Year-over-year salary changes

### 5. Opening Existing Dashboards

If there are pre-built Tableau workbooks in the `dashboard/` directory:
1. Open Tableau Desktop
2. Go to File → Open
3. Navigate to the `dashboard/` directory
4. Select the `.twb` or `.twbx` file

## Dashboard Components

The dashboard typically includes:
- **Overview**: Summary statistics and key metrics
- **Salary Analysis**: Detailed salary breakdowns by various dimensions
- **Geographic View**: Map visualizations showing global salary distribution
- **Trends**: Time-series analysis of salary changes
- **Role Comparison**: Interactive comparison of different job roles

## Customization

### Adding Your Own Data

1. Prepare your data in CSV format following the structure in `ds_salaries_sample.csv`
2. Place your file in the `data/` directory
3. In Tableau, go to Data Source and connect to your new file
4. The dashboard will update automatically with your data

### Modifying Visualizations

- Use Tableau's drag-and-drop interface to modify charts
- Add filters to focus on specific subsets of data
- Create calculated fields for custom metrics
- Adjust colors and formatting to match your preferences

## Tips for Best Results

1. **Data Quality**: Ensure your data follows the same format as the sample
2. **Performance**: For large datasets, consider using Tableau extracts (.hyper files)
3. **Filters**: Use dimension filters to focus on specific aspects
4. **Interactivity**: Add actions to enable cross-filtering between sheets

## Troubleshooting

### Data Connection Issues
- Verify the CSV file is properly formatted
- Check that all required columns are present
- Ensure there are no special characters causing parsing errors

### Performance Issues
- Create a data extract instead of using live connection
- Reduce the number of marks displayed
- Optimize calculated fields

## Resources

- [Tableau Documentation](https://help.tableau.com/)
- [Tableau Community Forums](https://community.tableau.com/)
- [Data Dictionary](DATA_DICTIONARY.md)

## Contributing

To contribute to this project:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Support

For questions or issues, please open an issue on the GitHub repository.
