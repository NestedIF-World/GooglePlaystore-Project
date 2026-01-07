# 🔍 Cracking the Code: An EDA Adventure 🚀

Welcome to my Exploratory Data Analysis (EDA) playground! If you've ever looked at a messy CSV file and felt like you were staring at the Matrix, you're in the right place. 

I built this repository to document my journey of turning "dirty" data into clear, actionable insights. This project breaks down the EDA process into bite-sized, digestible steps.

---

**Ready to explore the code? Check out the [Jupyter Notebook](./googleplaystore.ipynb)!**


<table>
  <tr>
    <td width="55%" valign="top">

### 🌐 The Big Picture: CRISP-DM Framework

Before diving into the code, it's important to understand the process. I follow the **CRISP-DM** (Cross-Industry Standard Process for Data Mining) methodology to ensure the analysis is structured and goal-oriented.

1. **Business Understanding:** Identifying the goal (e.g., "What makes an app successful?").
2. **Data Understanding:** Gathering and exploring the raw data.
3. **Data Preparation:** Cleaning and transforming data (The EDA heart).
4. **Modeling:** Applying algorithms (Future step).
5. **Evaluation:** Checking if results meet business goals.
6. **Deployment:** Sharing insights via this repository.

   </td>
   <td width="45%" align="left">

<img src="CRISP-DM Framework.png" alt="CRISP-DM Framework" width="350"/>

   </td>
  </tr>
</table>


> 🔗 For a deep dive into this standard, check out the [CRISP-DM Framework](./CRISP-DM.docx)!

---

## 🛠️ The EDA Roadmap

### 1. Data Ingestion 📥
The "treasure hunt" phase. Gathering raw data from Excel, CSVs, SQL databases, or APIs.

### 2. Data Cleaning & Preprocessing 🧼
Raw data is messy. I spend time:
* **Fixing Missing Values:** Imputing or deleting the "empty" spots.
* **De-duplication:** Making sure no data point is double-counting its importance.
* **Standardization:** Converting units (like feet to meters) so everything speaks the same language.

### 3. Descriptive Statistics 🔢
Getting the "vibe" of the data using math:
* **Central Tendency:** Mean, Median, Mode.
* **Dispersion:** Standard Deviation and Variance (how wild is the data?).

### 4. Univariate Analysis 👤
Looking at one variable at a time to find outliers and distributions.
* *Tools:* Histograms, Box Plots.


### 5. Bivariate Analysis 🤝
Do two variables have a "connection"? (e.g., Does more ad spend actually lead to more sales?)
* *Tools:* Scatter Plots, Bar Charts.

### 6. Multivariate Analysis 🕸️
When things get complicated. Examining 3+ variables to see how they interact.
* *Tools:* Heatmaps, Pair Plots.


### 7. Feature Engineering 🏗️
The "art" of data science. Creating new columns (like "Day of Week" from a date) to help models learn better.

### 8. Visualization 🎨
The storytelling phase. Turning numbers into beautiful, easy-to-read charts for stakeholders.

---

## 🏗️ Deep Dive: The Google Play Store Project

In this repo, I applied the roadmap above to a dataset of mobile apps. Here’s a peek into the engine room:

* **Datatype Magic:** Converted `Reviews`, `Size`, and `Price` from objects to `int`/`float`.
* **Time Travel:** Split the `Last Updated` column into `Day`, `Month`, and `Year`.
* **Unit Control:** Normalized the `Size` column to a single unit.
* **Quality Control:** Hunted down and removed duplicate apps.

---

## 💡 Key Insights (The "Aha!" Moments)

* **Free is King:** 92% of apps are free! 💸
* **Family First:** The most popular category is **Family** (19% share).
* **The Sweet Spot:** Most installs happen for apps with a rating between **4.0 - 4.5**.
* **Engagement:** **Games** are the most reviewed and installed category.
* **The Tail End:** "Adults only 18+" and "Unrated" content receive the fewest ratings.

---

## 🧰 Tech Stack

* **Language:** 🐍 Python
* **Data Wrangling:** 📦 Pandas & NumPy
* **Visuals:** 📊 Matplotlib & Seaborn
* **Environment:** 📓 Jupyter Notebook

---

## 🎓 Acknowledgments
A huge thank you to **Ajay Kumar Gupta**, Staff Data Scientist at **Synopsys**, for the mentorship and guidance throughout this deep dive!


