# Employee Attrition Prediction
**Author:** Pin-Yi (Judy) Chu  
**Tools:** Python, scikit-learn, pandas, matplotlib  
**Dataset:** IBM HR Analytics (1,470 employees, 35 features)

## Business Problem
Voluntary attrition costs companies 50–200% of an employee's 
annual salary. This project builds a predictive model to identify 
flight risks early and surfaces actionable retention insights 
for HR leadership.

## Key Findings
- Overall attrition rate: 16.1%
- Sales Representatives have highest attrition at 39.8%
- Overtime is the #1 controllable driver — 3x higher attrition risk
- Longer manager relationships independently reduce attrition risk
- Logistic Regression outperformed Random Forest on recall (0.77 vs 0.30)

## Business Recommendations
1. Audit overtime in Sales — workforce planning review needed
2. Invest in manager effectiveness programs
3. Build succession planning and career pathing framework
4. Use performance reviews as proactive attrition risk health checks

## Model Performance
| Model | Recall (Attrition) | Precision | F1 |
|---|---|---|---|
| Logistic Regression | 0.77 | 0.37 | 0.50 |
| Random Forest | 0.30 | 0.44 | 0.35 |

## Why Recall Over Accuracy?
In attrition prediction, missing a flight risk (false negative) 
is far more costly than a false alarm (false positive). 
We optimized for recall to catch as many real leavers as possible.
