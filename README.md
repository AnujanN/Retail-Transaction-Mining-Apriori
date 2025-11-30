# Retail Transaction Optimization using Association Rule Mining

A Machine Learning project that applies the Apriori algorithm with customer segmentation to optimize Buth Kade restaurant layout and improve customer experience.

## 📊 Project Overview

This project analyzes 5,076+ synthetic transactions to discover purchasing patterns and generate actionable business insights for local rice and curry shops.

## 🔧 Technologies Used

- **Python 3.8+**
- **pandas** - Data manipulation and analysis
- **mlxtend** - Association rule mining (Apriori algorithm)
- **scikit-learn** - K-Means clustering
- **matplotlib/seaborn** - Data visualization
- **fpdf** - PDF presentation generation

## 📁 Project Structure

```
├── Buth_Kade.ipynb              # Main analysis notebook
├── buth_kade_transactions.csv   # Dataset (5,076 transactions)
├── present.py                   # PDF presentation generator
├── presentation_script.md       # 2:30 min presentation script
├── slide_presentation_script.md # 1:30 min fast script
└── technical_walkthrough_script.md # Cell-by-cell explanation
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/AnujanN/Retail-Transaction-Mining-Apriori.git
   cd Retail-Transaction-Mining-Apriori
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy mlxtend scikit-learn matplotlib seaborn fpdf
   ```

3. **Run the analysis**
   - Open `Buth_Kade.ipynb` in Jupyter Notebook or VS Code
   - Execute all cells sequentially

4. **Generate presentation**
   ```bash
   python present.py
   ```

## 🎯 Key Features

- **Data Preprocessing**: Missing value handling, item standardization
- **Feature Engineering**: Base starch classification, time binning, dietary flags
- **Customer Segmentation**: K-Means clustering (3 segments)
- **Association Rule Mining**: Apriori algorithm with hyperparameter tuning
- **Business Insights**: Layout optimization, combo recommendations

## 📈 Results

- **99% efficiency gain** through Apriori's anti-monotonicity principle
- **72% average confidence** in discovered association rules  
- **2.8x average lift** proving significant item correlations
- **3 distinct customer segments** identified for targeted marketing

## 🏢 Business Applications

1. **Layout Optimization**: Place frequently co-purchased items adjacently
2. **Menu Engineering**: Create data-driven combo offerings
3. **Inventory Planning**: Stock ratios based on association patterns
4. **Customer Segmentation**: Targeted promotions per cluster

## 📋 Requirements

```
pandas
numpy
mlxtend
scikit-learn
matplotlib
seaborn
```

## 👨‍💻 Author

**Anujan N** - CM3720 Machine Learning Project  
University of Moratuwa, Department of Computational Mathematics

## 📄 License

This project is created for educational purposes as part of CM3720 coursework.