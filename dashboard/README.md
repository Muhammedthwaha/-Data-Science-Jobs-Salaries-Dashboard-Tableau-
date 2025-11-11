# Dashboard Files

This directory contains Tableau workbook files for the Data Science Jobs Salaries Dashboard.

## File Types

- **`.twb`** - Tableau Workbook files (require separate data connection)
- **`.twbx`** - Tableau Packaged Workbook files (include embedded data)

## Usage

1. Open Tableau Desktop
2. Go to File → Open
3. Navigate to this directory
4. Select the workbook file you want to open

## Creating New Dashboards

When creating new dashboards:
1. Connect to the data source in the `data/` directory
2. Build your visualizations
3. Save the workbook in this directory
4. Use descriptive file names (e.g., `salary_analysis_by_role.twb`)

## Best Practices

- Save as `.twbx` if you want to share the dashboard with embedded data
- Save as `.twb` for version control and when data is stored separately
- Document any custom calculations or parameters used
- Consider performance when building complex dashboards

## Note

Tableau workbook files will be added as the dashboard is developed.
