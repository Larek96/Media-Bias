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

## PivotTable Excel Analysis
Overall, Media is clearly biased to the left. 
![AgHyTlH](https://github.com/user-attachments/assets/316a0370-8367-45bd-b32d-1705446476da)

Of all outlets: high and low credibility sources are left biased, and medium credibility sources are very right-biased.
![vSwgsuV](https://github.com/user-attachments/assets/2c206283-030a-4783-849e-580c97808843)


Of popular outlets: whether it be high, medium, or low credibility, the left was more represented. No clear link between credibility and bias.
![EWFICPn](https://github.com/user-attachments/assets/87bf90f9-bdda-455d-8f22-4828cfb0e5f7)

## PowerBI Analysis

Left media is clearly more represented in the media landscape, with far-right wing sources having surprisingly levels of credibility, especially compared to how low credibility right-center biased outlets seem.

A table giving suggestions of who to follow based on this dataset are given, narrowed down to popular, high credibility outlets with their biases given in case you want a particular view point.
![image](https://github.com/user-attachments/assets/1a802ac4-1358-491c-917b-8734416894f4)

