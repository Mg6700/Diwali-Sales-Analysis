# Diwali Sales Analysis

**Tools:** Python (Pandas, Matplotlib, Seaborn)  
**Domain:** Retail Analytics | Festive Sales | Customer Segmentation  
**Portfolio:** [mg67.vercel.app](https://mg67.vercel.app/) | **GitHub:** [Mg6700](https://github.com/Mg6700)

---

## Project Overview

This project analyzes Diwali festive sales data using Python to uncover customer demographics, product preferences, and regional purchasing patterns. The analysis covers 11,239 customers across multiple Indian states, examining how gender, age, marital status, occupation, and product category influence sales — delivering actionable marketing and inventory insights for the festive season.

---

## Tools & Libraries

| Library | Usage |
|---|---|
| Pandas | Data loading, cleaning, aggregation |
| Matplotlib | Bar charts, visualizations |
| Seaborn | Styled plots, heatmaps |
| Jupyter Notebook | Interactive analysis environment |

---

## Dataset

| Field | Description |
|---|---|
| Total Customers | 11,239 |
| Gender | Female (7,832) / Male (3,407) |
| Age Groups | 0–17, 18–25, 26–35, 36–45, 46–50, 51–55, 55+ |
| Marital Status | Unmarried (6,518) / Married (4,721) |
| States | UP, Maharashtra, Karnataka, Delhi, MP, AP, HP, Kerala, Haryana, Gujarat |
| Occupations | IT, Healthcare, Aviation, Banking, Govt, Retail, Media, Hospitality, Automobile, others |
| Product Categories | Clothing & Apparel, Food, Electronics, Footwear, Furniture, Games & Toys, and more |

---

## Analysis Sections

### 1. Gender Analysis
- **Customers by Gender:** 7,832 female vs 3,407 male
- **Sales by Gender:** Female customers drive ~₹70M vs male ~₹30M
- Female customers are both the majority buyer segment and higher spenders per head

### 2. Age Group Analysis
- **Customers by Age & Gender:** 26–35 age group leads (F: 1,272, M: 1,305 combined ~2,577)
- **Sales by Age Group:** 26–35 generates ~₹40M — far above all other age groups
- 36–45 and 18–25 are secondary contributors

### 3. Marital Status Analysis
- **Unmarried customers (6,518)** outnumber married (4,721)
- **Unmarried females** are the single highest-spending segment — approaching ₹40M alone
- Married customers of both genders spend significantly less per segment

### 4. Product Category Analysis
- **Top categories by orders:** Clothing & Apparel (2,655), Food (2,490), Electronics (2,087)
- **Bottom categories:** Hand & Power Tools (26), Tupperware (72), Books (103)
- **Top categories by gender:** Females lead in Food (~₹25M) while males are secondary across all categories

### 5. Occupation Analysis
- **Top occupations by orders:** IT Sector (1,583), Healthcare (1,408), Aviation (1,310)
- **Bottom occupations:** Agriculture (283), Textile (349), Construction (414)
- **By gender:** IT sector males and Healthcare females are the highest-spending occupation-gender combinations

### 6. State Analysis
- **Top states by orders:** Uttar Pradesh (~4,800), Maharashtra (~3,800), Karnataka (~3,200)
- **Sales by state & gender:** UP leads with ~₹14M female + ~₹6M male = ~₹20M total
- Gujarat has the lowest orders (~1,000)

### 7. Product ID Analysis
- Top product: **P00265242** with ~128 orders — highest single product demand
- Top 10 products range from ~75 to ~128 orders each

---

## Key Findings

**1. Female customers drive 70% of revenue despite being 70% of the customer base**
The female dominance is proportional — 7,832 women (69.7%) generating ~₹70M of ~₹100M total. Marketing and inventory must center on female preferences.

**2. Unmarried females aged 26–35 in IT/Healthcare are the highest-value customer profile**
Combining age (26–35), marital status (unmarried), gender (female), and occupation (IT/Healthcare) reveals the core high-value segment — young professional women with disposable income spending on Diwali.

**3. Clothing & Apparel leads orders (2,655) — Diwali is primarily a fashion shopping event**
The top 3 categories (Clothing, Food, Electronics) account for over 60% of all orders, confirming that festive shopping is driven by gifts, food, and apparel rather than utility purchases.

**4. IT sector professionals are the most active shoppers (1,583 orders)**
Tech workers with higher salaries spend more freely during festive seasons — a key demographic for premium product targeting.

**5. Uttar Pradesh alone accounts for ~25% of total orders**
UP's dominance (UP + Maharashtra + Karnataka = ~58% of orders) suggests heavy geographic concentration — logistics and marketing should prioritize these three states.

**6. Agriculture, Textile, and Construction workers show minimal engagement**
Lower-income occupations show significantly less festive shopping activity — the Diwali sales customer base skews heavily toward white-collar, urban professionals.

---

## Conclusions & Recommendations

| Insight | Recommendation |
|---|---|
| Female 26–35 drives revenue | Target all Diwali campaigns at young urban women |
| IT/Healthcare top spenders | Premium product promotions via tech and health platforms |
| UP/Maharashtra/Karnataka dominate | Prioritize these 3 states for logistics and inventory |
| Clothing #1 category | Expand festive apparel catalog, offer bundled gift options |
| Unmarried customers lead | Focus on self-purchase and gifting messaging vs family messaging |

---

## How to Run

1. Clone the repository
2. Install dependencies: `pip install pandas matplotlib seaborn jupyter`
3. Open `Diwali_Sales_Analysis.ipynb` in Jupyter Notebook
4. Run all cells sequentially

---

## Data Source

Diwali Sales Dataset — Kaggle.

---

*Created by Mayur Goyal | [Portfolio](https://mg67.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mg67)*
