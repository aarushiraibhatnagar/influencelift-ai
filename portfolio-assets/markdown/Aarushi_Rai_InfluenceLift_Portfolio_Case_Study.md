# InfluenceLift AI - Marketing Analytics Portfolio Collaboration

**Live application:** https://influencelift-ai.streamlit.app  
**Source repository:** https://github.com/mohit231007/influencelift-ai

## Portfolio positioning

InfluenceLift AI is an end-to-end marketing analytics and machine-learning product that estimates influencer-campaign sales before budget is committed. It combines a realistic messy-data problem with an interactive business workflow: single-campaign forecasting, batch CSV analysis, prediction uncertainty, data-quality explanations, and baseline-versus-proposed campaign simulation.

## Collaboration and role attribution

### Aarushi Rai

- Marketing-use-case framing and portfolio positioning
- Business interpretation of campaign reach, engagement, spend, content quality, and sales
- Recruiter-facing storytelling and marketing communication
- Campaign scenario and decision-support framing

### Mohit Bhatnagar

- Data cleaning and data-quality policy
- Statistical modelling and cross-validation
- ML pipeline, inference, and prediction intervals
- FastAPI and Streamlit implementation
- Testing, Docker, CI/CD, deployment, and technical documentation

## Business problem

Marketing teams often invest in influencer campaigns before they know whether the campaign configuration is likely to generate enough sales. Historical records are frequently inconsistent: follower counts may use K/M units, engagement may contain percentage signs, spend may contain currency symbols or negative sign errors, and some values may be missing or implausibly scaled.

InfluenceLift AI transforms those records into an auditable forecast and shows the user exactly which corrections were made.

## Product capabilities

- Parse values such as `125K`, `3.7%`, and `£5,500`
- Detect missing, invalid, and scale-anomalous inputs
- Record every automatic correction
- Predict attributed sales units
- Display empirical lower and upper prediction bounds
- Warn when inputs are outside the model's training range
- Process and download batch CSV predictions
- Compare baseline and proposed campaign scenarios
- Provide a documented FastAPI service

## Model result

The original case study compared linear and nonlinear alternatives using five-fold cross-validation. Tuned Ridge was selected because it provided the strongest balance of predictive performance, stability, explainability, and operational simplicity.

| Metric | Original case-study result |
|---|---:|
| RMSE | 2,000.36 units |
| MAE | 1,592.73 units |
| R² | 0.4925 |

The hosted public application uses deterministic synthetic data because the original challenge dataset is not redistributed.

## Portfolio value

This case study demonstrates the ability to connect marketing questions with practical analytics, communicate uncertainty to non-technical stakeholders, and turn a modelling exercise into a tested and deployed product.

## Recommended GitHub description

> Marketing analytics case study for forecasting influencer campaign sales, auditing messy campaign data, and comparing budget scenarios through a live ML product.

## Recommended LinkedIn project line

> Collaborated on the marketing-use-case framing and portfolio positioning of InfluenceLift AI, a live campaign-sales forecasting product that combines messy-data auditing, model uncertainty, batch analysis, and scenario simulation.
