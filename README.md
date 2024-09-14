
# A/B Test Analysis: Click-Through Rate Improvement


This repository contains a Jupyter notebook that analyzes the results of an A/B test aimed at improving the click-through rate (CTR) by changing the call-to-action (CTA) button text. The analysis compares the experimental group (with the new CTA text) and the control group, using statistical methods to determine the significance of the results.

## Overview

![Alt text](controlexperiment.png)

The goal of this project is to evaluate whether the new CTA button text leads to a statistically and practically significant increase in CTR. The analysis includes:

- Data cleaning and preparation
- Exploratory data analysis (EDA)
- A/B test setup and hypothesis formulation
- Statistical tests to compare the control and experimental groups
- Business implications of the results

## Project Structure

- `ABTesting.ipynb`: The Jupyter notebook containing all code and analysis
- `controlexperiment.png`: The csv dataset that was used for analysis. For this case study, this is a randomly generated file and does not contain actual user data.
- `README.md`: This file

## Key Findings

- The experimental group demonstrated a significantly higher CTR compared to the control group.
- A p-value below 0.05 allowed us to reject the null hypothesis, confirming a statistically significant result.
- The test also met the Minimum Detectable Effect (MDE) of 10%, indicating practical significance.
- These findings suggest that implementing the new CTA text could drive increased user engagement and revenue growth.

## Requirements

To run the notebook, ensure you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scipy
```

Additionally, you will need to have Jupyter Notebook installed. You can do so with:

```bash
pip install notebook
```

## Running the Notebook

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/richardrietdijk/AB_Testing.git
   ```

2. Navigate to the project directory:

   ```bash
   cd AB_Testing
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `ABTesting.ipynb` and run the cells to execute the analysis.

## Conclusion

The results of the A/B test suggest that the new call-to-action button text significantly increases the click-through rate. This improvement has meaningful business implications, such as higher user engagement and potential revenue growth.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
