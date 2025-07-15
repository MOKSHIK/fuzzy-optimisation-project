| Method                | Accuracy | Rules | MF Complexity | Notes                  |
|-----------------------|----------|-------|----------------|-------------------------|
| Baseline FIS          | 90.0%    | 3     | Triangular     | Simple interpretable    |
| GA Optimised FIS      | 93.5%    | 3     | Triangular     | Tuned MFs improved fit  |
| Gradient Optimised FIS| 95.0%    | 3     | Custom curves  | May reduce interpretability |
| Ensemble (Boosted FIS)| 96.1%    | ~9    | Combined MFs   | Accuracy ↑, interpret ↓ |
