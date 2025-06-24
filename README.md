# cf-Instacart

Instacart is an online grocery store that operates through an app. The goal is to uncover information about their sales patterns.

## Objectives

The objective is to perform an exploratory analysis of the Instacart data to derive insights and suggest strategies for better segmentation. We want to better understand the variety of customers in the database along with their purchasing behaviors. Assuming everyone can't be targetted using the same methods, we need insights to support a targeted marketing strategy. This analysis is to inform what this strategy might look like to ensure Instacart targets the right customer profiles with the appropriate products.

## Key Questions

- What are the busiest days of the week and hours of the day, to know when to schedule ads at times when there are fewer orders.
- Whether there are particular times of the day when people spend the most money, as this might inform the type of products to advertise at these times.
- Instacart has a lot of products with different price tags. Can we develop a simple price range grouping to help direct sales and marketing efforts.
- Are there certain types of products that are more popular than others? 

Customer Segmentation:
- What’s the distribution among users in regards to their brand loyalty?
- Are there differences in ordering habits based on a customer’s loyalty status?
- Are there differences in ordering habits based on a customer’s region?
- Is there a connection between age and family status in terms of ordering habits?
- What different classifications does the demographic information suggest? 
- What differences are there in ordering habits of different customer profiles?

## Data

- orders

- orders_products_prior

- products

- customers

- departments

Citation: “The Instacart Online Grocery Shopping Dataset 2017”, Accessed from www.instacart.com/datasets/grocery-shopping-2017 via Kaggle on 07.04.2025.
The customer dataset as well as the 'prices' column have been synthesised and added to the dataset to allow more in-depth analyses.

## Tools

The data was analysed using Python and the following libraries:

- Pandas : for data analysis

- Numpy: for mathematical equations

- Seaborn: for data visulizations

- Matplotlib: for data visulizations

- Scipy: for data equations

## Folder Guide


The project files are divided between 5 folders:

    01_Project_Management: Project Brief.

    02_Data: Data was stored here and separated into two subfolders Original_Data and Prepared_Data. They contained the original data and the data after they have been cleaned and wrangled for analysis respectively. The files were not uploaded to GitHub due to size

    03_Scripts: The Jupyter notebooks containing the coding for the analysis, numbered in order of execution.

    04_Analysis: Contains the Visualizations folder with the visualizations generated in the analysis used to developing insights.

    05_Sent_to_Client: The final report in an Excel workbook.

