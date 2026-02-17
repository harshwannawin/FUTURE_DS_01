Task 1

I have created and used Python programs to examine a retail dataset with sales of about $2.29 million. Key company KPIs, regional performance trends, and category profitability have all been aided by this analysis.

Important revelations include:

The profit margin is 12.47%, and the total revenue is roughly $2, 297, 200.86.

When compared to other regions, the West has the biggest sales volume.

In order to increase the profit margins, I advise concentrating marketing efforts on the West region and streamlining the furniture category.

VS Code/Jupyter Notebooks and Python (Pandas, Matplotlib, Seaborn) are among the tools utilised.# FUTURE_DS_01







Task 2

Future Interns | Data Science & Analytics Task 2: Solving the "Leak" in Subscription Retention The Big Picture I recently spent some time digging into the Telco Customer Churn dataset to figure out why subscribers were hitting the "cancel" button. After analyzing over 7,000 customer records, I found that we’re looking at a 26.5% churn rate. It’s not just a number—it’s a clear sign that certain segments of the user base are struggling to find long-term value in the service.

<img width="700" height="423" alt="Screenshot 2026-02-17 012535" src="https://github.com/user-attachments/assets/4ae59448-4520-42ed-b74b-233f3c55a768" />

What the Data is Telling Us While looking at the KPIs, a few specific "red flags" stood out:

The "Newbie" Problem: Most customers who leave do so within their first 6 months. If we don't hook them early, we lose them.

The Fiber Optic Paradox: Interestingly, our Fiber Optic users—who should be our most satisfied high-tier customers—actually represent the highest volume of churn. This suggests a potential gap between price and perceived reliability.

The Contract Trap: Almost all of our losses are coming from Month-to-Month users. Without the stability of a long-term contract, there’s very little friction stopping them from jumping to a competitor.

My Recommendations for Growth Based on these findings, I’ve put together a four-point game plan to plug these leaks:

Prioritize the First 90 Days: We need an automated "Success Program" for new members. A well-timed check-in during the first three months could drastically improve our early-tenure retention.

The "Switch & Save" Incentive: We should offer a small discount (roughly 10%) to nudge Month-to-Month users toward a One-Year plan. Locking in that commitment is worth the slight hit to margins.

A Deep Dive into Service Quality: We need to investigate why Fiber Optic users are unhappy. Is it a technical stability issue or a billing frustration? We can't afford to lose this high-revenue segment.

High-Value Loyalty Perks: For customers paying over $70/month, we should deploy personalized loyalty offers. It’s much cheaper to keep a high-paying customer than to find a new one.

The Toolkit To pull these insights together, I used Python within a VS Code (Jupyter) environment. I relied heavily on Pandas and NumPy for the heavy lifting, using Seaborn and Matplotlib to visualize the KDE distributions and identify the correlation patterns that led to these conclusions.

