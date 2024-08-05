
![Dashboard](https://github.com/kscheran93/Video-Game-Sale-_-Tableau-Project/blob/main/Dashboard%201%20(1).png?raw=true)

[The full project Link ](https://public.tableau.com/views/VideoGamesales_17228957540670/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


![Kaggle dataset picture](https://github.com/kscheran93/Video-Game-Sale-_-Tableau-Project/blob/main/Screenshot%202024-08-05%20230417.png?raw=true)

[The kagggle Dataset Link](https://www.kaggle.com/datasets/gregorut/videogamesales)
# Video Games Sales 

### Problem Statement

The **Video Game Sales Dataset** aims to analyze sales data from over 16,500 video games, focusing on understanding sales trends, market dynamics, and the factors contributing to the success of games across different platforms, genres, and regions. This analysis seeks to answer several key questions:

1. **Which video games are the top sellers globally, and what are their sales figures?**
2. **How do sales vary across different platforms and genres?**
3. **What are the sales trends over time, and how do they differ by genre and region?**
4. **Who are the leading publishers in the industry based on sales, and which platforms are most successful?**

By addressing these questions, the project provides valuable insights for stakeholders, including game developers, publishers, marketers, and researchers, helping them make informed decisions and strategies based on historical sales data. The ultimate goal is to leverage data-driven insights to understand market behavior and identify opportunities for growth and innovation in the video game industry.

### README for GitHub: Video Games Sales Dataset

#### **KPIs**

1. **Total Names in Dataset**:
   - **Description**: Represents the total number of unique video games included in the dataset.
   - **Measurement**: Count distinct values in the `Name` column.

2. **Total Platforms in Dataset**:
   - **Description**: Indicates the total number of unique platforms (e.g., PC, PS4) featured in the dataset.
   - **Measurement**: Count distinct values in the `Platform` column.

3. **Total Publishers in Dataset**:
   - **Description**: The total number of unique game publishers present in the dataset.
   - **Measurement**: Count distinct values in the `Publisher` column.

4. **Total Genres in Dataset**:
   - **Description**: The total number of unique genres of games recorded in the dataset.
   - **Measurement**: Count distinct values in the `Genre` column.

#### **Chart Requirements**

1. **Sales by Year and Genre (Area Chart)**:
   - **Description**: An area chart that illustrates the distribution of global sales across different years, segmented by genre. This helps in visualizing trends and the popularity of various genres over time.
   - **Data Fields**: `Year` (x-axis), `Global_Sales` (y-axis), `Genre` (area segments).

2. **Top 10 Names by Sales (Horizontal Bar Chart)**:
   - **Description**: A horizontal bar chart showcasing the top 10 games by global sales, providing insight into the most popular games in the dataset.
   - **Data Fields**: `Name` (y-axis), `Global_Sales` (x-axis), sorted in descending order of sales.

3. **Top 10 Platforms by Sales (Horizontal Bar Chart)**:
   - **Description**: This chart displays the top 10 platforms ranked by total sales, highlighting the most successful platforms in terms of game sales.
   - **Data Fields**: `Platform` (y-axis), `Global_Sales` (x-axis), sorted in descending order of sales.

4. **Top 10 Publishers by Sales (Horizontal Bar Chart)**:
   - **Description**: A horizontal bar chart that presents the top 10 publishers based on total game sales. It helps in identifying the leading publishers in the industry.
   - **Data Fields**: `Publisher` (y-axis), `Global_Sales` (x-axis), sorted in descending order of sales.

5. **Total Sales by Genre (Vertical Bar Chart)**:
   - **Description**: A vertical bar chart showing the total global sales for each genre, offering a clear view of which genres dominate the market.
   - **Data Fields**: `Genre` (x-axis), `Global_Sales` (y-axis), sorted by sales in descending order.

#### **Dataset Reference**
The dataset used for this analysis can be found on Kaggle: [Video Game Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales).

#### **Usage Instructions**
- The Tableau dashboard provides an interactive way to explore the data, with filters for year, genre, platform, and publisher.
- Use tooltips for additional details on specific data points, such as sales figures and game information.

#### **Contributions**
- Contributions are welcome. Please submit pull requests for any new features, visualizations, or improvements.
