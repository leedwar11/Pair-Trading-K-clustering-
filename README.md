# Pair Trading via K-Means Clustering

## Project Overview
This project explores a systematic approach to **pair trading** by first reducing the search space using **K-Means clustering**, and then evaluating candidate pairs based on statistical relationships such as correlation and mean-reversion behavior.

Rather than exhaustively testing all possible pairs, clustering is used to group assets with similar characteristics, making pair selection more efficient and economically intuitive.

---

## Methodology
The workflow is structured as follows:

1. **Data Preparation**
   - Collect historical price data
   - Compute returns and relevant statistical features

2. **Feature Engineering**
   - Volatility, return-based features, and normalization
   - Features designed to capture similarity between assets

3. **Clustering**
   - Apply **K-Means clustering** to group assets
   - Use clustering results to limit candidate pairs within the same cluster

4. **Pair Selection & Analysis**
   - Evaluate candidate pairs within clusters
   - Analyze spread behavior and mean-reversion properties

5. **Backtesting**
   - Implement a simple rule-based pairs trading strategy
   - Evaluate performance metrics such as cumulative returns and stability

---

## Key Findings
- Clustering significantly reduces the dimensionality of the pair selection problem
- Candidate pairs selected within clusters exhibit stronger structural similarity
- The approach provides a scalable framework for systematic pair discovery


## Repository Structure
