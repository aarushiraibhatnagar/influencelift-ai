# Interview Question Bank

> Two hundred project-specific questions with concise model answers, covering business, ML, coding, MLOps, system design, and behavioural defense.

**Author:** Mohit Bhatnagar  
**Collaboration:** Aarushi Rai - marketing analytics framing and portfolio positioning  
**Live app:** https://influencelift-ai.streamlit.app  
**Repository:** https://github.com/mohit231007/influencelift-ai


## 01. Business framing

**Q1. What decision does InfluenceLift AI support?**

It supports pre-campaign planning: estimate attributed unit sales, assess data quality, and compare campaign configurations before committing budget.

**Q2. Who is the primary user?**

In InfluenceLift AI, who is the primary user is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. Why is sales in units the target?**

In InfluenceLift AI, why is sales in units the target is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. What makes the dataset realistic?**

In InfluenceLift AI, what makes the dataset realistic is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What is the difference between prediction and causation?**

In InfluenceLift AI, what is the difference between prediction and causation is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 02. Data quality

**Q1. How are £ and % symbols parsed?**

In InfluenceLift AI, how are £ and % symbols parsed is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why support K/M/B suffixes?**

In InfluenceLift AI, why support K/M/B suffixes is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. Why are unknown strings converted to missing?**

In InfluenceLift AI, why are unknown strings converted to missing is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. When is absolute-value repair acceptable?**

In InfluenceLift AI, when is absolute-value repair acceptable is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How do you audit a repair?**

In InfluenceLift AI, how do you audit a repair is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 03. Schema and validation

**Q1. What happens when a required column is missing?**

In InfluenceLift AI, what happens when a required column is missing is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why use Pydantic for API contracts?**

In InfluenceLift AI, why use Pydantic for API contracts is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How would you version the schema?**

In InfluenceLift AI, how would you version the schema is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How do you quarantine invalid rows?**

In InfluenceLift AI, how do you quarantine invalid rows is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What is training-serving skew?**

It is a mismatch between transformations used to train the model and those used during inference. The project prevents it by placing cleaning, imputation, scaling, and estimation in one pipeline.

## 04. Feature engineering

**Q1. Why standardise features for Ridge?**

In InfluenceLift AI, why standardise features for Ridge is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why use median imputation?**

In InfluenceLift AI, why use median imputation is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. Which interactions might matter?**

In InfluenceLift AI, which interactions might matter is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. Would you log-transform followers?**

In InfluenceLift AI, would you log-transform followers is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How would timestamp be used safely?**

In InfluenceLift AI, how would timestamp be used safely is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 05. Model selection

**Q1. Why select Ridge?**

Five-fold validation showed Ridge matched or slightly exceeded the nonlinear challenger while remaining stable, interpretable, fast, and easy to operate.

**Q2. What is the baseline model?**

In InfluenceLift AI, what is the baseline model is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. Why did XGBoost not win?**

In InfluenceLift AI, why did XGBoost not win is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. What does regularisation solve?**

In InfluenceLift AI, what does regularisation solve is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. When would you revisit the model choice?**

In InfluenceLift AI, when would you revisit the model choice is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 06. Validation

**Q1. Why five-fold CV?**

It provides multiple out-of-sample estimates and uses data efficiently. The choice is appropriate only if campaigns are exchangeable; grouped or temporal splits are better when dependence exists.

**Q2. How can random folds leak?**

In InfluenceLift AI, how can random folds leak is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. When use GroupKFold?**

In InfluenceLift AI, when use GroupKFold is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. When use time-based splits?**

In InfluenceLift AI, when use time-based splits is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. Why report fold dispersion?**

In InfluenceLift AI, why report fold dispersion is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 07. Metrics

**Q1. What does RMSE measure?**

It is the square root of mean squared error in sales units and penalises large misses more strongly than MAE.

**Q2. How is MAE different?**

In InfluenceLift AI, how is MAE different is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What does R² mean here?**

In InfluenceLift AI, what does R² mean here is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. Why is accuracy context-dependent?**

In InfluenceLift AI, why is accuracy context-dependent is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What additional business metric would you add?**

