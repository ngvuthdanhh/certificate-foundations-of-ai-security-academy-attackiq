# 🧪 Lab – Model Extraction Attack

## Objective
Simulate how an attacker can replicate an AI model by querying it.

## Steps
1. Host a trained model behind an API.
2. Query the model with thousands of crafted inputs.
3. Train a substitute model using the input-output pairs.
4. Compare accuracy between original and stolen models.

## Expected Outcome
- Substitute model approximates original performance.
- Shows risks of exposing ML APIs without rate limits.

## Defense Strategies
- Query rate limiting.
- Differential privacy.
- Watermarking model outputs.
