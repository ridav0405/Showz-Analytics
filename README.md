# Showz-Analytics

###  📊 Project Description
Comprehensive analysis of digital marketing data to determine the effectiveness of different user acquisition channels and optimize marketing strategy. The project includes analysis of user behavior, conversion rates, customer lifetime value (LTV), and return on marketing investment (ROMI).

### 🎯 Objectives
Analyze user behavior on the platform
Determine when and how users make their first purchases
Calculate customer lifetime value
Evaluate the effectiveness of different marketing channels
Determine when revenue covers the cost of customer acquisition

### 📈 Datasets Used
visits_log_us.csv: User visit log (359,400 records)
orders_log_us.csv: Order and revenue log (50,415 records)
costs_us.csv: Marketing costs by source (2,542 records)

### 🛠️ Technologies Used
Python 3.9
Pandas
Data manipulation and analysis
NumPy
Numerical calculations
Matplotlib & Seaborn
Data visualization
Jupyter Notebook
Development and documentation

### 🔍 Key Findings
### User Behavior
- 228,169 unique users with 359,400 total sessions
- Retention rate: 22.8% (52,128 returning users)
- Average session duration: 644 seconds
- 77.2% of users make only one visit

### Conversions and Sales
- Overall conversion rate: 16.0% (36,523 out of 228,169 users)
- 72.2% of conversions occur on the same day as the first visit
- Average time to conversion: 16.7 days
- Average order value: $4.99

### Customer Segmentation
| Segment | % Customers | Average LTV | Revenue Contribution |
|----------|------------|--------------|-------------------------|
| One-time buyers | 83% | $3.99 | 48% |
| Repeat buyers | 15% | $9.26 | 20% |
| Frequent buyers | 2.2% | $99.41 | 32% |

### Marketing Analysis (ROMI)
| Source | Total Expenditure | Revenue | ROMI | ROI |
|--------|-------------|----------|------|-----|
| Source 1 | $20,833 | $101,631 | 387.8% | 4.88x |
| Source 9 | $5,517 | $18,810 | 240.9% | 3.41x |
| Source 2 | $42,806 | $113,525 | 165.2% | 2.65x |
| Source 3 | $141,322 | $119,193 | -15.7% | 0.84x |