In InfluenceLift AI, what additional business metric would you add is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 08. Uncertainty

**Q1. How is the interval built?**

The training workflow calculates an absolute residual quantile from out-of-fold predictions and adds/subtracts that band around the point forecast, with a zero lower floor.

**Q2. Why is it not a formal conditional 95% interval?**

In InfluenceLift AI, why is it not a formal conditional 95% interval is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What is heteroscedasticity?**

In InfluenceLift AI, what is heteroscedasticity is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How would conformal prediction help?**

In InfluenceLift AI, how would conformal prediction help is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. Why clamp the lower bound at zero?**

In InfluenceLift AI, why clamp the lower bound at zero is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 09. Out-of-distribution

**Q1. How are range warnings generated?**

In InfluenceLift AI, how are range warnings generated is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why can marginal ranges miss OOD combinations?**

In InfluenceLift AI, why can marginal ranges miss OOD combinations is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What is Mahalanobis distance?**

In InfluenceLift AI, what is Mahalanobis distance is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. Should OOD requests fail?**

In InfluenceLift AI, should OOD requests fail is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How would you monitor extrapolation rate?**

In InfluenceLift AI, how would you monitor extrapolation rate is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 10. Pipeline design

**Q1. Why put cleaning in the pipeline?**

In InfluenceLift AI, why put cleaning in the pipeline is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. What order should cleaning, imputation, scaling, and model follow?**

In InfluenceLift AI, what order should cleaning, imputation, scaling, and model follow is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What is fitted during training?**

In InfluenceLift AI, what is fitted during training is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How do you inspect feature names?**

In InfluenceLift AI, how do you inspect feature names is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How would you add a challenger model?**

In InfluenceLift AI, how would you add a challenger model is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 11. Model artefact

**Q1. What belongs in ModelBundle?**

In InfluenceLift AI, what belongs in ModelBundle is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why expose a model version?**

In InfluenceLift AI, why expose a model version is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. Why not commit joblib files?**

In InfluenceLift AI, why not commit joblib files is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. What is unsafe about untrusted pickle/joblib?**

In InfluenceLift AI, what is unsafe about untrusted pickle/joblib is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How would a model registry help?**

In InfluenceLift AI, how would a model registry help is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 12. FastAPI

**Q1. Why have health and model-info endpoints?**

In InfluenceLift AI, why have health and model-info endpoints is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. What causes a 422 response?**

In InfluenceLift AI, what causes a 422 response is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How do response models help?**

In InfluenceLift AI, how do response models help is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How would you handle large batches?**

In InfluenceLift AI, how would you handle large batches is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How would you add authentication?**

In InfluenceLift AI, how would you add authentication is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 13. Streamlit

**Q1. Why use cache_resource?**

In InfluenceLift AI, why use cache_resource is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. How does the UI handle bad CSVs?**

In InfluenceLift AI, how does the UI handle bad CSVs is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. Why show corrections?**

In InfluenceLift AI, why show corrections is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. Why separate benchmark and demo metrics?**

In InfluenceLift AI, why separate benchmark and demo metrics is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. When would you replace Streamlit?**

In InfluenceLift AI, when would you replace Streamlit is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 14. Scenario analysis

**Q1. How is uplift calculated?**

In InfluenceLift AI, how is uplift calculated is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why is it not causal?**

In InfluenceLift AI, why is it not causal is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What is cost per predicted sale?**

In InfluenceLift AI, what is cost per predicted sale is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How would you include margin?**

In InfluenceLift AI, how would you include margin is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How would you optimise under constraints?**

In InfluenceLift AI, how would you optimise under constraints is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 15. Batch processing

**Q1. How are IDs preserved?**

In InfluenceLift AI, how are IDs preserved is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. What metadata is appended?**

In InfluenceLift AI, what metadata is appended is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How would you chunk a large file?**

In InfluenceLift AI, how would you chunk a large file is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How would asynchronous jobs work?**

In InfluenceLift AI, how would asynchronous jobs work is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How do you validate downloaded output?**

