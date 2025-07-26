# OTTO Multi-Objective Recommender System Analysis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)

A comprehensive data science project analyzing e-commerce user behavior and building insights for recommendation systems using the OTTO Multi-Objective Recommender System dataset from Kaggle.

## 🎯 Project Overview

This project performs in-depth exploratory data analysis (EDA) on the OTTO e-commerce dataset to understand user behavior patterns, product interactions, and temporal dynamics that drive recommendation systems. The analysis provides actionable insights for improving click-through rates, cart additions, and order conversions.

### Key Business Questions Addressed
- How do users interact with products across different touchpoints (clicks, carts, orders)?
- What are the conversion patterns from product views to purchases?
- Which articles drive the highest engagement and sales?
- How does time spent on products correlate with purchase intent?
- What co-occurrence patterns exist between products?

## 🛠️ Technologies & Tools

**Data Science Stack:**
- **Python 3.8+** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning utilities (CountVectorizer, sparse matrices)
- **SciPy** - Scientific computing (sparse matrix operations)

**Visualization & Analysis:**
- **Seaborn** - Statistical data visualization
- **Matplotlib** - Plotting library
- **Jupyter Notebooks** - Interactive development environment

**Data Processing:**
- **JSONL** parsing for large-scale data
- **Sparse matrix operations** for memory-efficient computations
- **Time series analysis** for temporal patterns

## 📊 Key Features & Analysis

### 1. User Behavior Analytics
- **Session Analysis**: User engagement patterns across 150K+ sessions
- **Product Interaction Mapping**: Click → Cart → Order conversion funnels
- **Time-based Patterns**: Session duration and product engagement timing

### 2. Product Intelligence
- **Article Performance Metrics**: Click, cart, and order frequency analysis
- **Conversion Rate Analysis**: 
  - 25.7% click-to-cart conversion rate
  - 38.6% cart-to-order conversion rate
  - 9.9% overall click-to-order conversion rate

### 3. Advanced Analytics
- **Co-occurrence Matrix**: 830K+ product co-visitation analysis using sparse matrices
- **Transition Analysis**: Product sequence patterns using n-gram analysis
- **Temporal Dynamics**: Time-spent analysis per product and event type

### 4. Statistical Insights
- Most users interact with 2-6 products per session
- 94% of product co-occurrences happen only once, indicating diverse user preferences
- Users spend more time on products they eventually order (228.7s vs 217.4s)

## 📈 Business Impact & Insights

1. **Personalization Opportunities**: Strong time-spend correlation with purchase intent enables better recommendation targeting
2. **Inventory Optimization**: 25% of products receive >5 clicks, indicating core inventory focus areas
3. **User Experience**: Session patterns reveal optimal engagement timeframes and product presentation strategies
4. **Cross-selling Potential**: Co-occurrence analysis identifies product bundling opportunities

## 🚀 Getting Started

### Prerequisites
```bash
pip install -r requirements.txt
```

### Dataset
Download the OTTO Multi-Objective Recommender System dataset from [Kaggle](https://www.kaggle.com/competitions/otto-recommender-system)

### Running the Analysis
```bash
jupyter notebook otto-eda-exploratory-data-analysis.ipynb
```

## 📁 Project Structure
```
recsys_otto/
├── README.md                                    # Project documentation
├── LICENSE                                      # MIT License
├── otto-eda-exploratory-data-analysis.ipynb   # Main analysis notebook
└── requirements.txt                            # Python dependencies
```

## 🔍 Technical Highlights

- **Big Data Processing**: Efficient handling of 13M+ sessions and 217M+ events using chunked processing
- **Memory Optimization**: Sparse matrix implementations for co-occurrence analysis (99.97% sparse)
- **Statistical Rigor**: Comprehensive statistical analysis
- **Scalable Architecture**: Modular code design supporting multiprocessing and distributed computing extensions

## 📊 Sample Results

- **Dataset Scale**: 830,140 unique products across 150,000 analyzed sessions
- **User Engagement**: Average session spans multiple days with peak activity around 30-second intervals
- **Product Performance**: Clear performance tiers with top 25% of products driving majority of interactions
- **Behavioral Patterns**: Distinct user segments with varying engagement depths (1-460 products per session)

## 🎓 Skills Demonstrated

**Data Science:**
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Time Series Analysis
- Recommendation System Analytics

**Technical:**
- Large-scale Data Processing
- Sparse Matrix Computations
- Memory-efficient Algorithm Design
- Data Visualization & Storytelling

**Business:**
- E-commerce Analytics
- Conversion Funnel Analysis
- User Behavior Modeling
- Performance Metrics & KPIs

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Akshay Sharma**
- Data Scientist
- Expertise in large-scale data processing and machine learning

---

*This project demonstrates advanced data science capabilities in e-commerce analytics, recommendation systems, and large-scale data processing - ideal for roles in data science, machine learning engineering, and business intelligence.*
