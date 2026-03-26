# DV---Optimizing-IT-Support-Team-Performance-Using-Analytics-Supportlytics-

---

#  Supportlytics: IT Support Performance Analytics

##  Overview

Supportlytics is a data analytics project designed to improve IT support team efficiency by analyzing ticket data. It combines **Python (EDA + clustering)** with a **Power BI dashboard** to identify bottlenecks, optimize workload, and enhance resolution performance.

---

##  Objectives

* Analyze ticket trends across priority, category, and region
* Measure and improve resolution time
* Identify inefficiencies and bottlenecks
* Group similar tickets using clustering
* Enable data-driven decision-making

---

##  Tech Stack

* **Python**: Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning**: Scikit-learn (KMeans)
* **Visualization**: Power BI
* **Tools**: Jupyter Notebook

---

## 📂 Project Structure

```
Supportlytics/
 ┣ data/
 ┣ notebooks/
 ┣ ITSM_DASHBOARD.pbix
 ┗ README.md
```

---

## ⚙️ Setup & Usage

### 1. Clone Repository

```bash
git clone https://github.com/your-username/supportlytics.git
cd supportlytics
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Run Analysis

```bash
jupyter notebook
```

Execute notebooks in order:

* Data Cleaning
* EDA
* Clustering

### 4. Open Dashboard

* Open `ITSM_DASHBOARD.pbix` in Power BI
* Update dataset path if required
* Refresh data

---

##  Using with Your Own Data

1. Export ticket data from tools (ServiceNow, Jira, Zendesk)
2. Replace dataset in `/data` folder
3. Ensure required fields (ticket ID, timestamps, priority, category)
4. Run notebooks and refresh Power BI dashboard

---

##  Key Insights

* High-priority tickets drive workload
* Resolution time varies across categories and regions
* Certain clusters indicate performance bottlenecks
* Repetitive issues can be automated

---

##  Impact

* Improved SLA compliance
* Faster resolution time
* Better resource allocation
* Continuous performance monitoring

---

##  Conclusion

Supportlytics converts IT support data into actionable insights, helping teams improve efficiency through analytics and visualization.


* ⭐ GitHub with badges + visuals
* 🎯 Recruiter-focused version (very high impact)
