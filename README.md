# LLM Analysis

## 1. Product Categories with Most 1-Star Reviews in Canada
The only product category with multiple 1-star reviews in Canada is:

Prom Dresses: 2 reviews

Other categories may exist with 1-star reviews, but only this one appears more than once in the dataset.
<img width="1968" height="1168" alt="image" src="https://github.com/user-attachments/assets/5ba5f070-4118-401f-b438-bb6a2b336245" />

## 2. Correlation Between Order Value and Rating
Correlation coefficient (r): -0.028

P-value: 0.789

🔎 Interpretation:
There is no meaningful correlation between higher order values and lower ratings.

The correlation is very close to zero and not statistically significant (p > 0.05).

This means order value doesn't impact how customers rate the product in this dataset.
<img width="1568" height="1168" alt="image" src="https://github.com/user-attachments/assets/ef9975dc-0057-4975-b0f2-5f5e4cc86b30" />

## 3.summarize the top 5 complaints and top 5 compliments across all reviews

  The rating distribution is as follows:
| Rating   | Count |
| :------- | :---- |
| **1.0**  | 19    |
| **2.0**  | 15    |
| **2.78** | 19    |
| **3.0**  | 16    |
| **4.0**  | 9     |
| **5.0**  | 14    |

For our analysis:

Negative feedback = Ratings 1.0 and 2.0

Note: There’s a recurring value 2.78, likely indicating missing or placeholder values. I’ll exclude this value from both complaints and compliments analysis as it's neither low nor high feedback.

Proceeding to extract:

Top 5 complaints from reviews with Ratings 1.0 or 2.0

Top 5 compliments from reviews with Ratings 5.0

I’ll perform basic keyword frequency analysis for both. 
📊 Insights Summary

🔴 Top 5 Complaints (Ratings 1 & 2)
| Rank | Word          | Frequency |
| :--- | :------------ | :-------- |
| 1    | **sing**      | 3         |
| 2    | **right**     | 3         |
| 3    | **several**   | 3         |
| 4    | **wait**      | 3         |
| 5    | **necessary** | 3         |

🟢 Top 5 Compliments (Rating 5)
| Rank | Word          | Frequency |
| :--- | :------------ | :-------- |
| 1    | **author**    | 2         |
| 2    | **social**    | 2         |
| 3    | **threat**    | 2         |
| 4    | **office**    | 2         |
| 5    | **financial** | 2         |


## 4. fulfillment statuses with most negative feedback

Fulfillment Status
Delaye       6
Returned     6
Fufilled     5
Cancelled    4
Delayed      3
Fulfilled    2

<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/8118b60c-d37b-409e-9d54-cee658a84b0c" />
