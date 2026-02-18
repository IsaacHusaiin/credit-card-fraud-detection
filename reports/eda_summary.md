# EDA Summary (Credit Card Fraud Detection)

1. **Shape:** 284,807 rows × 31 columns (30 features + `Class`)
2. **Class imbalance:** 492 fraud vs 284,315 legitimate  
   - Fraud rate = 0.1727% (≈ 1 in 579 transactions)
3. **Missing values:** 0 (dataset is clean)
4. **Amount distribution:** highly right-skewed with extreme outliers (max ≈ 25,691)
5. **Fraud vs non-fraud Amount:**
   - Fraud has higher mean amount (≈ 122 vs 88)
   - Fraud median is lower (9.25 vs 22), suggesting many small “test” fraud charges alongside some larger fraudulent transactions

   