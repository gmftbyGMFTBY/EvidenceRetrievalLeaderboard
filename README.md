# EvidenceRetrievalLeaderboard
The leaderboard for evidence retrieval task in QASPER dataset

## Baselines

1. [LED-base/large](https://aclanthology.org/2021.naacl-main.365.pdf)
2. [TF-IDF](https://aclanthology.org/2021.naacl-main.365.pdf)
3. [LED-base+InfoNCE loss](https://aclanthology.org/2022.naacl-main.207.pdf)
4. [ELECTRA-CE/CE-FT](https://arxiv.org/pdf/2210.01959.pdf)
5. [OpenAI embedding API](https://github.com/mukulpatnaik/researchgpt)
6. [OpenAI chatgpt with prompt](...)
7. [SciDPR](https://github.com/gmftbyGMFTBY/SciDPR)
8. [MultiCite](https://aclanthology.org/2022.naacl-main.137.pdf)


| Model | Evidence-F1 on dev set | Evidence-F1 on test set |
| ----- | ---------------------- | ----------------------- |
| Random paragraph | 2.09 | 1.30 |
| First paragraph | 0.71 | 0.34 |
| TF-IDF | 10.68 | 9.20 |
| LED-base | 23.94 | 29.85 |
| LED-large | 31.25 | 39.37 |
| LED-base+InfoNCE loss | 24.90 | 30.60 |
| ELECTRA-CE | 31.75 | 36.37 |
| ELECTRA-CE-FT | 31.58 | 36.12 |
| OpenAI embedding API | | |
| OpenAI ChatGPT with prompt | | |
| SciDPR | | |
| MultiCite | - | 0.48 |
| Human (lower bound) | - | 71.62 |
