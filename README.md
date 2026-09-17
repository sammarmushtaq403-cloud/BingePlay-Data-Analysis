# 🎬 BingePlay — Data Analysis Project

> Turning streaming data into meaningful insights 📊

BingePlay is a Data Science project focused on analyzing streaming-platform data to understand user behavior, content performance, engagement patterns, subscriptions, and potential churn signals.

The project combines **SQL, Python, and Pandas** to transform raw database data into meaningful analytical insights.

---

## 🚀 Project Overview

The goal of this project is to explore a fictional streaming-platform database and answer practical business questions using data analysis.

The analysis covers:

- 👥 User activity
- 💰 Subscription revenue
- 📈 Signup trends
- 📱 Device usage
- ⭐ User ratings
- 🎬 Content performance
- 🔥 Binge-watching behavior
- 💳 Subscription plan behavior
- ⬆️ Upgrade patterns
- 🔄 Viewer comeback behavior
- 📅 Long-term engagement
- ⚠️ Churn signals

---

## 🛠️ Technologies Used

- 🐍 Python
- 🗄️ MySQL
- 🔍 SQL
- 🐼 Pandas
- 🔗 PyMySQL
- 🧮 Data Analysis
- 📊 Data Visualization
- 📓 Jupyter Notebook

---

## 🗂️ Database Tables

The project works with data from tables such as:

- `users`
- `subscriptions`
- `watch_sessions`
- `ratings`
- `shows`

---

## 📊 Key Results

### 💰 Active Revenue
- Active subscriptions: **2,340**
- Monthly recurring revenue: **₹784,260**

### 📈 Signup Momentum
Monthly signups:

| Month | Signups |
|------|--------:|
| January | 350 |
| February | 400 |
| March | 500 |
| April | 550 |
| May | 600 |
| June | 600 |

May and June recorded the highest signup count with **600 signups each**.

### 📱 Device Analytics

| Device | Sessions | Watch Minutes | Avg. Watch Time | Completion |
|---|---:|---:|---:|---:|
| Laptop | 15,105 | 453,434 | 30.02 min | 60.51% |
| Mobile | 50,172 | 1,504,355 | 29.98 min | 60.24% |
| Tablet | 7,091 | 210,733 | 29.72 min | 59.79% |
| TV | 27,981 | 840,595 | 30.04 min | 59.98% |

### ⭐ Rating Distribution

- 1 Star: 234
- 2 Stars: 352
- 3 Stars: 847
- 4 Stars: 1,781
- 5 Stars: 1,786

Overall, **71.34%** of ratings were 4 or 5 stars.

### 🎬 Originals vs Acquired

| Content Type | Shows | Avg. IMDb |
|---|---:|---:|
| Original | 30 | 7.92 |
| Acquired | 70 | 6.63 |

### 🔥 Binge Day

- Total binge days: **414**
- Highest binge days by one user: **8**

A binge day was defined as a user watching the same show at least five times on the same date.

### 👤 Q1 Signups Who Never Watched

- Q1 signups: **1,250**
- Never watched: **226**

### 💳 Over-Paying Users

- Identified users: **212**

These users were identified based on their active subscription plan and the premium/family content they had watched.

### ⬆️ Upgrade Success Cohort

- Users: **55**
- Average time to first upgrade: **64.96 days**

### 🔄 Cliffhanger Comebacks

- Comeback events: **4,345**

These represent cases where a viewer had an incomplete viewing session and returned to the same show within the following 1–7 days.

### 📅 Consecutive-Week Engagement

- Users with 4+ consecutive weeks: **1,675**
- Longest streak: **26 weeks**

### ⚠️ Churn Signal

- Users identified: **521**

The analysis identifies users whose viewing activity showed a significant decline between May and June.

---

## 🔍 What I Learned

Through this project, I practiced:

- Writing SQL queries
- Connecting Python with MySQL
- Extracting data from relational databases
- Cleaning and transforming data
- Using Pandas for analysis
- Grouping and aggregating data
- Calculating analytical metrics
- Understanding user behavior
- Creating meaningful visualizations
- Turning data into actionable insights

---

## 📁 Project Structure

```text
BingePlay-Data-Analysis/
│
├── BingePlay.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── poster/
    └── BingePlay-Poster.png
