# Gaussian Naive Bayes (GNB)

## Formula:

P(C|X) ∝ P(C) * Π P(xᵢ | C)

Where:
- P(C|X): Posterior probability of class C given features X
- P(C): Prior probability of class C
- P(xᵢ | C): Likelihood of feature xᵢ given class C (Gaussian: Normal distribution)

For continuous features:
P(xᵢ | C) = (1 / sqrt(2πσ²)) * exp(- (xᵢ - μ)² / (2σ²))
