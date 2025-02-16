# Lead-Scoring-Case-Study
Building a Logistic Regression Model for predicting Hot Leads for X Education Company

**Objective**
X Education, an online course provider, aims to enhance its lead conversion strategy by developing a Logistic Regression model to assign Lead Scores (0-100) to potential customers. The goal is to:
•	Prioritize high-potential leads likely to convert.
•	Optimize sales efforts by focusing on leads with higher conversion probabilities.
•	Adapt strategies based on dynamic sales needs.
•	Provide data-driven recommendations to improve decision-making and maximize revenue.

**Problem Statement**

X Education receives a high volume of daily leads, but the conversion rate is only 30%. To improve efficiency, the company needs a data-driven lead scoring system that allows sales teams to focus on high-potential leads instead of indiscriminately engaging with all prospects.

**Methodology & Key Insights**

The model was built using data visualization, feature engineering, and logistic regression. Several insights were derived:
1.	Website Engagement & Lead Conversion
o	Users spending more time on the website are more likely to convert.
o	High visits with low time spent indicate non-engaged users with low conversion.
2.	Lead Source Analysis
o	Welingak Website and References show high conversion rates.
o	Lead Add Form submissions have good conversion rates, while Landing Page Submissions perform poorly.
3.	Specialization & Occupation Impact
o	Banking, Investment, and Insurance professionals convert at higher rates.
o	Working professionals have the highest conversion (92%)—more leads should be sourced from this group.
o	Unemployed individuals have lower conversion rates and need additional focus.
4.	Last Activity & Lead Behavior
o	Leads from "SMS Sent" and "Telephonic Conversations" show good conversion rates.
o	Olark Chat Conversations and Email Bounced leads have very low conversions and require improvement.
5.	Tag Categorization & Email Preference
o	Leads not opting for email contact have higher conversion rates.
o	"Tag_Category High" converts significantly better than "Medium" or "Low" groups.

**Model Performance & Evaluation**

The GLM Regression Model showed excellent performance:
•	Train Data: 90.32% Accuracy | 82.80% Sensitivity | 94.45% Specificity
•	Test Data: 90.83% Accuracy | 90.68% Sensitivity | 90.36% Specificity
•	High AUC (0.96-0.97) indicates the model is highly effective at distinguishing between potential and non-converting leads.
•	Optimal threshold of 0.3 balances accuracy, sensitivity, and specificity.

**Recommendations**

•	Focus on leads from the Welingak Website and SMS Sent category.
•	Prioritize working professionals, as they show high conversion intent.
•	Increase conversion rates for leads from API & Landing Page Submissions.
•	Use CRM to automate follow-ups and optimize call strategies based on conversion probability.
•	Adjust model threshold based on business goals: 
o	If maximizing conversions → Lower threshold (0.3) to improve recall.
o	If minimizing unnecessary calls → Increase threshold (0.7-0.8) to improve precision.
By implementing these strategies, X Education can significantly improve its lead conversion rates while optimizing sales efforts and minimizing unnecessary outreach.

