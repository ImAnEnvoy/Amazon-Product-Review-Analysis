# DSA Data Analysis (DSA Incubator Project) Documentation
This is where I started my portfolio building while taking my Data Analysis class with the Incubator Hub. As a result, I completed the final project (Fist case senario) of the Amazon e-commerse usin data set. This project was carried out to showcase my critical thinking, analytics, problem solving skills etc accumulated sofar during the DSA Incubator Data Analysis classes. This project done using microsoft excel, and as such, features such as power query, pivot, charts, functions/formulas.
While carrying out this project, I assumed the position of Junior Data Analyst at RetailTech Insights.

## Project topic: 
Amazon-Product-Review-Analysis

### Project overview
RetailTech Insights, a company that provides e-commerce analytics solutions to sellers on platforms like Amazon.  The task to  analyze products and customers review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.

For this analysis, a comprehensive Exploratory Data Analysis (EDA) was carried out using the MS excel and techniques relevant to the context of this dataset was employed. THis included: 
- Ingestion: this is connecting analytics system with the storage system.
- Transformation: Cleaning the data to remove unwanted (null, error values, blanks etc) data from the dataset
- Visualization: interpreting the data visuals e.g. graphs, chart, etc
- Analysis: performing calculations with the data
- Dashboard creation

## Discription of Data:
### Data Source
The data is an Amazon Product Review data. The dataset consists of 1,465 rows and 16 columns. The dataset contains information scraped from Amazon product pages, including: 
- Product details: name, category, price, discount, and ratings 
- Customer engagement: user reviews, titles, and content 
- Each row represents a unique product, with aggregated reviewer data stored as comma-separated values

### Tools Used
This project utilizes MS excel 2016:
- Power query:
    - for connection to the data
    - For data cleaning, creating measures etc
- Github repository (for project portfolio)

### Data Cleaning and Preparation
The following were done to clean and prepare the data for analysis and visiualization
- Assign a generic gender (e.g unknown) to status to these employees employees who refused to disclose their gender.
- Remove blanks (i.e. some employees are without a salary because they are no longer with the company).
- Remove departments that are indicated as “NULL”.
- Create measures ussing DAX expressions to determine total employee, percentages and number of male/female, average salary, etc

### Data Analysis Task
The task was to Use pivot tables and calculated columns where necessary to answer the following: 
1. What is the average discount percentage by product category? 
2. How many products are listed under each category? 
3. What is the total number of reviews per category?  
4. Which products have the highest average ratings? 
5. What is the average actual price vs the discounted price by category? 
6. Which products have the highest number of reviews? 
7. How many products have a discount of 50% or more? 
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)? 
9. What is the total potential revenue (actual_price × rating_count) by category? 
10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)? 
11. How does the rating relate to the level of discount? 
12. How many products have fewer than 1,000 reviews? 
13. Which categories have products with the highest discounts? 
14. Identify the top 5 products in terms of rating and number of reviews combined.

### Functions/formula used
- Logical function
- conditional function
- aggregation function

## Screen shots

### Dashboard
<img width="944" alt="screenpi" src="https://github.com/user-attachments/assets/baf1aad9-ef97-4f16-839d-c50f7ec342dc" />


### Cleaned table wiew
<img width="954" alt="3" src="https://github.com/user-attachments/assets/ee39eeed-9616-431d-a4fe-aae35e3d1db4" />


### Pivote tables
<img width="933" alt="2" src="https://github.com/user-attachments/assets/27382d03-0593-48e9-8e3f-02ce395e55d3" />

### Amazon Product Review raw data file
[DSA-FinalProject-Amazon.xlsx](https://github.com/user-attachments/files/21068400/DSA-FinalProject-Amazon.xlsx)

## About Me
###Ayoola Ezekiel O.
Higher National Diploma (HND) in Computer Science from the Federal Polytechnic Bauchi, Nigeria. I am passionate about learning, working and drawing actionable insights from data. My data analysis journey is also blended with graphics designs, which allows me to create dashboard visual for reporting and presentation.

## Contacts
Feel free to reach out to me on:
Email:       ezekieloluwafemiayoola@gmail.com
Phone:       +234 307 5187 993
WhatsApp:    +234 817 9264 472
Linkedin:    www.linkedin.com/in/ezekiel-ayoola-89a10983

## GitHub Support
If you find this work intersting and resourseful, kindly ⭐ this repository. Thank you.
