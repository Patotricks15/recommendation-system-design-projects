# Recommendation System Design Projects

A portfolio of independent, production-style recommender systems covering
classical machine-learning methods only — neighbourhood models, matrix
factorization, dimensionality reduction, learning-to-rank, probabilistic
models, bandits, graph algorithms, and diversity re-ranking. No project uses
a neural network, transformer, LLM, or deep-learning framework.

Each project is its own GitHub repository with a reproducible data pipeline,
a declarative feature-engineering layer, offline evaluation, a batch/API
serving entry point, a Floci-compatible AWS Terraform stack, an editable
architecture diagram, and a LaTeX technical report compiled to PDF.

## Projects

| # | Name | Dataset | Main method | Repository |
|---|------|---------|-------------|-------------|
| 1 | Restaurant EASE Recommender | Restaurant consumer ratings | EASE^R (closed-form item-item) | [restaurant-ease-recommender](https://github.com/Patotricks15/restaurant-ease-recommender) |
| 2 | Anime BPR Recommender | Anime Recommendations Database | BPR matrix factorization | [anime-bpr-recommender](https://github.com/Patotricks15/anime-bpr-recommender) |
| 3 | Indonesia Tourism Diversity | Indonesia tourism destinations | MMR followed by greedy-DPP re-ranking | [indonesia-tourism-diversity](https://github.com/Patotricks15/indonesia-tourism-diversity) |
| 4 | MovieLens SVD Ranking | MovieLens 20M | PureSVD | [movielens-svd-ranking](https://github.com/Patotricks15/movielens-svd-ranking) |
| 5 | Clothing Fit Ordinal Recommender | Clothing Fit Dataset | Ordinal learning with conformal prediction | [clothing-fit-ordinal-recommender](https://github.com/Patotricks15/clothing-fit-ordinal-recommender) |
| 6 | Crop Contextual Recommender | Crop Recommendation Dataset | Constrained LinUCB | [crop-contextual-recommender](https://github.com/Patotricks15/crop-contextual-recommender) |
| 7 | Deskdrop Contextual Bandit | CI&T DeskDrop articles | LinUCB and Thompson Sampling with IPS evaluation | [deskdrop-contextual-bandit](https://github.com/Patotricks15/deskdrop-contextual-bandit) |
| 8 | Food.com NMF Recommender | Food.com recipes and reviews | Non-negative Matrix Factorization | [foodcom-nmf-recommender](https://github.com/Patotricks15/foodcom-nmf-recommender) |
| 9 | Retailrocket Session-kNN | Retailrocket e-commerce events | Session-kNN | [retailrocket-session-knn](https://github.com/Patotricks15/retailrocket-session-knn) |
| 10 | Sephora LightFM Retrieval | Sephora products and skincare reviews | Hybrid LightFM/WARP | [sephora-lightfm-retrieval](https://github.com/Patotricks15/sephora-lightfm-retrieval) |
| 11 | Cosmetics CatBoost Ranker | Cosmetics e-commerce events | CatBoost ranking | [cosmetics-catboost-ranker](https://github.com/Patotricks15/cosmetics-catboost-ranker) |
| 12 | LinkedIn Skills Job Matching | LinkedIn jobs and skills | BM25 plus LambdaMART | [linkedin-skills-job-matching](https://github.com/Patotricks15/linkedin-skills-job-matching) |
| 13 | Steam Markov Recommender | Steam game recommendations | Variable-order Markov chain | [steam-markov-recommender](https://github.com/Patotricks15/steam-markov-recommender) |
| 14 | Drug Knowledge Graph PageRank | UCI Drug Review Dataset | Typed Personalized PageRank plus association rules | [drug-knowledge-graph-pagerank](https://github.com/Patotricks15/drug-knowledge-graph-pagerank) |

## Scope

This is part of a larger 23-repository portfolio plan. Projects are added
here as they are completed; each repository listed above is self-contained
and can be cloned, tested, and deployed independently.
