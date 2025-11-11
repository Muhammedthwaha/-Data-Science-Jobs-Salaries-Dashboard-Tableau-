# Data Science Jobs Salaries Dashboard (Tableau)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Tableau](https://img.shields.io/badge/Tableau-2020.1+-E97627?logo=tableau&logoColor=white)](https://www.tableau.com/)

This project presents a comprehensive Tableau dashboard analyzing salaries across various roles in the Data Science & Analytics industry. The dashboard provides interactive visualizations to explore salary trends, distributions, and patterns across different dimensions such as experience level, job role, location, and company size.

## 📊 Overview

This dashboard helps answer questions like:
- What is the average salary for different Data Science roles?
- How do salaries vary by experience level?
- What's the impact of remote work on compensation?
- Which locations offer the highest salaries?
- How do company sizes affect salary ranges?
- What are the salary trends over recent years?

## 🗂️ Repository Structure

```
├── data/                      # Data files
│   └── ds_salaries_sample.csv # Sample dataset
├── dashboard/                 # Tableau workbook files (.twb, .twbx)
├── images/                    # Dashboard screenshots and visualizations
├── docs/                      # Documentation
│   ├── DATA_DICTIONARY.md     # Data field descriptions
│   └── SETUP_GUIDE.md         # Setup and usage instructions
├── .gitignore                 # Git ignore file
├── LICENSE                    # MIT License
└── README.md                  # This file
```

## 🚀 Quick Start

### Prerequisites
- Tableau Desktop (version 2020.1 or later)

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Muhammedthwaha/-Data-Science-Jobs-Salaries-Dashboard-Tableau-.git
   cd -Data-Science-Jobs-Salaries-Dashboard-Tableau-
   ```

2. **Open Tableau Desktop**

3. **Connect to the data**
   - Click "Connect" → "Text file"
   - Navigate to `data/ds_salaries_sample.csv`

4. **Start exploring!**
   - Create your own visualizations, or
   - Open pre-built workbooks from the `dashboard/` directory (if available)

For detailed setup instructions, see the [Setup Guide](docs/SETUP_GUIDE.md).

## 📈 Dashboard Features

### Key Visualizations
- **Salary Distribution**: View salary ranges across different roles
- **Experience Level Analysis**: Compare compensation by seniority
- **Geographic Insights**: Interactive map showing global salary patterns
- **Remote Work Impact**: Analyze salary differences for remote vs. on-site positions
- **Temporal Trends**: Track salary changes over time
- **Company Size Comparison**: Understand how organization size affects pay

### Interactive Filters
- Filter by job title, experience level, location
- Adjust time ranges and remote work preferences
- Focus on specific company sizes or employment types

## 📋 Data Dictionary

The dataset includes the following key fields:
- **work_year**: Year of salary data
- **experience_level**: EN (Entry), MI (Mid), SE (Senior), EX (Executive)
- **employment_type**: FT (Full-time), PT (Part-time), CT (Contract), FL (Freelance)
- **job_title**: Specific role name
- **salary_in_usd**: Standardized salary in USD
- **remote_ratio**: 0 (On-site), 50 (Hybrid), 100 (Remote)
- **company_size**: S (Small), M (Medium), L (Large)

For complete field descriptions, see the [Data Dictionary](docs/DATA_DICTIONARY.md).

## 🛠️ Usage

### Analyzing Your Own Data

1. Prepare your data following the same structure as `ds_salaries_sample.csv`
2. Place your CSV file in the `data/` directory
3. In Tableau, update the data source connection
4. The visualizations will automatically update

### Customizing the Dashboard

- Modify chart types and layouts
- Add new calculated fields
- Create custom filters and parameters
- Adjust color schemes and formatting

See the [Setup Guide](docs/SETUP_GUIDE.md) for detailed instructions.

## 📸 Screenshots

_(Screenshots of the dashboard will be added to the `images/` directory)_

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Data Science community for salary transparency
- Tableau for providing excellent visualization tools
- Contributors who help improve this dashboard

## 📧 Contact

**Muhammed Thaha Uwais**
- GitHub: [@Muhammedthwaha](https://github.com/Muhammedthwaha)

## 🔗 Resources

- [Tableau Public Gallery](https://public.tableau.com/app/discover)
- [Tableau Learning Resources](https://www.tableau.com/learn)
- [Data Dictionary](docs/DATA_DICTIONARY.md)
- [Setup Guide](docs/SETUP_GUIDE.md)

---

⭐ If you find this project useful, please consider giving it a star!
