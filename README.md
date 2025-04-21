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

---

## 🎯 Key Questions Explored

1. Is there more left-leaning or right-leaning media bias overall?
2. Amongst well-known MSM outlets, is there a left or right bias?
3. Are some outlets more credible, even if biased?
4. Which outlets should I follow if I want left, center, or right perspectives?

--- 

📊 Excel PivotTable Analysis
General Overview

Media representation leans left overall. 
![AgHyTlH](https://github.com/user-attachments/assets/316a0370-8367-45bd-b32d-1705446476da)

By Credibility

    High and low credibility outlets tend to be left-biased.

    Medium credibility sources skew right. 
![vSwgsuV](https://github.com/user-attachments/assets/2c206283-030a-4783-849e-580c97808843)


Popular Outlets Only

Across all credibility levels, left-leaning outlets dominate.
No clear link was found between bias and credibility. 
![EWFICPn](https://github.com/user-attachments/assets/87bf90f9-bdda-455d-8f22-4828cfb0e5f7)

📈 Power BI Dashboard

The Power BI visualization confirms that left-leaning outlets dominate the media landscape. Interestingly, some far-right sources show high credibility, while right-center outlets often rank lower.

A suggestion table is included in the dashboard, recommending popular, high-credibility outlets across the bias spectrum, helping you curate a balanced media diet. 
![image](https://github.com/user-attachments/assets/1a802ac4-1358-491c-917b-8734416894f4)

