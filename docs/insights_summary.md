# 📝 Insights Summary — Customer Behavior Analytics

*Detailed written analysis supporting the Power BI dashboard findings.*

---

## 1. Revenue Performance

### Category Breakdown
| Category | Revenue | Share |
|---|---|---|
| Clothing | $104K | 45% |
| Accessories | $74K | 32% |
| Footwear | $36K | 15% |
| Outerwear | $19K | 8% |

**Analysis:** Clothing dominates revenue but also carries the highest concentration of Fair reviews. This creates a risk — high revenue reliance on a category where customer satisfaction is mediocre. Accessories performs strongly as the second category, and both deserve dedicated marketing attention.

### Age Group Breakdown
| Age Group | Revenue |
|---|---|
| Young Adults | $62K |
| Middle-aged | $59K |
| Adults | $56K |
| Senior | $56K |

**Analysis:** Revenue is relatively balanced across age groups, with Young Adults slightly ahead. Marketing campaigns should not over-index on a single demographic; however, retention strategies for Young Adults could yield outsized returns given their slight lead.

### Geographic Insights
Montana ($5.8K), Illinois ($5.6K), and California ($5.6K) are the top three revenue-generating states. The top 10 locations are tightly clustered between $5.2K–$5.8K, indicating geographically distributed demand — a positive sign for national campaigns.

---

## 2. Customer Segmentation & Engagement

### Gender Gap Analysis
This is the most significant finding in the dataset and warrants immediate investigation.

| Metric | Male | Female |
|---|---|---|
| Discount Rate | 43% | 0% |
| Subscription Rate | 39.71% | 0% |
| Revenue (Clothing) | $71K | $34K |
| Revenue (Accessories) | $50K | $24K |

**Possible Explanations:**
- Data quality issue — female discount/subscription data may be missing or miscoded
- Systemic bias in how promotions were distributed (e.g., channel-specific campaigns that didn't reach female customers)
- Female customers may represent a distinct acquisition channel that was never enrolled in loyalty programs

**Recommended Action:** Audit the data pipeline for gender-based filtering errors. If the data is accurate, urgently design inclusive discount and subscription outreach targeting female customers.

### Subscription Program
At 27% overall subscription rate (all male), the program has significant headroom for growth. If female customers (~50% of the base) were enrolled at even a 20% rate, subscription penetration would rise to ~37%, meaningfully improving CLV and retention metrics.

---

## 3. Product Performance & Review Analysis

### Review Sentiment Distribution
| Sentiment | Count | % |
|---|---|---|
| Fair | 1,564 | ~40.1% |
| Average | 817 | ~21% |
| Good | 761 | ~19.5% |
| Excellent | 692 | ~17.7% |
| Poor | ~66 | 1.69% |

**Analysis:** The dominance of "Fair" reviews is the clearest signal for product teams. Fair is not negative — customers aren't angry — but they are underwhelmed. This is a conversion opportunity: nudging Fair reviewers to Good/Excellent through targeted improvements (packaging, quality, delivery experience) could significantly lift NPS.

### Category-Level Review Distribution
| Category | Poor | Fair | Average | Good | Excellent |
|---|---|---|---|---|---|
| Clothing | 41.91% | 21.07% | 18.42% | 17.04% | — |
| Accessories | 39.84% | 20.00% | 20.08% | 18.31% | — |
| Footwear | 36.56% | 22.37% | 19.53% | 19.87% | — |
| Outerwear | 37.96% | 21.30% | 23.15% | 15.43% | — |

**Footwear** has the lowest Fair rate (36.56%) and the highest Excellent rate — making it the benchmark for customer satisfaction. Understanding what Footwear does right (quality, sizing accuracy, product descriptions) and applying those learnings to Clothing could have significant revenue impact.

---

## 4. Strategic Recommendations Summary

### Short-Term (0–3 months)
1. Audit female customer discount and subscription data for data integrity issues
2. Launch a targeted email/loyalty campaign for female customer subscription enrollment
3. Conduct qualitative research (surveys, review text analysis) to understand Fair review drivers in Clothing

### Medium-Term (3–6 months)
4. Implement a Footwear-style quality checklist across Clothing and Accessories production/sourcing
5. A/B test discount strategies for underrepresented segments
6. Build a review monitoring dashboard to track sentiment shifts in real time

### Long-Term (6–12 months)
7. Develop a CLV (Customer Lifetime Value) model segmented by gender, age group, and subscription status
8. Expand subscription program with tiered benefits to increase the 27% participation rate
9. Use geographic revenue data to prioritize regional marketing spend

---

*Document prepared as part of the Customer Behavior Analytics Power BI project.*
*Author: Anis | Date: June 2026*
