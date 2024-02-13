#!/usr/bin/env python
# coding: utf-8

# # Wee 3: Obtaining Data for Visualization

# 
# In this notebook, we will explore three methods of obtaining data in Python, which you can later use for data visualization purposes:
# 1. Typing Data Directly
# 2. Using NumPy
# 3. Reading from an External File with Pandas
# 4. Fetching Data from an API
#     

# ## 1. Typing Data Directly

# In[ ]:


# Example of typing data directly
x = [1, 2, 3, 4, 5]
y = [10, 20, 30, 40, 50]


    


# ## 2. Using NumPy

# In[ ]:


import numpy as np
import matplotlib.pyplot as plt

# Creating a simple array
array = np.array([1, 2, 3, 4, 5])

# Generating a range of numbers
range_array = np.arange(0, 10, 2) # Start, Stop, Step

# Generating random data
random_array = np.random.rand(5) # 5 random numbers between 0 and 1

# Generating random integers
random_integers = np.random.randint(0, 100, 5) # Start, Stop, Number of values

# Generating numbers from a normal distribution
normal_distribution = np.random.normal(0, 1, 1000) # Mean, Standard deviation, Number of values

# Generating numbers from a uniform distribution
uniform_distribution = np.random.uniform(0, 10, 1000) # Lower bound, Upper bound, Number of values

# Generate a sequence of 1000 evenly spaced numbers from 0 to 2π
#linespace is very useful, since 
x = np.linspace(0, 2 * np.pi, 1000)

# Calculate the sine of these numbers
y1 = np.sin(x)
# Plot the sine and cosine waves
plt.plot(x, y1, label='sin(x)')
plt.title('Sine  Waves')
plt.xlabel('x')
plt.ylabel('y')
plt.legend()
plt.grid(True)
plt.show()


# ## Task 1: Plotting Sine and Cosine Curves
# 
# In the following exercise, you are tasked with generating a graph that simultaneously displays both the `sin(x)` and `cos(x)` functions. Please adhere to the guidelines below to ensure your graph meets the specified requirements:
# 
# ### Requirements:
# - **Function Domain:** The graph should cover the domain from `-2π` to `2π`. This range ensures that the periodic nature of both functions is adequately represented.
# - **Labels and Title:** Each axis should be clearly labeled to indicate what it represents. Specifically, label the horizontal axis as 'x' and the vertical axis as 'y'. Additionally, the graph must include a title that succinctly describes its contents.
# - **Styling:** Avoid using the default styles provided by the plotting library. Instead, choose distinct colors and line styles for the `sin(x)` and `cos(x)` plots to enhance visual differentiation.
# - **Legend:** Incorporate a legend into the graph to identify which curve represents `sin(x)` and which represents `cos(x)`. Ensure the legend is placed in a position that does not obstruct any part of the curves.
# 
# 
# 

# In[ ]:


## your code for task 1 should be here. 


# In[ ]:


import numpy as np

# Generate random numbers from a normal distribution
data = np.random.normal(0, 1, 1000)

# Plot histogram
plt.hist(data,bins=30)
plt.show()
        


# ## Task 2: Enhancing a Histogram of Normal Distribution Data
# 
# Given the initial Python code that generates random numbers from a normal distribution and plots a histogram, your task is to enhance and analyze this histogram. Follow the instructions below to modify the existing code and explore the characteristics of the normal distribution.
# 
# ### Instructions:
# 
# 1. **Modify Bin Count:** Experiment with the `bins` parameter by choosing at least two different values other than 30. Observe how the histogram's appearance changes with more or fewer bins. 
# 
# 2. **Add Titles and Labels:** Improve the readability of the plot by adding an appropriate title to the histogram. Also, label the x-axis as 'Value' and the y-axis as 'Frequency'. 
# 
# 3. **Apply Different Color:** Change the color of the histogram bars to something other than the default. You may choose any color that you find visually appealing.
# 
# 4. **Include Mean Line:** Calculate the mean of the `data` array and draw a vertical line on the histogram at the mean value. Use a contrasting color for the line and include a legend to indicate that this line represents the mean.
# 
# 5. **Answer Reflection Questions:**
#    - How does changing the number of bins affect the histogram's appearance and interpretation?
#    - What can you infer about the distribution of data from the histogram and the mean line?
# 
# 

# In[ ]:


# Your code for Task 2 should be here


# ## 3. Reading from an External File with Pandas

# In[ ]:


import pandas as pd

# File path
file_path = 'data.csv'

# Reading the CSV file
data = pd.read_csv(file_path)

# Displaying the first few rows of the dataframe
print(data.head())
    


# ## Task 3: Data Analysis with Pandas from Multiple Sources
# 
# In this task, you are required to perform data manipulation and analysis using the pandas library on datasets from two sources: a local file and a remote file hosted online. This will introduce you to handling data in different formats and from various sources.
# 
# ### Instructions:
# 
# 1. **Local Data Exploration:**
#    - Use the provided code snippet to read a local CSV file into a DataFrame. Display the first 10 rows and use the `.info()` method to summarize the DataFrame.
#    - File path for local data: `'data.csv'` (This file should be in your dataset repository).
# 
# 2. **Remote Data Handling:**
#    - Read a CSV file into a DataFrame directly from a URL. You can use the following example URL for a dataset: `https://example.com/data.csv` (Replace this URL with the actual URL of the dataset you wish to use).
#    - Display the summary information and the first few rows of this remote DataFrame as well.
# 
# 3. **Combined Data Analysis:**
#    - Choose one numerical column from each DataFrame and calculate its mean, median, and standard deviation.
#    - For a categorical column in each DataFrame, count the frequency of each category.
# 
# 4. **Visualization (Optional):**
#     - For each dataset choose a reasonalbe plot ( bar, plot or histogram).  
# 
# 

# In[1]:


## Your code for Task 3 should be here


# ## 4. Fetching Data from an API

# 
# This is more advance, we will do it in future!    

# 
# ### Task 3: Visualization with Data from a CSV File (Using Pandas)
# 1. **Line Plot from CSV Data**: Create a line plot using two selected columns from your CSV data. Add a title, axis labels, and grid.
# 2. **Bar Graph from CSV Data**: Create a bar graph to compare values in two selected columns from your CSV data. Add a title, axis labels.
#     

# ## Resources
# 
# For further exploration and to deepen your understanding of the capabilities offered by NumPy, please consult the following official documentation resources:
# 
# - [NumPy Random Generator Documentation](https://numpy.org/doc/stable/reference/random/generator.html) - A comprehensive guide to generating random data with NumPy, covering various functionalities of the random number generator.
# 
# - [NumPy Mathematical Functions](https://numpy.org/doc/stable/reference/routines.math.html) - Detailed documentation on the mathematical functions available in NumPy. This resource is invaluable for understanding the wide range of mathematical operations you can perform with NumPy.
# 
# 
# 
