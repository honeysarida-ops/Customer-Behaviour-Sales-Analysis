# 🛒 Customer Behaviour & Sales Analysis

**Exploratory analysis of transactions to uncover revenue drivers, customer patterns, and delivery/satisfaction dynamics.**

---

## 📌 Project Highlights

| | |
|---|---|
| **Type** | Exploratory Data Analysis (EDA) |
| **Language / Tools** | Python, pandas, matplotlib, seaborn |
| **Skills demonstrated** | Data cleaning, time-series aggregation, group-by analysis, multi-chart visualization storytelling |
| **Status** | Complete — demo/learning notebook |

---

## 🎯 Objective

Explore an transactions dataset to answer practical business
questions: which product categories drive revenue, how customers behave by
device/payment method, how delivery time relates to satisfaction, and how
revenue trends over time.

## 🧩 Approach

1. **Data quality checks** — shape, dtypes, nulls, and summary statistics.
2. **Customer demographics** — age distribution, gender split, top cities by
   customer count.
3. **Revenue analysis** — total and average revenue by product category, plus
   a combined category summary (sum, mean, count, rating, quantity).
4. **Channel & payment behaviour** — device type split, average order value
   by payment method.
5. **Satisfaction** — distribution of customer ratings, and average rating by
   product category.
6. **Time trend** — monthly revenue trend using a `Year_Month` period column.
7. **Customer loyalty** — average spend for returning vs. new customers.
8. **Delivery performance** — delivery time distribution and its relationship
   to customer rating.

## 📈 Results

- Clear differences in revenue and average order value across product
  categories (see the notebook for the category breakdown table).
- Delivery time shows a visible relationship with customer rating — faster
  deliveries trend toward higher satisfaction.
- Monthly revenue trend highlights whether the business is growing,
  seasonal, or flat over the observed period.

## 🗂️ Files

| File | Description |
|---|---|
| `customer-behaviour-sales-analysis.ipynb` | Full notebook — EDA, revenue analysis, delivery/satisfaction analysis |
| `customer-behaviour-sales-analysis.pdf` | Read-only, formatted export of the notebook |

## ⚙️ Requirements

```
python >= 3.9
numpy
pandas
matplotlib
seaborn
```

```bash
pip install numpy pandas matplotlib seaborn
```

## ⚠️ Known Limitations

- **Purely descriptive** — this is EDA, not predictive modeling; findings are
  correlational, not causal (e.g. faster delivery correlating with higher
  ratings doesn't prove delivery speed *causes* the rating).
- **No statistical testing** — differences between groups (e.g. categories,
  payment methods) are visual only, not confirmed with hypothesis tests.
- **Single dataset snapshot** — no cross-validation against another time
  period or source to confirm trends are stable.

## 🚀 Possible Next Steps

- Add statistical tests (e.g. ANOVA, chi-square) to confirm whether observed
  differences are significant.
- Build a simple revenue forecasting model on the monthly trend.
- Segment customers (e.g. RFM analysis) to complement the category-level view
  with a customer-level one.
