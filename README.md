# Book Sales Data Analysis

## 📋 Project Overview  
This project analyzes a dataset of book sales in order to uncover insights related to genre popularity, author performance, sales trends over time, and the relationship between book attributes (ratings, price, etc.) and units sold.  
It leverages Python libraries including **NumPy**, **Pandas**, and **SciPy**, and uses data visualization to present the findings.

## 🧰 Tools & Technologies  
- Python  
- NumPy  
- Pandas  
- SciPy  
- Matplotlib / Seaborn (for visualization)  
- Jupyter Notebook (`notebook.ipynb`)  

## 🔍 Exploratory Data Analysis (EDA) & Key Questions  
- How many units were sold / what was the gross sales over time?  
- Which genres are most popular by units sold and revenue?  
- Which authors sold the most units?  
- What is the relationship between a book’s average rating, number of ratings, sale price, and units sold?  
- Are there trends in publishing year vs sales performance?  
- Data cleaning included handling missing values, fixing incorrect types, filtering invalid entries.

## 📊 Insights Summary  
- Strong positive correlation observed between **units sold** and **gross sales** — more units sold → higher revenue.  
- Genre **Fiction** dominated both in number of titles published and units sold.  
- Books with very high or very low average ratings did *not* always correspond to highest units sold; mid‐rated authors often performed best.  
- The most prolific years of publication and sales do *not* always align.  
- Price, number of ratings, and average rating showed *limited* correlation with units sold (indicating other factors at play).

## 📌 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Nitin7827/Book-Sales-Data-Analysis.git
2. Install dependencies (if requirements.txt is provided):
    pip install -r requirements.txt
3. Launch and open notebook.ipynb in Jupyter Notebook, Google Colab or VS Code:
     jupyter notebook notebook.ipynb
4. Follow the notebook to execute cells sequentially and review analysis & visualizations.

🚀 Project Highlights & Potential Extensions

Interactive dashboard using Streamlit or Dash that allows filtering by genre, author, year.

Build a predictive model (e.g., linear regression, decision tree) to forecast units sold based on book attributes.

Add more external datasets (e.g., marketing spend, social media metrics) for richer insights.

Deploy the application online for live interaction.

🙏 Acknowledgements

Thank you to the dataset contributors and open‐source libraries used (NumPy, Pandas, SciPy, Matplotlib, Seaborn).

