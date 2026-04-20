# hotel-cancellation-analysis
# Predicting Hotel Cancellations: A Data-Driven Approach to Revenue Protection

**One-line hook:** This project leverages predictive analytics to identify at-risk hotel bookings, enabling proactive strategies to reduce cancellations and safeguard hotel revenue.

---

## The Business Problem

A Portuguese hotel chain faces significant revenue losses due to a high volume of booking cancellations. With over one-third of all bookings being canceled, accurately predicting which reservations are likely to fall through is critical for optimizing room inventory, managing operational costs, and maximizing occupancy. Without a predictive model, the hotel struggles to proactively address these cancellations, leading to lost revenue from empty rooms or the cost of overbooking.

## The Data

We analyzed a comprehensive dataset of nearly 120,000 individual hotel bookings made between 2015 and 2017. This data captures a wide range of information, including how far in advance guests booked (lead time), their market segment, deposit type, number of guests (adults, children, babies), country of origin, and special requests. This rich detail allows us to understand the various factors influencing booking behavior and cancellation decisions.

## Key Discoveries

- **Longer Lead Times, Higher Cancellation Risk:** Bookings made significantly far in advance (e.g., several months) show a much greater propensity for cancellation, suggesting less firm plans among early bookers.
- **Market Segment Matters:** Certain market segments, particularly 'Groups' and 'Online TA' (Travel Agent), exhibit notably higher cancellation rates, indicating specific channels or customer types pose greater risks.
- **Non-Refundable Deposits Secure Bookings:** Bookings with 'Non Refund' deposit types have a near-zero cancellation rate, while 'No Deposit' bookings have a substantial cancellation rate, highlighting the effectiveness of stricter deposit policies.

## Visualizing the Story

<!-- Embed your most compelling chart. Pick the ONE visual that best captures your main finding. -->

![Cancellation Rate by Deposit Type](your_chart_filename.png)

*This chart powerfully illustrates how the type of deposit dramatically influences the likelihood of a booking being canceled. 'Non Refund' deposits effectively eliminate cancellations, while 'No Deposit' bookings remain a high-risk category.*

## Prediction Model

Our predictive model, a Decision Tree Classifier, successfully achieved an accuracy of 84% in identifying cancellations. This model can correctly flag approximately 84 out of every 100 bookings as either canceled or not canceled. Crucially, it provides the hotel with early warnings for high-risk bookings, enabling timely interventions to convert potential cancellations into confirmed stays, thereby protecting revenue.

## Recommendations

1.  **Implement Targeted Engagement for Early Bookers with 'No Deposit' Policies:** Proactively engage guests who book far in advance without a deposit through personalized communication or incentives to confirm their plans, potentially reducing cancellations in this high-risk group by 10-15%.
2.  **Re-evaluate 'Groups' and 'Online TA' Booking Policies:** Review and adjust deposit requirements or cancellation deadlines for 'Groups' and 'Online TA' segments, or explore partnerships with lower-cancellation travel agents, aiming for a 5-8% reduction in overall cancellations.
3.  **Strategically Promote Non-Refundable Deposit Options for At-Risk Bookings:** Offer or promote non-refundable rates, especially for bookings identified by the predictive model as high-risk or during peak seasons. This could secure an additional 15-20% of otherwise highly cancellable bookings.

## Tools & Techniques

Python | Pandas | Scikit-Learn | Matplotlib | Seaborn | Gaussian Naive Bayes | Decision Tree Classifier | Logistic Regression | Google Colab

---

*This project was completed as part of ISOM 835: Predictive Analytics at Suffolk University's
Sawyer Business School.*
