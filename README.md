# Data-Prep-Handling-Messy-Data

### In 2–3 sentences, explain when you would prefer one over the other.

Min-Max Scaling transforms features to a fixed range, usually 0 to 1. It is often preferred when the data distribution is not Gaussian or when algorithms like neural networks expect input features within a specific range. However, it is sensitive to outliers.

Standardisation (Z-score normalization) transforms features to have a mean of 0 and a standard deviation of 1. It is generally preferred when the data follows a Gaussian distribution or when algorithms linear regression assume normally distributed data. It handles outliers better than Min-Max Scaling as it doesn't bound the data to a specific range.
