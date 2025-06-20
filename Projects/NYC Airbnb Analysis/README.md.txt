# 🏙️ Manhattan Airbnb Investment Analysis

## 📊 Executive Summary

This project provides **data-driven recommendations** for investing in Manhattan’s vacation rental (Airbnb) market. The goal is to identify the most attractive neighborhoods and property types and estimate their revenue potential using the NYC Airbnb dataset.

Key insights:
- **Top Neighborhoods**: Lower East Side, East Village, Harlem, Hells Kitchen, Upper West Side, West Village, Chelsea, East Harlem, Upper East Side, and Midtown.
- **Best Property Types**: 1-bedroom properties dominate performance in most neighborhoods. **Studios** perform well specifically in Midtown.
- **Revenue Potential**:
  - Top listings earn an **average of $75,190 annually**.
  - Exceptional listings exceed **$100,000** in annual revenue.
  - Example: ID `6833395` generates $273,600; ID `3662827` earns $720,000.

---

## ✅ Recommendations

### 🔹 Investment Focus
- Prioritize **1-bedroom properties** in high-demand neighborhoods listed above.
- For **Midtown**, target **studio apartments**, which demonstrate competitive revenue (e.g., ID `52553537` with $115,116).

### 🔹 Revenue Strategy
- Optimize for:
  - High occupancy.
  - Competitive pricing.
  - Strong guest experience and reviews.
- Use high-performing listings (e.g., ID `3662827`) as **benchmarks** for revenue strategy and positioning.

### 🔹 Operational Considerations
- Maintain **high listing quality** to drive positive reviews and repeat bookings.
- **Validate revenue estimates** with longer booking histories; current projections are based on 30-day data extrapolated over a year.
- **Diversify across neighborhoods** to reduce market risk and improve stability.

---

## 🔍 Methodology & Assumptions

- **Attractiveness Proxy**: 
  - Used `number_of_reviews_ltm` (reviews in the last 12 months) as a **proxy for rental frequency**.
- **Revenue Calculation**: 
  - Revenue was estimated by extrapolating the last 30 days of booking data, assuming a steady occupancy and pricing trend.
- **Missing Bedrooms**: 
  - Listings with missing values in the `bedrooms` column were assumed to be **studio apartments**.

---

- **`README.md`**  
  This documentation file outlining the purpose, findings, and how to use the analysis.

---

## 📌 Conclusion

Investing in **1-bedroom Airbnb rentals** in neighborhoods like the **Lower East Side, East Village, and Harlem**, or in **studio units in Midtown**, presents a compelling opportunity in Manhattan’s vacation rental market.

By focusing on high-demand locations and leveraging proven pricing strategies from top listings, investors can expect solid annual returns—**often exceeding $75K**, with exceptional cases far surpassing that mark.