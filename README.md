# **Semmelweis and the Impact of Handwashing on Maternal Mortality**

## 📌 **Overview**
This project analyzes historical data from the Vienna General Hospital (1841–1849) to investigate the impact of handwashing practices introduced by Dr. Ignaz Semmelweis.  
Using Python, Pandas, Seaborn, Matplotlib and Plotly, the analysis demonstrates how maternal mortality dropped dramatically after chlorine handwashing became mandatory.

---

## 🎯 **Objectives**
- Analyze monthly and yearly birth/death data from two clinics.  
- Compare mortality before and after the introduction of handwashing.  
- Visualize trends using multiple chart types.  
- Quantify the impact using descriptive statistics and hypothesis testing.  
- Demonstrate that handwashing produced a statistically significant reduction in deaths.

---

## 📊 **Key Visualizations**
- **Monthly Births and Deaths Over Time**  
  Shows stable birth counts but highly unstable death counts, with a dramatic spike before handwashing.

- **Annual Births by Clinic**  
  Clinic 1 consistently handled more births, indicating higher workload.

- **Annual Deaths by Clinic**  
  Clinic 1 had significantly more deaths, revealing severe hygiene issues.

- **Maternal Death Percentage by Clinic**  
  Clinic 1 was two to three times deadlier than Clinic 2.

- **Monthly Maternal Death Rate Before and After Handwashing**  
  Shows a sharp drop in mortality after mid‑1847.

- **Box Plot of Monthly Death Rates**  
  Highlights the reduction in mean, spread, and extreme values.

- **Histogram + KDE Distribution**  
  Shows how the entire distribution shifted from high‑risk to low‑risk.

---

## 📈 **Statistical Findings**
### **Descriptive Statistics**
Before handwashing:  
- Mean monthly death rate ≈ **10.5%**  
- High variability and extreme values up to **31%**

After handwashing:  
- Mean monthly death rate ≈ **2.1%**  
- Much lower variability, maximum ≈ **4.9%**

### **T‑Test**
A two‑sample t‑test comparing the two periods yields:  
- **t‑statistic ≈ 5.51**  
- **p‑value = 0.0**

This means the difference is **extremely statistically significant**.  
We can be **more than 99% certain** that handwashing caused the reduction in deaths.

---

## 🧠 **Conclusion**
The analysis provides strong visual and statistical evidence that the introduction of handwashing drastically reduced maternal mortality.  
Semmelweis’s intervention transformed childbirth from a **high‑risk** to a **low‑risk** event, marking one of the most important breakthroughs in medical history.
