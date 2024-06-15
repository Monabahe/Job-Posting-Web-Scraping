# Job Postings Web Scraping

## Project Overview
The **Job Postings Web Scraping** project involves extracting more than 10,000 job postings from the Instahyre website using Selenium, a powerful web scraping library. The extracted data is then processed and cleaned using Pandas, resulting in a structured and clean dataset ready for further analysis.

## Tools Used
- **Selenium**: For web scraping to automate the extraction of job postings.
- **Pandas**: For data manipulation and cleaning.

## Project Steps

### 1. Web Scraping Setup
- Installed and configured Selenium, including the appropriate WebDriver for the browser.
- Wrote scripts to navigate the Instahyre website, locate job postings, and extract relevant information such as job titles, companies, locations, and descriptions.

### 2. Data Extraction
- Developed a scraping script to iteratively collect data from multiple pages.
- Ensured efficient and respectful scraping by implementing appropriate delays between requests to avoid overloading the server.

### 3. Data Storage
- Stored the extracted data in a structured format using a Pandas DataFrame.
- Saved interim data to CSV files to ensure data persistence in case of interruptions.

### 4. Data Cleaning
- Loaded the extracted data into Pandas for cleaning.
- Performed data cleaning tasks including:
  - Removing duplicates.
  - Handling missing values.
  - Standardizing formats (e.g., date formats, text casing).
- Validated the data to ensure consistency and accuracy.

### 5. Data Analysis (Optional)
- Conducted preliminary analysis to gain insights into the job postings.
- Explored key metrics such as the number of job postings by company, location, and job title.

## Repository Structure
- `scraping/`: Contains the Selenium scripts for web scraping.
- `data/`: Stores raw and cleaned data files.
- `notebooks/`: Includes any Jupyter notebooks used for data cleaning and analysis.
- `README.md`: Project description and overview.

## How to Use
1. Clone the repository to your local machine.
3. Run the python file selenium craping script located in the `Web Scraping Project 1.0/` folder:
4. Load the extracted data into a Pandas DataFrame and perform any additional data cleaning as needed.

## Conclusion
This project successfully demonstrates the use of Selenium for web scraping and Pandas for data cleaning. By extracting a substantial number of job postings from Instahyre and processing them into a clean dataset, this project provides a valuable resource for job market analysis and insights.

---

Feel free to contribute to this project by suggesting improvements, reporting issues, or submitting pull requests. Happy scraping!
