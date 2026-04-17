# phishing-detection-analysis
Cybersecurity data analysis project using Python
# Phishing Detection Data Analysis (Cybersecurity Project)

## Overview
This project analyzes a large-scale phishing dataset (600,000+ URLs) to identify patterns and indicators of malicious websites. Using data-driven techniques, the analysis explores how URL characteristics such as length, numeric density, structure, and special symbols contribute to phishing detection.

The goal of this project is to demonstrate how statistical analysis and data visualization can improve cybersecurity decision-making and help identify high-risk web behavior.

---

## Dataset
- Source: Kaggle Phishing Dataset
- Size: ~600,000+ observations
- Focus: URL-based phishing detection features

---

## Tools & Technologies
- Python (pandas, numpy, matplotlib, seaborn)
- Excel (descriptive statistics, outlier detection)
- Tableau (data visualization)
- Statistical Testing (t-test, Mann-Whitney U, Chi-square)

---

## Key Analysis Areas

### 1. HTTPS vs Phishing Behavior
- Found that HTTPS-related URLs had a disproportionately high phishing rate (~76.6%)
- Demonstrates that attackers exploit HTTPS to build trust

### 2. Numeric Density & URL Length
- URL length is a strong indicator of phishing risk
- Numeric characters alone are inconsistent but become powerful when combined with length

### 3. Statistical Analysis of URL Length
- Welch’s t-test and Mann-Whitney U test confirmed statistically significant differences
- Weak correlation (r ≈ -0.13) shows URL length alone is not sufficient for detection
- U-shaped risk pattern: both very short and very long URLs are high-risk

### 4. URL Structure (Dots & Dashes)
- High counts of dots and dashes strongly correlate with phishing behavior
- Outliers represent real attacker strategies, not noise

### 5. Special Symbols & Path Length
- The “@” symbol is rare but a strong phishing indicator
- Path length varies widely and must be interpreted with other features

---

## Key Findings
- No single variable reliably detects phishing
- Combining multiple URL features significantly improves detection accuracy
- Attackers use multiple strategies (simple vs complex URLs)
- Outliers are critical and represent real-world cyber threats
- HTTPS should not be used as a sole indicator of security

---

## Cybersecurity Implications
This project highlights the importance of multi-feature detection systems in cybersecurity. Organizations should:
- Avoid relying on single indicators (like HTTPS)
- Implement layered detection strategies
- Train users to recognize both obvious and subtle phishing patterns

---

## My Contributions
- Conducted statistical analysis on URL length vs phishing classification
- Performed hypothesis testing (Welch’s t-test, Mann-Whitney U, Chi-square)
- Built Python-based visualizations (heatmaps, histograms, bar charts)
- Interpreted statistical results and cybersecurity implications
- Assisted in structuring data insights into actionable findings

---

## Team Members
- Dan Haniff
- Albina Martynenko
- Zoe Rodriguez
- Chao Han Yang
- Luke Yates

---

## Files Included
- Python analysis scripts
- Dataset (or sample dataset)
- Excel analysis
- Final report (PDF)

---

## Future Improvements
- Implement machine learning models for phishing classification
- Build real-time phishing detection system
- Expand dataset to include behavioral and network-level features
