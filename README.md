# Youtube_Top1000_Dashboard

## **Project Overview**
This project analyzes the top 1000 Youtube channels using a SQLite database and Python. The goal is to explore channel performance, efficiency, and growth trends across categories using interactive visualizations.

The dashboard is built in **Google Colab** and allows users to explore the data dynamically with charts, tables, and KPI summaries.

---

## **Features**

- **KPI Summary:**
  Total channels, average subscribers, and average views

- **Top 10 Categories:**
  Bar chart showing categories with the highest average views per video

- **Top Efficiency Channels:**
  Interactive table of top-performing channels by average views per video and subscribers per video
  - Filter by category using a dropdown

- **Channel Age Analysis**
  Scatter plot showing the relationship between channel age and total subscribers

---

## **Skills Demonstrated**

- SQL: querying and creating analytical views  
- Python: pandas for data manipulation, matplotlib & plotly for visualization  
- Data visualization: interactive charts, tables, and KPI summaries  
- Portfolio-ready end-to-end data analysis and dashboard creation

---

## **Getting Started**

1. Open the notebook in (https://colab.research.google.com/drive/1vthe2LUMF9HQHQOVx7EK32c5-GePPox9?usp=sharing) 
2. Upload `youtube.db` when prompted  
3. Run all cells to explore the interactive dashboard  

---

## **Repository Contents**

| File | Description |
|------|-------------|
| `youtube_dashboard_colab.ipynb` | Interactive Colab notebook with dashboard |
| `youtube.db` | SQLite database containing the top 1000 YouTube channels data |
| `README.md` | Project overview and instructions |

---

## **Screenshots**
<img width="600" height="353" alt="image" src="https://github.com/user-attachments/assets/f87c897e-143e-44f1-a970-fad5aba98893" />
<img width="532" height="458" alt="image" src="https://github.com/user-attachments/assets/5e8ac479-578a-4b87-b93a-ceb69709ceb2" />
<img width="527" height="351" alt="image" src="https://github.com/user-attachments/assets/01d5948e-cc47-48b3-b6e6-510ed699bb9e" />

---

## **Future Improvements**

- Add subscriber growth trends over time  
- Include more advanced efficiency metrics (subs per million views, engagement ratio)  
- Implement a fully interactive web dashboard outside Colab (e.g., Streamlit or Dash)
