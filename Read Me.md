#### **Project Overview: COVID-19 Data Cleaning and Visualization Using Python**

In this project, we set out to explore the global impact of the COVID-19 pandemic through data. The dataset, obtained from Our World in Data, contained extensive records on daily new cases, deaths, vaccinations, and population metrics across various countries. At first glance, the dataset was rich, but also raw—it included inconsistencies such as blank strings, improperly formatted dates, and scattered missing values. Thus, our first task was clear: the data had to be cleaned.

Using the pandas library in Python, we systematically performed each data cleaning step. We removed empty strings from textual columns, trimmed unnecessary whitespaces, and ensured that the date column was correctly converted into datetime objects. This allowed for time-based operations such as grouping by year or month. Additionally, irrelevant or missing values were handled with care to preserve the integrity of the analysis.

Once the data was cleaned, we exported the final dataset to a separate CSV file for safekeeping and future use. This step made the data ready for in-depth analysis and visualization, a critical part of understanding trends hidden in rows and columns.

The next phase of the project focused on data visualization. Using the matplotlib library, we created a series of seven distinct charts to analyse various aspects of the pandemic. These visualizations were designed to be beginner-friendly and insightful. For example, we created a line chart to track new daily COVID-19 cases in India, helping to visualize spikes and waves. A bar chart was used to compare total deaths across countries, highlighting those hit hardest.

Further, we created a horizontal bar chart to compare total vaccinations among nations. A scatter plot offered a perspective on the relationship between population size and total reported cases—revealing whether larger populations directly correlated with higher case numbers. Another powerful visualization was a filled area chart, comparing total COVID-19 cases over time for India, Brazil, and the United States. To enhance clarity, this chart was later modified to display total cases year-wise, simplifying the trend analysis and enabling country-to-country comparisons.

The insights derived were both fascinating and sobering. We observed India’s sharp waves of infection, the United States’ consistently high numbers, and Brazil’s vaccination and case patterns. Through visual storytelling, we made complex data more understandable and accessible.

In essence, this project exemplified the full cycle of data analytics: starting from raw data cleaning to building meaningful charts that tell a story. Using only pandas and matplotlib, we showcased the power of Python for real-world problem solving. For beginners stepping into data analysis, this project stands as a comprehensive example of how to transform messy data into clear visual insights—turning numbers into knowledge.





