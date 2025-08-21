# ai-mmm-evaluation
## AI Marketing Mix Model Evaluation

### Overview

This repository contains Python functions for evaluating the performance of an AI Marketing Mix Model (MMM). The tools focus on both statistical accuracy and business interpretability, helping marketers and data scientists assess how well their modeled revenue aligns with actual revenue across channels and over time.

- The visualizations and metrics included allow you to:
- Compare actual vs modeled revenue.
- Track residuals and errors over time.
- Evaluate performance by marketing channel.
- Examine input feature correlations.
- Detect systematic biases or underperforming channels.

## Features / Functions

| Function                        | Purpose                                                                     |
| ------------------------------- | --------------------------------------------------------------------------- |
| `scatter_actual_vs_modeled(df)` | Plots actual vs modeled revenue to quickly assess overall fit.              |
| `time_series_revenue(df)`       | Visualizes revenue trends over time for both actual and modeled values.     |
| `error_over_time(df)`           | Plots residuals (actual - modeled) to detect temporal bias or drift.        |
| `box_plot_error_by_channel(df)` | Shows distribution of % errors by marketing channel.                        |
| `rmse_by_channel(df)`           | Computes and visualizes RMSE per channel to identify large errors.          |
| `error_histogram(df)`           | Displays the distribution of prediction errors to spot systemic bias.       |
| `correlation_heatmap(df)`       | Shows correlation among numeric input features to detect multicollinearity. |
