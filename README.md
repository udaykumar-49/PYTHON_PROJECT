
# 📊 Netflix Content Analysis 2023

This project performs an exploratory data analysis on Netflix content for the year 2023. Using Python and popular data science libraries, it provides visual insights into various aspects of Netflix's content catalog, such as most viewed titles, content types, language performance, and more.

## 📁 Dataset

The dataset used in this project is assumed to be named:
```
netflix_content_2023.csv
```
It should contain relevant columns like `Title`, `Hours Viewed`, `Content Type`, `Language Indicator`, `Release Date`, and `Available Globally?`.

> 📍 Update the file path in the script as needed:  
```python
df = pd.read_csv("path/to/netflix_content_2023.csv")
```

---

## 📦 Dependencies

Make sure to install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## 📌 Objectives Covered

1. **Top 10 Most Viewed Titles**  
   A bar chart showcasing the most watched Netflix titles in 2023.

2. **Movies vs Shows Distribution**  
   A count plot comparing the number of movies and shows.

3. **Top 10 Languages by Viewing Hours**  
   Horizontal bar chart showing languages with the highest viewership.

4. **Monthly Release Timeline**  
   Bar chart depicting the number of titles released each month.

5. **Global Availability**  
   Pie chart showing the percentage of content available globally.

6. **Title Length vs Hours Viewed**  
   Scatter plot analyzing if title length correlates with viewership.

7. **Distribution of Hours Viewed**  
   Histogram with KDE to explore how viewership is distributed.

---

## 🧼 Data Cleaning

- Removed commas and converted `Hours Viewed` to numeric.
- Converted `Release Date` to datetime and extracted the month.
- Dropped duplicate entries.
- Handled missing values gracefully.

---

## 📊 Visualizations

The script uses `matplotlib` and `seaborn` for all data visualizations, with customized themes and layout optimizations for clarity.

---

## 🚀 How to Run

1. Place your `netflix_content_2023.csv` in the appropriate path.
2. Run the Python script using any IDE or command line:
   ```bash
   python netflix_analysis.py
   ```
3. Visualizations will be displayed sequentially.

---

## 📃 License

Feel free to modify and use this analysis for educational or personal projects. Attribution is appreciated.
