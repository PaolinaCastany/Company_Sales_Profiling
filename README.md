# Project: Data Profiling and Analysis of Company Data Using Python ![icons8-python-48](https://github.com/swaapnaa/PYTHON_PROJECTS/assets/149737403/32f187c4-66ee-4288-9439-38a6b3950a14)

In this project, the objective was to perform data profiling and in-depth analysis on a multi-sheet Excel dataset containing information on companies, investments, acquisitions, and employees. The analysis included cleaning, transformation, and exploratory data visualization to uncover actionable insights. The dataset comprised four key sheets:

## COMPANY: Firmographic Details
- Included firmographic details such as location, industry, founding dates, and operational status.
- **Insights**:
  - Identified 1,000 unique companies, with the United States having the highest representation.
  - Categorized companies as:
    - **Active**: 67.4%
    - **Exited**: 32.2%
    - **Closed**: 0.4%
  - Explored the distribution of U.S.-based companies by state.

## INVESTMENT: Funding Data
- Included funding amounts and types of investments.
- **Insights**:
  - Converted funding amounts to USD for consistency across currencies.
  - Found that 935 companies received investments, with Reliance Jio being the most funded ($24.4B).
  - Analyzed funding patterns by type (e.g., Seed, Series A) and by industry.

## ACQUISITION: Details on Acquisitions
- Included acquisition types and announcement dates.
- **Insights**:
  - Microsoft was identified as the company with the highest number of acquisitions (235).
  - Determined that 94.16% of acquired companies also received investments.
  - Calculated an average time to acquisition as 38 years and 224 days after founding.

## EMPLOYEE: Employee Data
- Included job titles and educational backgrounds.
- **Insights**:
  - Found 20,702 unique employees, with an average of 21 employees per company.
  - Highlighted top job titles (e.g., Software Engineer, CEO, Product Manager) and identified Microsoft as employing the most diverse job roles (1,130 unique titles).
  - Explored educational affiliations, identifying employees from top universities (e.g., Stanford, MIT, Harvard) in 322 companies.


## Key Tools and Techniques
- **Tools Used**:
  - Python libraries:
    - `pandas` for data manipulation
    - `matplotlib` for visualization
    - `numpy` for calculations
- **Techniques**:
  - Cleaned data by handling missing values and standardizing formats for analysis.
  - Conducted advanced data transformations, such as currency conversion, text parsing, and merging datasets to explore relationships across sheets.
