# Bootstrap-and-Jackknife
Exploring resampling statistics through Bootstrap and Jackknife methods to estimate the mean, median, and variance, while visualizing their distributions. This approach is ideal for learning practical statistics in Python. 📊

# 📊 Bootstrap vs. Jackknife Estimation: Resampling Statistics in Python

Welcome to the project that explores statistical resampling using **Bootstrap** and **Jackknife**! 🎯  
The goal of this project is to understand how both techniques can be used to estimate the **mean**, **median**, and **variance**, while also evaluating the stability of these estimates using **Confidence Intervals (CI)** and **Mean Squared Error (MSE)**.

---

## 🧠 Methods Used

### Bootstrap
- Performs **resampling with replacement**.
- Calculates statistical distributions (mean, median, and variance) based on 1000 bootstrap samples.
- Used to measure statistical uncertainty (variability).

### Jackknife
- Removes one observation per iteration to create a new sample.
- Suitable for small datasets.
- Provides insight into the stability of the estimator when the data changes slightly.

---

## 📈 Visualization

- Histograms and Kernel Density Estimation (KDE) for the bootstrap mean and median distributions.
- Histograms and KDE for the jackknife mean and median distributions.
- Confidence Intervals (CI) for mean, median, and variance.

---

## 💡 Key Features

✅ Modular code (reusable functions)  
✅ CI and MSE analysis  
✅ Visualization using Seaborn and Matplotlib  
✅ Graph explanations and statistical interpretations  
✅ Educational documentation and narrative  

## 📁 Project Structure
```
├── BootStrap_and_JackKnife.ipynb  # Main code
├── README.md                # Documentation
```

---

## 🧪 Example Results

🎯 **Bootstrap CI (95%)**  
- Mean: [47.25, 50.62]  
- Median: [46.90, 50.50]  
- Variance: [65.88, 97.63]

🎯 **Jackknife CI (95%)**  
- Mean: [47.38, 49.16]  
- Median: [47.66, 47.66]  
- Variance: [75.27, 92.15]

---

✨ Additional Notes  
* Bootstrap is more suitable for large datasets, as it provides smooth distribution estimates.
* On the other hand, Jackknife is limited to smaller datasets but remains useful for variance estimation and outlier detection.
* This project can be expanded to include real datasets or additional methods such as Bayesian Bootstrap or Cross-Validation..
