# cf-Instacart

Instacart is an online grocery store that operates through an app. They want to uncover more information about their sales patterns.

## Objectives

The objective is to perform an initial data and exploratory analysis of some of the Instacart data in order to derive insights and suggest strategies for better segmentation based on the provided criteria and information. The Instacart stakeholders are most interested in the variety of customers in their database along with their purchasing behaviors. They assume they can't target everyone using the same methods, and they’re considering a targeted marketing strategy. They want to target different customers with applicable marketing campaigns to see whether they have an effect on the sale of their products. This analysis is to inform what this strategy might look like to ensure Instacart targets the right customer profiles with the appropriate products.

## Key Questions

- The sales team needs to know what the busiest days of the week and hours of the day are in order to schedule ads at times when there are fewer orders.
- They also want to know whether there are particular times of the day when people spend the most money, as this might inform the type of products they advertise at these times.
- Instacart has a lot of products with different price tags. Marketing and sales want to use simpler price range groupings to help direct their efforts.
- Are there certain types of products that are more popular than others? The marketing and sales teams want to know which departments have the highest frequency of product orders.
- The marketing and sales teams are particularly interested in the different types of customers in their system and how their ordering behaviors differ. For example:
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
The customer dataset as well as the 'prices' column have been synthesised and added to the dataset by Career Foundry for learning purposes

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

Note: Instacart is a real company that’s made their data available online. However, the contents of the project brief have been fabricated for the purpose of this Achievement.
