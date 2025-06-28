# Airbnb Data Analysis

An Airbnb data analysis project using only core Python and NumPy. Includes data cleaning, transformation, outlier handling, and insights — all built from scratch without using Pandas.

---

## 📌 Overview

This project explores a real-world Airbnb listings dataset using only core Python libraries and NumPy — without using Pandas or visualization tools like Matplotlib.  
The goal was to challenge conventional workflows and show that meaningful insights can still be extracted using just fundamental tools.

---

## 🧠 Motivation

I wanted to challenge myself by doing this project without using Pandas or Matplotlib — just plain Python and NumPy.  
It helped me really understand how data works behind the scenes — from raw CSVs to cleaning, grouping, and analyzing.

I didn’t want to just follow tutorials; I wanted to build something from scratch that felt like my own effort.  
This also gave me something unique and honest to add to my portfolio as I prepare for university admissions.

I did everything manually — from loading the CSV file to cleaning and analyzing the data — without relying on high-level tools. It was tough at times, but worth it.

---

## 📂 Dataset

- *Source*: [Inside Airbnb](http://insideairbnb.com/get-the-data.html)  
- *Format*: CSV  
- *Location*: London  
- *Features Used*:
  - price
  - neighbourhood
  - minimum_nights
  - reviews_per_month
  - last_review
  - number_of_reviews

---

## ⚙ Project Workflow

1. *CSV Loading* – Done using csv.reader (not Pandas).  
2. *Basic Exploration* – Row count, header analysis, sample prints.  
3. *Data Cleaning* – Handled missing values in price, reviews_per_month, and last_review. Converted strings to float.  
4. *Outlier Detection and Removal* – Removed unrealistic values in price and minimum_nights.  
5. *Descriptive Statistics* – Used NumPy to calculate mean, median, and percentiles.  
6. *Neighbourhood-Level Analysis* – Found top 10 cheapest neighbourhoods by average price.

---

## 🧩 Key Challenges

- Handling missing data without Pandas  
- Performing operations like group-by manually  
- Working with date columns without the datetime library  
- Skipping visual validation — all verification was done numerically

---

## 💡 Key Insights

- The majority of listings are reasonably priced, but some outliers exist.  
- A few listings had extreme outliers that could distort trends if not removed.  
- The final list of cheapest neighbourhoods could help low-budget travelers.

---

## 🗃 Project Structure

airbnb_numpy_project/
├── data/
│   └── london_airbnb.csv
├── main.py
├── README.md
├── LICENSE
└── output/
    └── top10_cheapest_neighbourhoods.txt

---

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 💬 Final Thoughts

This project taught me how much we usually rely on libraries.  
There were moments I felt stuck, but solving problems on my own was the best part.  
Now I feel more confident working with raw data and understanding what’s going on under the hood.

It also made me realize I enjoy figuring things out, even if it takes longer — and that’s probably the mindset I want to carry forward in the future.


