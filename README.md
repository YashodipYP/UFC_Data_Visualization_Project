# UFC_Data_Visualization_Project
This is my third EDA project , been learning about data and how to work on it and what to extract out of Data and what to look out for.

#UFC Fight Prediction: Exploratory Data Analysis🥊

This project explores a dataset of over 6,000 UFC fights to identify which statistics (features) actually correlate with winning.

## 🔍 Key Insights
* **The "Age Trap":** Betting favorites who are 5+ years older than their opponents see their win rate drop from **84%** to **74%**.
* **Physicality vs. Skill:** Contrary to popular belief, Reach and Height advantages only provide a ~5% boost in win probability.
* **Market Efficiency:** The betting odds remain the strongest predictor of fight outcomes, significantly outperforming individual physical stats.

## 🛠️ Technologies Used
* **Python** (Pandas, NumPy)
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab

## 📊 Visualizations
### The Feature Heatmap
The correlation heatmap reveals that while physical traits are linked to each other, they have a weak direct correlation with the final 'Target' (winning).

## 📊 Data Source
The data used in this project was sourced from the [Ultimate UFC Dataset](https://www.kaggle.com/datasets/mdabbert/ultimate-ufc-dataset) on Kaggle. 
This dataset is a comprehensive collection of UFC fights, combining multiple sources including:
* **ufcstats.com** (Bout and fighter statistics)
* **bestfightodds.com** (Betting odds)
