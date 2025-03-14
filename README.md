# 🏢 Naukri.com Job Scraper – Data Scientist Jobs  

This project automates job data scraping from **Naukri.com** using **Selenium**. It filters jobs based on **location (Delhi/NCR)** and **salary range (3-6 Lakhs)**, then extracts **job title, company name, experience required, salary, and location** for the **first 10 listings**.  

---

## 🚀 Features  

✅ Automatically navigates to **Naukri.com**  
✅ Searches for **Data Scientist** jobs  
✅ Applies **location (Delhi/NCR)** and **salary (3-6 Lakhs)** filters  
✅ Extracts **job title, company name, experience required, salary, and location**  
✅ Stores results in a **Pandas DataFrame** for analysis  

---

## 📂 Project Structure  

Naukri_Job_Scraper/  
│  
├── **src/**  
│   ├── `job_scraper.py`     # Main script for scraping job data  
│   ├── `utils.py`           # Helper functions  
│  
├── **data/**  
│   ├── `jobs.csv`           # Scraped job data  
│  
├── **notebooks/**  
│   ├── `analysis.ipynb`     # Jupyter notebook for analysis  
│  
├── `requirements.txt`       # Required dependencies  
├── `README.md`              # Project documentation  
└── `.gitignore`             # Ignore unnecessary files  


---

## 🔧 Technologies Used  

- 🐍 **Python**  
- 🌐 **Selenium** – For web automation  
- 📊 **Pandas** – For data handling  

---

## 🎯 How It Works  

1️⃣ Open **Naukri.com** and enter **"Data Scientist"** in the search field.  
2️⃣ Click the **Search** button.  
3️⃣ Apply **location (Delhi/NCR)** and **salary (3-6 Lakhs)** filters.  
4️⃣ Extract details from the first **10 job results**.  
5️⃣ Store the scraped data in a **Pandas DataFrame**.  

---

## 📊 Sample Output  

| Rank | Company Name | Job Title | Experience | Salary | Location |
|------|-------------|-----------|------------|--------|----------|
| 1 | Creative Hands HR Consultancy | Data Scientist/ ML Engineer | 0-0 Yrs | 3-4 LPA | Mohali, Hyderabad, Ahmedabad |
| 2 | GABA Consultancy Services | Fresher / Data Scientist / Analyst | 0-0 Yrs | 2.25-4.75 LPA | Noida, Greater Noida, Delhi/NCR |
| 3 | inVentiv International | Senior Data Scientist | 3-6 Yrs | Not Disclosed | Gurgaon, Hyderabad, Bangalore |
| 4 | iHackers Inc | Data Scientist Internship | 0-1 Yrs | Not Disclosed | New Delhi |
| 5 | Inference Labs | Data Scientists | 3-5 Yrs | Not Disclosed | Gurgaon |
| 6 | Newgen Software | Data Scientist | 2-5 Yrs | 5-12 LPA | Noida |
| 7 | R Systems | Data Scientist | 5-10 Yrs | Not Disclosed | Noida |
| 8 | Agreeya | Data Scientist | 3-6 Yrs | Not Disclosed | Noida, Gurgaon, Delhi/NCR |
| 9 | NIL-LABS Innovation | Data Scientist | 5-10 Yrs | 5-7.5 LPA | New Delhi, Gurgaon, Delhi/NCR |
| 10 | Experiture | Data Scientist | 5-7 Yrs | 5-8.5 LPA | Kolkata, Hyderabad, Ahmedabad, Bangalore |

---
