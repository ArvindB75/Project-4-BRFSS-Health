# Project-4
Educational project in group at the end of the Fullstack Data Analysis Jedha Bootcamp about Healthcare

# Health Factors and Pathologies Analysis Project

## Project Objective

The primary objective of this project is to explore and ascertain, through exploratory data analysis (EDA) and machine learning techniques, the various factors that influence the onset of different pathologies.

## Methodology

Our data processing began with cleaning our dataset using the Python libraries, `pandas` and `numpy`. This allowed us to retain only 46 columns and eliminate rows containing missing values. Following this, an extensive exploratory data analysis was carried out using the `Seaborn` and `Matplotlib` libraries. Additionally, we developed an insightful dashboard with Power BI and conducted machine learning tasks with Dataiku.

## Installation Instructions

This project was developed using Python and requires the installation of the following packages:
- pandas
- numpy
- matplotlib
- seaborn

These can be installed using pip:

```
pip install pandas numpy matplotlib seaborn
```

## How to Use the Dataset

The dataset is a CSV file named 'EDA.csv'. It can be loaded into a Python environment using the `pandas` library:

```python
import pandas as pd

data = pd.read_csv('path_to_file/EDA.csv')
```

## Results and Conclusions

- **Key Findings**:

  - BMI plays a pivotal role in the onset of diabetes.
  - Smoking is strongly associated with cardiovascular and pulmonary pathologies.
  - Osteoarthritis is profoundly linked with age.
  - Women are more susceptible to depression compared to men.
  
- **Recommendations**:

  This project has provided invaluable insights and facilitated the application of a considerable portion of our learning from the data analyst bootcamp. In terms of machine learning, several improvements could be integrated, such as incorporating more data or new features. This might encompass dietary habits or the physical demands of one's occupation. A comparison with the BRFSS data from the previous year could also be intriguing. Furthermore, the creation of an application offering tailored predictions to users might be a promising avenue.

## License and Citation

The dataset, BRFSS 2020, originates from the American Center for Disease Control and Prevention.

## Contributions

This project was a collaborative effort, with invaluable contributions from Sarah and Julie.

## Contact

For inquiries or feedback regarding this project, please reach out to:

*abajolah@gmail.com*
