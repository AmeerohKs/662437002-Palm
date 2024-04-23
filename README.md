# Data Science with Python 2023
---
## Prediction Palm Data

### Overview

This is a life cycle project using CRISP-DM as the process. The objective of this project is to gather statistics about car brands and predict car prices.

---

* Tool
    * Anaconda
    * Jupyter lab

* Installation
    * Python v.3
    * Python libraries:
        * sklearn.
        * Pandas.
        * numpy.
        * seaborn
        * matplotlib.

## Methodology

### 1. Business Understanding
---
Wold like to know what month the palm fruit will cost the most to prepare our palm for a larger yield in that month.

### 2. Data Understanding
---
Information taken from (https://www.kaggle.com/datasets/missionjee/car-sales-report](https://mis-app.oae.go.th/service/id/opendata/34) as a CSV file.

### 3. Data Preparation
---
- Check data missing in table.
![Data Missing](https://github.com/AmeerohKs/662437002-Palm/blob/main/df.info().png)

- Drop columns:
  - MARKET_NAME
![Drop Columns](https://github.com/AmeerohKs/662437002-Palm/blob/main/PD.info().png)

- Filter the name of Product
Filter only "ผลปาล์มน้ำมันทั้งทะลาย นน.> 15 กก. ขึ้นไป"

- Change the the name of the months
Change Thai string months to number

- Replace the data name
Replace the long data name to be shorter

- Data Visualization and Interpretation:
  - Make a graph of productivity and price
  - Univariate and Bivariate Analysis

Conclusion:
  - The lowest price of palm is in the 10th month of 2018.
  - Palm prices were the highest in the 11th month of 2018.





