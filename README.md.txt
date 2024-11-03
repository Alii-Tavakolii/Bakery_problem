# Probability and Statistics Project: The Bakery Problem

## Project Overview
This project explores probability in the context of choosing the best bakery for consistent quality bread. It uses statistical techniques, including the Beta distribution and Thompson Sampling, to model and rank bakeries based on customer satisfaction.

## Problem Statement
We aim to find the probability that each of five bakeries provides good bread. By ranking bakeries based on prior experiences, we maximize the probability of a good experience each day.

## Methodology
1. **Beta Distribution**: Models probability for each bakery, adjusted by successful and unsuccessful attempts.
2. **Thompson Sampling**: Uses prior distribution to make adaptive choices, balancing exploration and exploitation.
3. **Comparison of Approaches**:
   - **N-Test Selection**: Tests bread quality over `N` trials.
   - **Beta Distribution-Based Selection**: Chooses the best bakery using generated values from each bakery’s Beta distribution.
   - **Greedy Exploration Strategy**: Balances bakery selection based on success rates over time.

## Simulation Results
1. **First Approach**: Optimal `N` found to be 12 for about 71.3% satisfaction.
2. **Second Approach**: Achieves 76.1% satisfaction by adapting preferences with Beta distribution.
3. **Third Approach**: Approximately 71% satisfaction using a greedy exploration strategy.

## Conclusion
The Beta Distribution-Based Selection Strategy (Second Approach) performed best, achieving a 76.1% success rate. 

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Alii-Tavakolii/Bakery_problem.git
2. Install dependencies:
   pip install -r requirements.txt