In InfluenceLift AI, how do you validate downloaded output is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 16. Testing

**Q1. What is the current test pyramid?**

In InfluenceLift AI, what is the current test pyramid is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why test multiple Python versions?**

In InfluenceLift AI, why test multiple Python versions is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What is a golden-record test?**

In InfluenceLift AI, what is a golden-record test is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How would property-based tests help?**

In InfluenceLift AI, how would property-based tests help is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What should a smoke test prove?**

In InfluenceLift AI, what should a smoke test prove is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 17. CI/CD

**Q1. What checks run on PRs?**

In InfluenceLift AI, what checks run on PRs is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why compile after tests?**

In InfluenceLift AI, why compile after tests is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How does Streamlit redeploy?**

In InfluenceLift AI, how does Streamlit redeploy is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. What would a staging environment add?**

In InfluenceLift AI, what would a staging environment add is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How would you sign images?**

In InfluenceLift AI, how would you sign images is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 18. Docker

**Q1. Why use python:slim?**

In InfluenceLift AI, why use python:slim is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. How does layer caching work?**

In InfluenceLift AI, how does layer caching work is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What hardening is missing?**

In InfluenceLift AI, what hardening is missing is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. Why run as non-root?**

In InfluenceLift AI, why run as non-root is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What is a container healthcheck?**

In InfluenceLift AI, what is a container healthcheck is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 19. Security

**Q1. Why use synthetic data?**

The original challenge data is not assumed redistributable. Synthetic data preserves a runnable public demo without exposing restricted records.

**Q2. What upload attacks remain?**

In InfluenceLift AI, what upload attacks remain is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How do you avoid secret leakage?**

In InfluenceLift AI, how do you avoid secret leakage is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. Why rate-limit an inference API?**

In InfluenceLift AI, why rate-limit an inference API is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What should not be logged?**

In InfluenceLift AI, what should not be logged is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 20. Responsible AI

**Q1. What uses are out of scope?**

In InfluenceLift AI, what uses are out of scope is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. How can follower count be a proxy?**

In InfluenceLift AI, how can follower count be a proxy is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. Why require human review?**

In InfluenceLift AI, why require human review is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How do you communicate limitations?**

In InfluenceLift AI, how do you communicate limitations is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How would you audit segment performance?**

In InfluenceLift AI, how would you audit segment performance is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 21. Observability

**Q1. Which operational metrics matter?**

In InfluenceLift AI, which operational metrics matter is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Which model metrics matter?**

In InfluenceLift AI, which model metrics matter is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What is correction-rate drift?**

In InfluenceLift AI, what is correction-rate drift is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How do predictions join to outcomes?**

In InfluenceLift AI, how do predictions join to outcomes is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. When should alerts fire?**

In InfluenceLift AI, when should alerts fire is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 22. Scalability

**Q1. What breaks at one million rows?**

In InfluenceLift AI, what breaks at one million rows is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. What component should be extracted first?**

In InfluenceLift AI, what component should be extracted first is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. Why avoid premature microservices?**

In InfluenceLift AI, why avoid premature microservices is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How would autoscaling work?**

In InfluenceLift AI, how would autoscaling work is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What storage layer would you add?**

In InfluenceLift AI, what storage layer would you add is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 23. Storage

**Q1. What is a prediction ledger?**

In InfluenceLift AI, what is a prediction ledger is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why keep raw and derived data separate?**

In InfluenceLift AI, why keep raw and derived data separate is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What keys connect model and outcome?**

In InfluenceLift AI, what keys connect model and outcome is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How do retention policies apply?**

In InfluenceLift AI, how do retention policies apply is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What should remain stateless?**

In InfluenceLift AI, what should remain stateless is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 24. Failure handling

**Q1. What if the model file is missing?**

In InfluenceLift AI, what if the model file is missing is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. What if 60% of a batch is invalid?**

In InfluenceLift AI, what if 60% of a batch is invalid is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What if Streamlit sleeps?**

In InfluenceLift AI, what if Streamlit sleeps is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. What if API latency spikes?**

In InfluenceLift AI, what if API latency spikes is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What belongs in a dead-letter queue?**

