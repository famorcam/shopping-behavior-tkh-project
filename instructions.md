# Instructions

You are a junior data analyst at a fast-growing online shopping company headquartered in Bengaluru, India, **FlashFash**. This company has recently gone public with a 90 Billion USD IPO evaluation which will allow it to establish operations in the global market.

To get an understanding of the American market, your team has been tasked with analyzing the shopping behavior of consumers. 

Your job will entail analyzing the sample dataset `data/raw/shopping.csv` for aggregate descriptive statistics and visualizations on American consumers. We are interested in discovering the "seasonality" of shoppers, which demographics buy the most, and which market outreach strategies we can apply to maximize purchases.

Primarily you are tasked with discovering:

* What are the most popular colors by season?
* What is the most popular clothing item by season?
* What is the effect of promo-codes on the dollar-amount of purchases?
* When do users leave a review?

By answering these questions, we hope to optimize inventory and also determine marketing campaigns. 

Instructions & screenshots for this project are listed underneath each respective section, as well as in each respective jupyter notebook. For example, instructions for `Part 1: Exploratory Data Analysis` will also be in `01explore.ipynb`. There is one difficulty level for this project.

Utilize documentation, your peers, readings, and classroom notes to complete this project. 

Fun fact: fashion is not immune to the promises of data science. Check out these links to find out more:
* [data, but make it fashion](https://databutmakeitfashion.com/)
* [SHEIN data practices](https://news.sophos.com/en-us/2023/03/10/shein-shopping-app-goes-rogue-grabs-price-and-url-data-from-your-clipboard/)

## Background

This dataset contains 3900 samples & 15 columns of simulated data. We recommend lightly exploring this dataset by opening it up in your favorite spreadsheet technology (Excel or Google Sheets) to get an introductory understanding of the format & structure of this dataset.

### Columns

The columns of this dataset are as follows:

**Customer ID**
A unique identifier is assigned to each customer, facilitating tracking and analysis of their shopping behavior over time.

**Age**
The age of the customer, providing demographic information for segmentation and targeted marketing strategies.

**Gender**
The gender identification of the customer.

**Item Purchased**
The specific product or item selected by the customer during the transaction.

**Purchase Amount (USD)**
The monetary value of the transaction, denoted in United States Dollars (USD), indicates the cost of the purchased item(s).

**Location**
The state from where the order was made, offers insights into regional preferences and market trends.

**Size**
The size specification (if applicable) of the purchased item, is relevant for apparel, footwear, and certain consumer goods.

**Color**
The color variant or choice associated with the purchased item influences customer preferences and product availability.

**Season**
The seasonal relevance of the purchased item (e.g., spring, summer, fall, winter), impacts inventory management and marketing strategies.

**Review Rating**
A numerical assessment is provided by the customer regarding their satisfaction with the purchased item.

**Shipping Type**
Specifies the method used to deliver the purchased item (e.g., standard shipping, express delivery), influencing delivery times and costs.

**Promo Code Used**
Notes whether a promotional code or coupon was utilized during the transaction, aiding in the evaluation of marketing campaign success.

**Previous Purchases**
Provides information on the number or frequency of prior purchases made by the customer, contributing to customer segmentation and retention strategies.

**Payment Method**
Specifies the mode of payment employed by the customer (e.g., credit card, cash), offering insights into preferred payment options.

**Frequency of Purchases**
Indicates how often the customer engages in purchasing activities, a critical metric for assessing customer loyalty and lifetime value.

## Part 1: Exploratory Data Analysis

Similar to the first project (Rental Pricing Explore), we will first begin data analysis by exploring our dataset. During exploratory data analysis, we will be generating visualizations to find patterns and outliers. To find out more about this process, read the following [article from IBM](https://www.ibm.com/topics/exploratory-data-analysis).

Follow along with the instructions and documentation provided within the `code/01explore.ipynb` file. You will be focusing on the `data/raw/shopping.csv` file. 

After completing your code in `Exploratory Data Analysis I`, be sure to answer the questions located in `Exploratory Data Analysis II`

After completing the data exploration process, validate your visualizations using the screenshots located in `docs/part1.md`. If your output looks different, look back to your code and ensure that your syntax is correct, and code does not fail with error, and that your semantics match the goal of each section.

## Part 2: Data Transformation

After confirming your data exploration steps are complete, move forward to `code/02transform.ipynb`. Within this step, we will be cleaning and transforming our dataset to help answer our primary questions. Follow along with the instructions and documentation provided to complete this part of the data analysis.

After completing the data cleaning process, validate your transformed dataset using the screenshots located in `docs/part2.md`. Similiar to the previous step, ensure that your output matches before moving forward.

## Part 3: Aggregate Stats

Now that we've completed our data transformation step and have created a new file called `data/processed/shopping_cleaned.csv`, let's begin our analysis in `code/03analysis.ipynb`. In this step, we will be primarily focused on answering the questions proposed in our introduction. 

Validate that your output matches with the screenshots located `docs/part3.md` before moving forward to the last step.

## Part 4: Post Write-Up

Lastly, include a short summary of your project in `README.md` as well as a write-up describing what you observed in your observations and analyses.

Within this write-up, be sure to describe:

* The workflow that this project took
* What observations you made on your visualization
* Conclusions regarding your analytical questions
* The challenges you faced
* Which next-actions you would like to take to figure out more about this dataset

Feel free to use [this example by Timothy Lu](https://github.com/lutimoth/SpringboardMay2022/blob/main/Data%20Science%20Pipeline/LondonBoroughs/Unit%204%20Challenge%20-%20Tier%203_TimothyLu.ipynb) to help frame this write-up.

## Submission

The due date for this project is `11/27`.

To submit this project, you will push a completed version of this repository to your GitHub and post a link to your repo in Canvas. Please ensure that **all 4 parts are complete**. This includes **Part 4: Post Write-Up**. Any project without a **Post Write-Up** will not be graded.

**Note**: You must upload this to GitHub and submit a GitHub link to receive a grade for this project.
