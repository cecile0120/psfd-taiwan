# PSFD Taiwan - Panel Study of Family Dynamics

A modern web interface for browsing and exploring variables from the Panel Study of Family Dynamics (PSFD) dataset from Academia Sinica.

## About PSFD

The Panel Study of Family Dynamics (PSFD) is the longest and largest panel study in Taiwan, collecting comprehensive data on families, population, labor, education, health, and psychological studies since 1999. The project is managed by the Center for Survey Research (CSR) at Academia Sinica.

## Features

- **Variable Browser**: Browse and search through PSFD variables by category, wave, and keyword
- **Interactive Filtering**: Filter variables by demographic, family, education, employment, income, health, and psychological categories
- **Wave Selection**: Filter by specific survey waves (1999-2020)
- **Sample Data Preview**: Generate realistic sample data for selected variables
- **Data Export**: Download selected variables in various formats (CSV, SPSS, Stata, R)
- **Responsive Design**: Works on desktop, tablet, and mobile devices

## Dataset Information

- **Start Year**: 1999
- **Total Waves**: 22 (1999-2020)
- **Total Respondents**: 6,000+
- **Coverage**: Taiwan & Southeast China (Shanghai, Zhejiang, Fujian)
- **Institution**: Academia Sinica, Center for Survey Research

## Variable Categories

1. **Demographic**: Basic demographic characteristics
2. **Family**: Family structure and relationships
3. **Education**: Educational attainment and experiences
4. **Employment**: Employment status and work characteristics
5. **Income & Wealth**: Income, wealth, and economic well-being
6. **Health**: Health status and healthcare utilization
7. **Psychological**: Psychological well-being and attitudes

## Usage

1. Open `index.html` in a web browser
2. Use the search and filter options to find variables of interest
3. Select variables by checking the checkboxes
4. View sample data for selected variables
5. Download data in your preferred format

## Data Source

This interface provides access to variables from the Panel Study of Family Dynamics (PSFD). For actual data access and complete documentation, please visit the official PSFD website:

**Official PSFD Website**: https://psfd.sinica.edu.tw/V2/?page_id=966&lang=en

## Technical Details

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **Data Format**: JSON
- **No Build Process**: Pure static files, no compilation required

## File Structure

```
IPUMSTW/
├── index.html              # Main website file
├── data/
│   └── psfd_variables.json # Variable data and metadata
├── README.md               # This file
└── .gitignore             # Git ignore rules
```

## Contributing

To add new variables or modify existing ones:

1. Edit the `data/psfd_variables.json` file
2. Follow the existing structure for variable definitions
3. Include all required fields: name, description, category, coding, moreInfo, availability, waves, dataType
4. For numeric variables, include range and missingValues
5. For categorical variables, include categories array

## License

This project is for educational and research purposes. The PSFD data is owned by Academia Sinica. Please refer to the official PSFD website for data usage terms and conditions.

## Citation

When using PSFD data, please cite according to the official guidelines provided by Academia Sinica. 