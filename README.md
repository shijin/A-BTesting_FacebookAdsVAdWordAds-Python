# A/B Testing Analysis: Facebook vs. Adwords

This project analyzes ad performance data from Facebook and Google Adwords to determine which platform delivers better ROI based on marketing KPIs like CTR, CPC, Conversion Rate, and Cost per Conversion.

---

## Objective

To evaluate and compare the efficiency of Facebook and Adwords campaigns using historical ad performance data.

---

## Dataset Overview

The dataset includes:
- Views
- Clicks
- Conversions
- CTR (Click-through Rate)
- CPC (Cost per Click)
- Conversion Rate
- Cost per Ad
- Cost per Conversion
- Platform
- Date and Month

---

## Key Analysis

- Platform-wise performance comparison (CTR, CPC, Conversion Rate)
- Time-series trends for each platform
- Monthly trends in total conversions
- Cost efficiency evaluation using Cost per Conversion
- Statistical testing (t-test) for significance in CTR, CPC, and Conversion Rate

---

## Insights

- Facebook campaigns achieved better overall performance in CTR and Conversion Rate.
- Adwords campaigns incurred higher costs per conversion.
- July 2023 showed a notable spike in conversions, but due to inconsistent campaign timing and lack of objective details, the reason remains unclear.
- Ads appear to be run on an irregular basis, possibly seasonal or based on promotions.

---

## Tools Used

- Python (Pandas, Matplotlib, Seaborn, Scipy)
- Jupyter Notebook

---

## Conclusion

Facebook outperformed Adwords in this A/B testing scenario based on available metrics. However, strategic campaign planning and consistent objective-based tracking would improve the validity of future tests.

---

## How to Use

1. Clone this repository
2. Open the Jupyter Notebook: `A B Testing - Facebook vs. Adwords.ipynb`
3. Run each cell step-by-step to view the analysis

---

### To Run on Google Colab:
1. Open this notebook in Colab:  
   [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/shijin/A-BTesting_FacebookAdsVAdWordAds-Python/blob/main/A%20B%20Testing%20-%20Facebook%20vs.%20Adwords.ipynb)

2. Upload the dataset manually:  
   - Click the file icon (left sidebar in Colab)
   - Click **Upload**, then select `A_B_testing.csv`  
   *(or run the cell `from google.colab import files` to upload interactively)*

3. Alternatively, replace the `read_csv()` line with a GitHub raw link:
```python
df = pd.read_csv('https://github.com/shijin/A-BTesting_FacebookAdsVAdWordAds-Python/blob/main/A_B_testing.csv')
```
---

## Author

Shijin Ramesh
LinkedIn: [View Link](www.linkedin.com/in/shijinramesh)
