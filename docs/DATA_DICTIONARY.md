# Data Dictionary

This document describes the data fields used in the Data Science Jobs Salaries dataset.

## Fields Description

| Field Name | Data Type | Description |
|------------|-----------|-------------|
| work_year | Integer | The year the salary was paid |
| experience_level | String | The experience level in the job during the year:<br>- EN: Entry-level / Junior<br>- MI: Mid-level / Intermediate<br>- SE: Senior-level / Expert<br>- EX: Executive-level / Director |
| employment_type | String | The type of employment:<br>- PT: Part-time<br>- FT: Full-time<br>- CT: Contract<br>- FL: Freelance |
| job_title | String | The role worked in during the year |
| salary | Integer | The total gross salary amount paid |
| salary_currency | String | The currency of the salary paid (ISO 4217 currency code) |
| salary_in_usd | Integer | The salary in USD (converted using FX rate) |
| employee_residence | String | Employee's primary country of residence (ISO 3166 country code) |
| remote_ratio | Integer | The overall amount of work done remotely:<br>- 0: No remote work (less than 20%)<br>- 50: Partially remote<br>- 100: Fully remote (more than 80%) |
| company_location | String | The country where the company is located (ISO 3166 country code) |
| company_size | String | The median number of people that worked for the company during the year:<br>- S: Small (less than 50 employees)<br>- M: Medium (50 to 250 employees)<br>- L: Large (more than 250 employees) |

## Sample Data

The `ds_salaries_sample.csv` file contains a representative sample of data science job salaries across different roles, experience levels, and locations.

## Data Sources

This dataset is intended for educational and analytical purposes. It represents typical salary ranges and distributions in the data science and analytics industry.

## Usage Notes

- All salaries are represented in both original currency and USD for easier comparison
- Remote ratio indicates the percentage of remote work allowed
- Experience levels are standardized across different job titles
- Company sizes are categorized based on employee count
