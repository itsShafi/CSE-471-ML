# Review: "Are Language Models Actually Useful for Time Series Forecasting?"

## Summary
This paper critically examines the efficacy of large language models (LLMs) in time series forecasting tasks. Through a series of ablation studies on recent LLM-based forecasting methods, the authors find that removing or replacing the LLM components does not degrade performance; in some cases, it even improves results. The study reveals that pretrained LLMs, despite their computational cost, do not outperform models trained from scratch, fail to capture sequential dependencies effectively, and do not offer advantages in few-shot settings. The findings suggest that simpler architectures may suffice for time series forecasting, challenging the necessity of LLMs in this domain.

## Strengths
- **Comprehensive Analysis**: Thorough ablation studies provide valuable insights into the actual contribution of LLMs in time series forecasting.
- **Challenging Assumptions**: The study promotes reevaluation of trends, encouraging more efficient and effective modeling approaches.
- **Practical Implications**: Highlights the potential of simpler models to achieve comparable or superior performance while reducing computational costs.
- **Reproducibility**: Provides all necessary resources to reproduce the work, enhancing transparency and facilitating further research.

## Weaknesses
- **Scope of Evaluation**: Focused primarily on forecasting tasks; other time series tasks such as classification or anomaly detection remain unexplored.
- **Dataset Diversity**: A broader range of datasets with varying characteristics would strengthen the generalizability of the conclusions.
- **Sequential Dependencies**: A deeper analysis or visualization of why LLMs fail to capture sequential dependencies effectively is needed.

## Suggestions
1. **Expand Task Evaluation**: Include other time series tasks, such as classification or anomaly detection.
2. **Increase Dataset Variety**: Incorporate datasets with different frequencies, lengths, and domains for better robustness evaluation.
3. **Analyze Sequential Dependencies**: Conduct in-depth studies or provide visualizations to explain LLM limitations in capturing sequential dependencies.
4. **Explore Hybrid Models**: Combine LLMs with traditional time series models to assess potential synergistic effects.
#   C S E - 4 7 1 - M L  
 