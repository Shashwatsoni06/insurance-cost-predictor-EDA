# Insurance-cost-predictor-EDA
omprehensive insurance cost analysis using advanced EDA techniques on 1,338+ insurance records. Features statistical analysis, risk factor identification, demographic insights, and feature engineering with correlation analysis and chi-square testing. Demonstrates Python, pandas, seaborn, and statistical modeling expertise for insurance analytics.

## 🔍 Project Overview

This project delivers an in-depth exploratory analysis of insurance cost data, uncovering critical patterns and factors that influence insurance premiums. Through rigorous statistical analysis and compelling visualizations, this work demonstrates practical applications of data science in insurance analytics and risk assessment.

**Key Achievement**: Analyzed 1,338 insurance records across 7 demographic and health variables to identify significant cost drivers and risk patterns in insurance pricing.

## 📊 Dataset Information

- **Records**: 1,338 insurance policyholders
- **Features**: 7 key variables (Age, Sex, BMI, Children, Smoker, Region, Charges)
- **Target Variable**: Insurance charges (continuous)
- **Data Quality**: Clean dataset with comprehensive feature coverage
- **Geographic Coverage**: 4 US regions (Southwest, Southeast, Northwest, Northeast)

## 🛠️ Technical Skills Demonstrated

### Advanced Data Analysis
- **Statistical Testing**: Chi-square tests for categorical feature selection
- **Correlation Analysis**: Pearson correlation coefficients for feature relationships
- **Feature Engineering**: BMI categorization and binary encoding
- **Data Preprocessing**: Standardization and categorical encoding
- **Feature Selection**: Statistical significance testing (p < 0.05)

### Python Libraries & Techniques
- **Data Manipulation**: Pandas for efficient data processing
- **Statistical Analysis**: NumPy for numerical computations
- **Visualization**: Matplotlib & Seaborn for professional plots
- **Feature Engineering**: Custom categorical transformations
- **Data Quality**: Missing value analysis and data validation

### Statistical Insights Generated
- **Smoking Status**: Highest correlation with charges (r = 0.787)
- **Age Factor**: Moderate positive correlation (r = 0.298)
- **BMI Impact**: Obesity category shows significant association
- **Gender Analysis**: Statistically significant but weak correlation
- **Feature Selection**: Identified 5 statistically significant predictors

## 📈 Key Analytical Findings

### Primary Cost Drivers (Statistical Significance)
- **Smoking Status**: Strongest predictor (χ² = 848.2, p < 0.001)
- **Gender**: Significant factor (χ² = 10.3, p = 0.016)
- **BMI Category**: Obesity shows significance (χ² = 8.5, p = 0.036)
- **Age**: Strong continuous correlation (r = 0.298)
- **Region**: Southeast shows highest correlation

### Feature Engineering Results
- **BMI Categorization**: Normal (BMI < 25), Overweight (25-30), Obese (>30)
- **Binary Encoding**: Gender and smoking status conversion
- **Regional Analysis**: One-hot encoding for geographic factors
- **Standardization**: Z-score normalization for continuous variables

## 🗂️ Project Structure

├── Insurence-EDA.ipynb # Complete EDA notebook with statistical analysis
├── insurance.csv # Clean, analysis-ready dataset (1,338 records)
├── README.md # Comprehensive project documentation
└── requirements.txt # Python dependencies

text

## 🚀 Getting Started

### Prerequisites
Python 3.8+
Jupyter Notebook or JupyterLab

text

### Installation & Execution
1. Clone the repository
git clone https://github.com/yourusername/insurance-cost-analysis-eda.git
cd insurance-cost-analysis-eda

text

2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter scipy

text

3. Launch the analysis
jupyter notebook Insurence-EDA.ipynb

text

## 📋 Analytical Workflow

1. **Data Import & Validation**: Dataset integrity and structure assessment
2. **Exploratory Analysis**: Descriptive statistics and distribution analysis
3. **Feature Engineering**: BMI categorization and binary encoding
4. **Statistical Testing**: Chi-square tests for categorical associations
5. **Correlation Analysis**: Pearson coefficients for continuous relationships
6. **Feature Selection**: Statistical significance filtering (α = 0.05)
7. **Data Preprocessing**: Standardization and encoding for modeling readiness
8. **Insights Generation**: Business-relevant pattern identification

## 💡 Business Impact & Applications

### Insurance Industry Applications
- **Premium Pricing**: Evidence-based risk assessment models
- **Underwriting**: Statistical decision support systems
- **Risk Segmentation**: Customer profiling for targeted products
- **Actuarial Modeling**: Feature importance for predictive models

### Healthcare Analytics
- **Cost Prediction**: Health-based insurance forecasting
- **Population Health**: Demographic risk analysis
- **Preventive Care**: Lifestyle factor impact assessment

### Data Science Methodologies
- **Statistical Rigor**: Hypothesis testing and significance analysis
- **Feature Engineering**: Domain-specific transformations
- **Data Quality**: Comprehensive validation and preprocessing
- **Reproducible Analysis**: Well-documented, executable workflow

## 🎯 Skills Highlighted for Recruiters

**Core Data Science Competencies:**
- Advanced statistical analysis and hypothesis testing
- Feature engineering and selection methodologies
- Insurance domain knowledge and actuarial concepts
- Professional data visualization and storytelling
- Python programming for data analysis

**Statistical Analysis:**
- Chi-square testing for categorical relationships
- Pearson correlation analysis
- Feature selection based on statistical significance
- Data standardization and normalization
- Categorical encoding techniques

**Industry Applications:**
- Insurance analytics and risk modeling
- Healthcare cost analysis
- Customer segmentation and profiling
- Predictive analytics foundations
- Financial services data science

## 📊 Key Statistical Results

- **Smoking Impact**: 78.7% correlation with insurance charges
- **Age Correlation**: 29.8% positive association with costs
- **Feature Significance**: 5 out of 12 features statistically significant
- **BMI Categories**: Obesity shows 20% correlation with charges
- **Model Readiness**: Preprocessed dataset with engineered features

## 🔮 Future Enhancements

- **Predictive Modeling**: Machine learning models for cost prediction
- **Advanced Segmentation**: Clustering analysis for customer profiles
- **Interactive Dashboard**: Streamlit/Dash web application
- **A/B Testing Framework**: Premium pricing optimization
- **Time Series Analysis**: Historical cost trend analysis

## 📞 Connect With Me

Interested in discussing data science opportunities in insurance, healthcare, or fintech? Let's connect!

- **LinkedIn**: www.linkedin.com/in/shashwat-soni-b3a1ba233
---

*This project demonstrates practical application of statistical analysis in insurance analytics, showcasing the ability to extract actionable business insights from complex datasets and translate statistical findings into strategic recommendations for the insurance industry.*

## 🏆 Project Highlights

- ✅ **Comprehensive Statistical Analysis**: Chi-square testing and correlation analysis
- ✅ **Advanced Feature Engineering**: BMI categorization and binary encoding
- ✅ **Professional Data Science Workflow**: From EDA to model-ready data
- ✅ **Business-Relevant Insights**: Actionable findings for insurance industry
- ✅ **Statistical Rigor**: Significance testing and proper methodology
- ✅ **Industry Application**: Real-world insurance analytics use case
