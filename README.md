# 📊 NYC311 Service Request Analysis

## 📌 Project Overview
The **NYC311 Project** analyzes New York City’s 311 service request dataset to uncover patterns in citizen complaints, service efficiency, and urban resource allocation. Using Python and Jupyter Notebook, the project demonstrates skills in **data cleaning, exploratory data analysis (EDA), and visualization**.

---

## 📂 Data Description

The analysis is based on the **NYC 311 Service Requests dataset**, one of the largest open city datasets available through [NYC Open Data](https://opendata.cityofnewyork.us/). It contains millions of records of citizen complaints and service requests logged since 2010.

### Dataset Details
- **Source**: NYC Open Data – 311 Service Requests (2010–Present)  
- **Size**: Over 34 million rows and 40+ columns (updated daily)  
- **Coverage**: All five boroughs of New York City  
- **Frequency of Update**: Daily  

### Key Columns
- **Unique Key** → Identifier for each service request  
- **Created Date / Closed Date** → When the complaint was filed and resolved  
- **Complaint Type** → Broad category (Noise, Illegal Parking, Sanitation, Housing, etc.)  
- **Descriptor** → Specific detail about the complaint  
- **Location Type** → Street, residence, commercial building, etc.  
- **Incident Address / Borough / Zip Code** → Geographic details for mapping  
- **Agency / Agency Name** → Department responsible for handling the request  
- **Status** → Whether the complaint is open, closed, or pending  

### Why It’s Useful
- **Urban insights**: Identifies problem hotspots across boroughs  
- **Seasonal trends**: Shows when complaints peak (e.g., noise in summer)  
- **Agency performance**: Tracks resolution times and efficiency  
- **Policy planning**: Guides city officials in resource allocation  

---

## 🎯 Objectives
- Explore the most common complaint types (noise, sanitation, illegal parking, housing, etc.).
- Identify geographic distribution of complaints across boroughs.
- Analyze seasonal and time-based trends in complaint volumes.
- Evaluate service response times and resolution efficiency.
- Present findings through clear visualizations and narrative storytelling.

---

## 🛠 Tools & Technologies
- **Python**: Pandas, NumPy for data wrangling  
- **Visualization**: Matplotlib, Seaborn for charts and graphs  
- **Jupyter Notebook**: Interactive analysis and documentation  
- **Dataset**: NYC Open Data – 311 Service Requests  

---

## 📊 Key Insights
- **Noise complaints dominate** the dataset, especially in Manhattan and Brooklyn.  
- **Seasonal peaks** occur in summer months and holidays, reflecting outdoor activities and construction.  
- **Geographic hotspots** show higher complaint density in densely populated boroughs.  
- **Response times vary**: quick for issues like illegal parking, slower for housing and sanitation complaints.  
- **Policy implications**: Agencies can use these insights to allocate inspectors and resources more effectively.  

---

## ✅ Conclusion
This project highlights how open city data can be transformed into actionable insights. By analyzing complaint types, borough-level distribution, and response times, the study demonstrates the power of **data analytics in urban governance**. The findings suggest that targeted resource allocation and seasonal planning could improve citizen satisfaction and service efficiency.  

---

## 🚀 Getting Started

Follow these steps to run the project locally:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/NivedhaSiva/NYC311.git
   cd NYC311
2. **Install dependencies** 
Make sure you have Python 3.x installed, then run:
    ```bash
       pip install -r requirements.txt
(If no requirements file exists, install Pandas, NumPy, Matplotlib, Seaborn manually.)

3. **Open Jupyter Notebook**
   ```bash
      jupyter notebook
Then open NYC311.ipynb to explore the analysis step by step.

### 👩‍💻 Author  
Nivedha Sivakumar    

🌐 GitHub   : NivedhaSiva  
💼 LinkedIn : [Nivedha Sivakumar](www.linkedin.com/in/nivedhasivakumar)  
📧 Email    :  nivedha_sivalumar@outlook.com

If you found this project useful or have feedback, feel free to reach out!
