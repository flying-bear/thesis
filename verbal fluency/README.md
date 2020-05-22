# Automated Analysis of Verbal Fluency Task

[Analysis](https://github.com/flying-bear/thesis/blob/master/verbal%20fluency/clustering_schizo_new.ipynb) consisted of 6 steps:
1. Loading and preprocessing [the dataset](https://github.com/flying-bear/thesis/blob/master/verbal%20fluency/verbal_fluency_schizo.csv);
2. Statistically analyzing [sociolinguistic and psychiatric data](https://github.com/flying-bear/thesis/blob/master/verbal%20fluency/All_psych.csv);
3. Vectorizing words and calculating pairwise cosine similarity;
4. Clustering words automatically using threshold and sharp change methods;
5. Retrieving correct clustering (calculating inter-rater agreement and creating the gold standard);
6. Comparing automated clustering with the gold standard.

Qalitative statistical analysis of [the verbal fluency metrics](https://github.com/flying-bear/thesis/blob/master/verbal%20fluency/to_analyze.csv) using PCA was done using [r](https://github.com/flying-bear/thesis/blob/master/verbal%20fluency/PCA.r).

Qantitative analysis was performed using [python](https://github.com/flying-bear/thesis/blob/master/verbal%20fluency/clustering_schizo_new.ipynb).
