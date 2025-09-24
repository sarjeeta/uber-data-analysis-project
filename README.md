
# Uber Ride Data Analysis

##  Project Overview

This project involves analyzing Uber ride data to uncover insights into customer behavior, booking patterns, pricing trends, and more. The analysis is conducted using Python and powerful libraries such as `pandas`, `matplotlib`, and `seaborn`.

##  Files
- `uber.ipynb`: The main Jupyter Notebook containing the full exploratory data analysis (EDA) on Uber ride data.

##  Features and Analysis Covered

- Data cleaning and preprocessing  
- Conversion of date columns into datetime format  
- Extraction of useful features like:
  - **Day of week**
  - **Month**
  - **Time of day**
  - **Days left to travel**
- Visualization of:
  - For Which Purpose Do People Book Uber the Most
  - Most Common Uber Booking Categories
  - At What Time do People Book Uber the Most
  - Which Month do People Book Uber Rides
  - Which Day of the Week do People book Uber rides the Most
  - Distribution of Miles People usually book for Uber rides

##  Technologies Used

- Python 
- Jupyter Notebook
- `pandas` for data manipulation
- `matplotlib` and `seaborn` for visualizations

##  How to Run

1. Clone the repository or download the `uber.ipynb` file.
2. Open the notebook in JupyterLab, Jupyter Notebook, or any compatible environment.
3. Run all cells sequentially to reproduce the analysis and visualizations.

```bash
pip install pandas matplotlib seaborn
```

##  Sample Visuals

- Line plots showing booking trends by month
- Bar plots 
- Histograms and scatter plots for price vs. other variables
- Box plots

##  Insights (Sample)

- Bookings peak during November month.
- Price increases as the travel date approaches.
- Business class significantly increases average fare.