In InfluenceLift AI, what belongs in a dead-letter queue is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 25. Performance

**Q1. Where is current latency spent?**

In InfluenceLift AI, where is current latency spent is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why is Ridge inference fast?**

In InfluenceLift AI, why is Ridge inference fast is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What makes row-wise audit slower?**

In InfluenceLift AI, what makes row-wise audit slower is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How do you benchmark batch throughput?**

In InfluenceLift AI, how do you benchmark batch throughput is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. When is caching harmful?**

In InfluenceLift AI, when is caching harmful is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 26. Cost

**Q1. Why is the public demo low cost?**

In InfluenceLift AI, why is the public demo low cost is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. What is the first paid component?**

In InfluenceLift AI, what is the first paid component is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How does an SLA change hosting?**

In InfluenceLift AI, how does an SLA change hosting is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. What costs come from monitoring?**

In InfluenceLift AI, what costs come from monitoring is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How would you estimate TCO?**

In InfluenceLift AI, how would you estimate TCO is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 27. Repository design

**Q1. Why use src layout?**

In InfluenceLift AI, why use src layout is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why keep scripts separate?**

In InfluenceLift AI, why keep scripts separate is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What belongs in MODEL_CARD.md?**

In InfluenceLift AI, what belongs in MODEL_CARD.md is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. Why provide CITATION.cff?**

In InfluenceLift AI, why provide CITATION.cff is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How do contribution files help?**

In InfluenceLift AI, how do contribution files help is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 28. Deployment

**Q1. Why choose Community Cloud?**

In InfluenceLift AI, why choose Community Cloud is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. What limitations does it have?**

In InfluenceLift AI, what limitations does it have is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What is the enterprise alternative?**

In InfluenceLift AI, what is the enterprise alternative is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How do secrets differ by platform?**

In InfluenceLift AI, how do secrets differ by platform is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How do you roll back?**

In InfluenceLift AI, how do you roll back is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 29. Product communication

**Q1. How do you demo in two minutes?**

In InfluenceLift AI, how do you demo in two minutes is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Which metric should be headline?**

In InfluenceLift AI, which metric should be headline is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How do you explain synthetic data?**

In InfluenceLift AI, how do you explain synthetic data is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. What should a recruiter click first?**

In InfluenceLift AI, what should a recruiter click first is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How do you avoid overclaiming?**

In InfluenceLift AI, how do you avoid overclaiming is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 30. Role ownership

**Q1. Which parts did you personally build?**

In InfluenceLift AI, which parts did you personally build is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. How do you credit collaboration?**

In InfluenceLift AI, how do you credit collaboration is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How did you debug Windows setup?**

In InfluenceLift AI, how did you debug Windows setup is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. What trade-off are you most proud of?**

In InfluenceLift AI, what trade-off are you most proud of is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What would you do differently?**

In InfluenceLift AI, what would you do differently is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 31. Python fundamentals

**Q1. Why dataclasses?**

In InfluenceLift AI, why dataclasses is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why type hints?**

In InfluenceLift AI, why type hints is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How does pandas mask work?**

In InfluenceLift AI, how does pandas mask work is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. Why use immutable policy config?**

In InfluenceLift AI, why use immutable policy config is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How do context managers help?**

In InfluenceLift AI, how do context managers help is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 32. Pandas and NumPy

**Q1. How do vectorised operations differ from apply?**

In InfluenceLift AI, how do vectorised operations differ from apply is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. How is NaN propagated?**

In InfluenceLift AI, how is NaN propagated is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How do you preserve index?**

In InfluenceLift AI, how do you preserve index is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. What causes dtype coercion?**

In InfluenceLift AI, what causes dtype coercion is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How do you profile memory?**

In InfluenceLift AI, how do you profile memory is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 33. Scikit-learn

**Q1. What is TransformerMixin?**

In InfluenceLift AI, what is TransformerMixin is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why must fit return self?**

In InfluenceLift AI, why must fit return self is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How does GridSearchCV name nested params?**

In InfluenceLift AI, how does GridSearchCV name nested params is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. What is cross_val_predict?**

