# TV Usage Analysis: Consumer Brand Preferences and Market Trends

## Project Overview

This project analyzes consumer brand preferences for televisions in the modern streaming era. With the rise of internet services and streaming devices, TV consumption patterns have evolved significantly. This analysis examines brand preferences, resolution trends, pricing strategies, and consumer attitudes toward television usage and utility.

## Dataset Description

**Dataset:** Television Market Analysis  
**Size:** 912 samples with 7 attributes  
**Source:** Market research data on television specifications and consumer ratings

### Dataset Attributes:
- **Brand**: Television manufacturer/brand name
- **Resolution**: Display resolution specifications  
- **Size**: Screen size measurements
- **Selling Price**: Current market selling price
- **Original Price**: Manufacturer's suggested retail price
- **Operating System**: Smart TV operating system
- **Rating**: Consumer rating/satisfaction score

## Research Questions

This analysis addresses the following key business questions:

1. **Market Leadership**: What are the top 5 television brands by market presence?
2. **Price Analysis**: How do average selling prices vary across brands and resolutions?
3. **Statistical Validation**: What are the descriptive statistics for selling price and consumer ratings?
4. **Distribution Testing**: Is the pricing data normally distributed (Shapiro-Wilk test)?
5. **Market Demand**: Which segments show higher demand for digital/smart TVs?
6. **Premium Positioning**: Analysis of Samsung's market position across resolution categories

## Methodology

### Statistical Analysis
- **Descriptive Statistics**: Comprehensive analysis of selling prices and ratings
- **Hypothesis Testing**: Statistical validation of market assumptions
- **Normality Testing**: Shapiro-Wilk test for price distribution
- **Non-parametric Testing**: Alternative statistical methods for non-normal distributions

### Data Visualization
- Average selling price analysis by brand
- Resolution category comparisons
- Market share visualization
- Price-rating correlation analysis
- Brand positioning maps

### Key Findings Preview
- Samsung emerges as a premium brand leader across multiple resolution categories
- Clear price differentiation between resolution tiers
- Consumer rating patterns correlate with price positioning
- Digital TV adoption shows specific market segment preferences

## Tools and Technologies

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib/Seaborn**: Data visualization
- **SciPy**: Statistical testing
- **Jupyter Notebook**: Interactive development environment

## Business Impact

This analysis provides valuable insights for:
- **Manufacturers**: Understanding competitive positioning and pricing strategies
- **Retailers**: Inventory planning and market segment targeting
- **Consumers**: Informed purchasing decisions based on value analysis
- **Market Analysts**: Television industry trend identification

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/AchuRamu/tv-usage-analysis.git
   cd tv-usage-analysis
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter notebook:
   ```bash
   jupyter notebook tv-usage-analysis.ipynb
   ```

4. Run all cells to reproduce the analysis

### Dataset
The analysis uses `TV_Final.csv` containing 912 television specifications with the following columns:
- Brand, Resolution, Size, Selling Price, Original Price, Operating System, Rating

*Note: Original analysis was conducted in Google Colab. Data loading paths have been updated for local execution.*

## Project Structure

```
tv-usage-analysis/
│
├── tv-usage-analysis.ipynb    # Main analysis notebook
├── README.md                  # Project documentation
├── data/                      # Dataset files (if included)
└── visualizations/           # Generated charts and graphs
```

## Key Insights

- Comprehensive brand comparison across 912 television models
- Statistical validation of market positioning claims
- Data-driven recommendations for consumer purchasing decisions
- Market trend analysis supporting business strategy development

## Contact

**Archana Ramachandran**  
Data Scientist | Software Engineer  
📧 aramach82@gmail.com  
🔗 LinkedIn: [linkedin.com/in/archana-ramachandran](https://www.linkedin.com/in/archana-ramachandran)

---

*This project demonstrates proficiency in statistical analysis, data visualization, hypothesis testing, and market research methodologies using Python and data science libraries.*
