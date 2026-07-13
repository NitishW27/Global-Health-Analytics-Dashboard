# 🌍 Global Health Analytics Dashboard

An interactive **R Shiny dashboard** that explores global health trends using publicly available health datasets. The dashboard enables users to compare countries, analyse health indicators over time, and gain insights through interactive visualisations.

---

## 📖 Overview

Healthcare outcomes vary significantly across countries due to factors such as economic development, healthcare expenditure, demographics, and access to medical services.

This project was developed to provide an intuitive and interactive platform for exploring global health data. Users can investigate trends, compare countries, and visualise relationships between multiple health indicators to better understand global health patterns.

---

## 🎯 Objectives

- Explore global health indicators across countries
- Compare health outcomes between regions
- Analyse changes in health metrics over time
- Identify patterns and trends through interactive visualisations
- Present complex health data in an accessible dashboard

---

## 🚀 Features

- 🌍 Country and regional comparisons
- 📈 Interactive time-series visualisations
- 📊 Dynamic charts and graphs
- 🔍 Custom filtering and exploration
- 📉 Multiple health indicators
- ⚡ Responsive R Shiny dashboard

---

## 🛠️ Technologies Used

- **R**
- **Shiny**
- **ggplot2**
- **dplyr**
- **tidyr**
- **plotly**
- **DT**
- **tidyverse**

---

## 📂 Project Structure

```
Global-Health-Analytics-Dashboard/
│
├── app.R
├── data/
├── scripts/
├── www/
├── outputs/
├── images/
├── README.md
└── requirements.md
```

---

## 📊 Dashboard Preview

> Add screenshots of your dashboard here.
> <img width="958" height="502" alt="image" src="https://github.com/user-attachments/assets/ac45c5ee-4127-4cc9-98ec-332a6deb2cef" />
<img width="952" height="425" alt="image" src="https://github.com/user-attachments/assets/aad38eee-1009-4f2e-bbc0-5cf6c9ae38ec" />
<img width="959" height="404" alt="image" src="https://github.com/user-attachments/assets/4703bbdf-92a2-4a6a-9d9e-69f4eeb134ed" />




Example:

```
images/
    dashboard-home.png
    country-comparison.png
    trend-analysis.png
```

Then display them:

![Dashboard Home](images/dashboard-home.png)

![Country Comparison](images/country-comparison.png)

![Trend Analysis](images/trend-analysis.png)

---

## 📁 Dataset

The dashboard uses publicly available global health data containing multiple health indicators across countries and years.

Example information to include:

- Source: WHO
- Geographic coverage: Global
- Time period: (2000–2023)
- Indicators analysed:
  - Life expectancy
  - Mortality rates
  - Healthcare expenditure
  - Population statistics
  - Disease prevalence
 

---

## 📈 Key Insights

The dashboard enables users to:

- Compare healthcare outcomes between countries
- Identify long-term health trends
- Explore relationships between different health indicators
- Discover regional disparities in healthcare outcomes
- Generate interactive visualisations for decision-making

---

## ▶️ Running the Project

### Clone the repository

```bash
git clone https://github.com/NitishW27/Global-Health-Analytics-Dashboard.git
```

### Install required packages

```R
install.packages(c(
  "shiny",
  "ggplot2",
  "dplyr",
  "tidyr",
  "plotly",
  "DT",
  "tidyverse"
))
```

### Launch the application

```R
shiny::runApp()
```

---

## 💡 Future Improvements

- Deploy the dashboard online
- Add predictive analytics
- Integrate additional health datasets
- Improve mobile responsiveness
- Add downloadable reports
- Expand country-level comparisons

---

## 👨‍💻 Author

**Nitish Wadpally**

Master of Data Science & Decisions  
UNSW Sydney

- GitHub: https://github.com/NitishW27
- LinkedIn: https://www.linkedin.com/in/nitish-prasad-wadpally-08819a216/

---

## 📄 License

This project is licensed under the MIT License.