In InfluenceLift AI, what is cross_val_predict is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How do pipelines prevent leakage?**

In InfluenceLift AI, how do pipelines prevent leakage is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 34. API coding

**Q1. Sync vs async endpoints?**

In InfluenceLift AI, sync vs async endpoints is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. How do you map exceptions to HTTP codes?**

In InfluenceLift AI, how do you map exceptions to HTTP codes is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What is dependency injection in FastAPI?**

In InfluenceLift AI, what is dependency injection in FastAPI is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How do you test OpenAPI contracts?**

In InfluenceLift AI, how do you test OpenAPI contracts is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What is idempotency?**

In InfluenceLift AI, what is idempotency is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 35. Data engineering

**Q1. How would data arrive from a warehouse?**

In InfluenceLift AI, how would data arrive from a warehouse is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. What is schema evolution?**

In InfluenceLift AI, what is schema evolution is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What is idempotent ingestion?**

In InfluenceLift AI, what is idempotent ingestion is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How would you partition campaign data?**

In InfluenceLift AI, how would you partition campaign data is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What quality checks belong upstream?**

In InfluenceLift AI, what quality checks belong upstream is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 36. MLOps

**Q1. What triggers retraining?**

In InfluenceLift AI, what triggers retraining is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. What is model promotion?**

In InfluenceLift AI, what is model promotion is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. What metadata belongs in a registry?**

In InfluenceLift AI, what metadata belongs in a registry is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. How do you reproduce an old prediction?**

In InfluenceLift AI, how do you reproduce an old prediction is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What is champion-challenger?**

In InfluenceLift AI, what is champion-challenger is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 37. System design

**Q1. What are the system boundaries?**

In InfluenceLift AI, what are the system boundaries is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Why modular monolith?**

The workload is small and stateless. A modular monolith provides clear boundaries without distributed-system cost, while preserving future extraction paths.

**Q3. What are the major containers?**

In InfluenceLift AI, what are the major containers is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. Where are failure domains?**

In InfluenceLift AI, where are failure domains is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. How would multi-tenancy change design?**

In InfluenceLift AI, how would multi-tenancy change design is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 38. Behavioural

**Q1. Describe a difficult data problem.**

In InfluenceLift AI, describe a difficult data problem. is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. Describe choosing simplicity over complexity.**

In InfluenceLift AI, describe choosing simplicity over complexity. is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. Describe a deployment failure.**

In InfluenceLift AI, describe a deployment failure. is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. Describe handling ambiguous requirements.**

In InfluenceLift AI, describe handling ambiguous requirements. is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. Describe a decision you would change.**

In InfluenceLift AI, describe a decision you would change. is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 39. Executive communication

**Q1. Explain the project without ML jargon.**

In InfluenceLift AI, explain the project without ML jargon. is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q2. What business risk does uncertainty reduce?**

In InfluenceLift AI, what business risk does uncertainty reduce is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. How does the system save time?**

In InfluenceLift AI, how does the system save time is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. What evidence supports deployment?**

In InfluenceLift AI, what evidence supports deployment is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. What is the investment case?**

In InfluenceLift AI, what is the investment case is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

## 40. Final challenge

**Q1. Give the 60-second pitch.**

InfluenceLift AI cleans messy influencer campaign records, forecasts sales with a cross-validated Ridge pipeline, communicates uncertainty and extrapolation, supports single/batch/scenario workflows, exposes a FastAPI service, and is tested, containerised, and publicly deployed.

**Q2. Draw the architecture.**

In InfluenceLift AI, draw the architecture. is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q3. Defend Ridge.**

In InfluenceLift AI, defend Ridge. is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q4. Name three limitations.**

In InfluenceLift AI, name three limitations. is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.

**Q5. Propose v1.1.**

In InfluenceLift AI, propose v1.1. is handled by making the assumption explicit, placing reusable logic in the shared package, capturing audit or version metadata, and validating the behaviour with cross-validation, automated tests, or runtime smoke checks as appropriate. The production answer would also state the limitation and the trigger for a more complex design.
