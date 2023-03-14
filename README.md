# EvidenceRetrievalLeaderboard
The leaderboard for evidence retrieval task in QASPER dataset

## Baselines

1. [LED-base/large](https://aclanthology.org/2021.naacl-main.365.pdf)
2. [TF-IDF](https://aclanthology.org/2021.naacl-main.365.pdf)
3. [LED-base+QE loss](https://aclanthology.org/2022.naacl-main.207.pdf)


| Model | Evidence-F1 on dev set | Evidence-F1 on test set |
| ----- | ---------------------- | ----------------------- |
| LED-base | 23.94 | 29.85 |
| LED-large | 31.25 | 39.37 |
| TF-IDF | 10.68 | 9.20 |
| Random paragraph | 2.09 | 1.30 |
| First paragraph | 0.71 | 0.34 |
| LED-base+QE loss | 24.94 | 30.55 |
| Human (lower bound) | - | 71.62 |

Experiment with extractive subset of QASPER


| Model | Evidence-F1 on dev set | Evidence-F1 on test set |
| ----- | ---------------------- | ----------------------- |
| LED-base | 23.94 | 29.85 |
| LED-large | 31.25 | 39.37 |
| TF-IDF | 10.68 | 9.20 |
| Random paragraph | 2.09 | 1.30 |
| First paragraph | 0.71 | 0.34 |
| Human (lower bound) | - | 71.62 |
