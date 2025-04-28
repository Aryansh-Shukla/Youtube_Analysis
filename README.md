# YouTube Video & Comment Analysis 📊🎥

This project performs an exploratory data analysis and sentiment analysis on YouTube video metadata and user comments.  
It uses libraries like **Pandas**, **Seaborn**, **TextBlob**, **WordCloud**, **Plotly**, and **Emoji** to draw interesting insights from YouTube datasets.

---

## 📚 Project Description

- **Dataset**:  
  - `video_id_info.csv`: Metadata of YouTube videos.
  - Additional CSV files: Video-related data for various regions.
  - `US_category_id.json`: Mapping YouTube category IDs to human-readable names.

- **Analysis Performed**:
  - Checking for missing data and duplicates.
  - Sentiment analysis of comments using `TextBlob`.
  - WordCloud generation for positive and negative comments.
  - Extraction and frequency analysis of emojis used in comments.
  - Category-wise analysis of likes and views.
  - Correlation heatmaps between views, likes, and dislikes.
  - Identification of top YouTube channels based on total videos.

- **Visualizations**:
  - WordCloud for positive/negative comments.
  - Bar plots for most frequent emojis.
  - Box plots for like rates across different video categories.
  - Regression plots for views vs. likes.
  - Heatmaps showing correlations.

---

## 🛠️ Tech Stack

- **Languages**: Python 3
- **Libraries**:
  - `pandas`
  - `numpy`
  - `seaborn`
  - `matplotlib`
  - `textblob`
  - `wordcloud`
  - `emoji`
  - `plotly`

---

## 🚀 How to Run

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/Youtube_Analysis.git
    cd Youtube_Analysis
    ```

2. Install the required libraries:

    ```bash
    pip install pandas numpy seaborn matplotlib textblob wordcloud emoji plotly
    ```

3. Open the Jupyter Notebook (`.ipynb`) file.

4. Run all the cells sequentially.

---

## 📊 Sample Visualizations

- **WordCloud of Positive Comments**  
- **Bar Chart of Top Emojis**  
- **Heatmap of Views, Likes, Dislikes Correlation**  
- **Boxplot of Like Rate by Video Category**  

---

## ✨ Improvements Possible

- Apply more advanced NLP for deeper sentiment analysis.
- Add time series analysis on video publish dates.
- Build an interactive dashboard using Plotly Dash or Streamlit.
- Train machine learning models for predicting video popularity.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to open a Pull Request.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---
