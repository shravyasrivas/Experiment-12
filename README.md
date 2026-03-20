

# Experiment 12: Categorical Data Analysis using Python

---

### Aim: Categorical Data Analysis using Python

---

### Theory

Categorical data represents variables that can be divided into distinct groups or categories, such as "Department," "Gender," or "Grade". Unlike numerical data, categorical data is analyzed through frequencies, proportions, and relationships between groups. 

In this experiment, Python's **Pandas** library is used to perform categorical analysis on two datasets: a student academic record and a retail order system. The focus is on summarizing data through frequency counts, cross-tabulations (contingency tables), and data grouping to uncover patterns between different categories.

---

### Command Descriptions

The following Pandas commands were used to manipulate and analyze the categorical datasets:

| Command | One-Line Description |
| :--- | :--- |
| `pd.read_csv()` | Loads data from an external CSV file into a DataFrame. |

| `df.head()` | Displays the first five rows of the dataset to provide a quick preview. |

| `df.info()` | Provides a summary of the dataset including column names, non-null counts, and data types. |

| `.value_counts()` | Calculates the frequency of occurrences for each unique category in a column. |

| `.value_counts(normalize=True)` | Returns the relative proportions (percentage distribution) of categories instead of raw counts. |

| `pd.crosstab()` | Computes a frequency table (contingency table) to show the relationship between two categorical variables. |

| `normalize='index'` | An argument in `crosstab` that calculates percentages across rows rather than total counts. |

| `df.groupby()` | Clusters the data into groups based on a specific column for aggregate analysis. |

| `pd.DataFrame()` | Manually creates a new DataFrame object from a Python dictionary. |

| `.unique()` | Lists all the distinct category names found within a specific column. |

| `.nunique()` | Counts the total number of unique categories present in a column. |

| `df[df['Col'] == 'Val']` | Filters the DataFrame to include only rows that match a specific category value. |

| `.sort_values()` | Rearranges the rows of the table alphabetically or numerically based on a selected column. |

---

### Functions and Logic Used

#### Analysis Logic
* **Frequency Analysis:** Determining how often specific attributes (like "Electronics" or "Grade A") appear in the dataset.
  
* **Percentage Distribution:** Normalizing data to understand the weight of each category relative to the whole.
  
* **Bi-Variate Analysis:** Using cross-tabulation to compare two categories (e.g., Department vs. Grade) to see if one influences the other.
  
* **Data Filtering:** Isolating specific segments of data for targeted inspection.

---

### Conclusion

Through this experiment, I successfully performed categorical data analysis using Python. I learned how to move beyond simple data loading to extracting meaningful insights through frequency distributions and cross-tabulations. This analysis is essential for identifying trends in non-numerical data, such as academic performance across departments or customer preferences in retail.

---

