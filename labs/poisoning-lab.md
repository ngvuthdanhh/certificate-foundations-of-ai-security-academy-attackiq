# 🧪 Lab – Data Poisoning Attack

## Objective
Understand how attackers can inject malicious data into AI training datasets to manipulate model behavior.

## Steps
1. Collect a sample dataset (e.g., MNIST digits).
2. Inject mislabeled samples (e.g., label "7" images as "1").
3. Retrain the model with poisoned data.
4. Test the model’s accuracy on clean vs. poisoned samples.

## Expected Outcome
- Accuracy drops significantly on targeted labels.
- Demonstrates how **data integrity** directly affects ML performance.

## Defense Strategies
- Data validation pipelines.
- Anomaly detection for mislabeled samples.
- Trusted data provenance.
