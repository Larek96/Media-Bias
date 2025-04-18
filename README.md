# 📰 Media Bias Analysis Dashboard

## 📌 Overview

In an era of rising political division, I started questioning the reliability of the news I consume. This project explores **media bias across major news outlets**, aiming to create an **interactive dashboard** that visualizes bias in a clear, digestible format.

> 💡 The goal isn't to eliminate biased sources, but to **balance** media consumption by understanding which outlets lean **left**, **center**, or **right**.

---

## 📂 Dataset Selection

After comparing options, I focused on two potential datasets:

- 🧠 **MBIC (Media Bias Including Characteristics)**  
  Highly detailed with word- and sentence-level bias annotations and annotator profiles.

- 📊 **AllSides Media Bias Ratings**  
  A high-level classification of political bias (e.g., *Left*, *Center*, *Right*) for hundreds of news outlets.

➡️ I chose **AllSides** due to its clarity and accessibility, making it ideal for building a simple yet powerful dashboard.

---

## 🗂️ About the Data

- Originally created in **2019**.
- Ratings are **continuously updated** through community votes and editorial reviews.
- I **manually updated** some major outlet ratings (e.g., **Bloomberg**, **The Guardian**) based on changes up to **2024**.
- Added a new column called "relevant" that is filled with "yes" if I know of the outlet.

---

## 🔧 Data Cleaning

Only minimal cleanup was needed:

- 🗑️ Removed outlets with missing bias ratings.
- ✏️ Standardized bias labels for clarity  

Once the data was cleaned and outliers removed, I used PowerQuery to import the excel file to Power BI.
---

## 🎯 Key Questions Explored

1. Is there more left-leaning or right-leaning media bias overall?
2. Amongst well-known MSM outlets, is there a left or right bias?
3. Are some outlets more credible, even if biased?
4. Which outlets should I follow if I want left, center, or right perspectives?
