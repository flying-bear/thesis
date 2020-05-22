# Automated Assessment of Discourse Coherence

Automated coherence analysis for the thesis consists of 3 steps;
1. [Preprocessing](https://github.com/flying-bear/thesis/blob/master/coherence/Reembed_and_apply.ipynb) csv with [raw ELAN story transcripts](https://github.com/flying-bear/thesis/blob/master/coherence/stories.csv).
2. [Sentence vectorization](https://github.com/flying-bear/thesis/blob/master/coherence/Reembed_and_apply.ipynb), using 
  - w2v (Mikolov et al., 2013) + SIF (Arora et al., 2017);
  - ELMo (Peters et al., 2018); 
  - BERT (Devlin et al., 2018). 
3. [Ananlysis of coherence](https://github.com/flying-bear/thesis/blob/master/coherence/Apply_metrics.ipynb) based on sentence embeddings:
  - Semi-local coherence;
  - Local coherence;
  - Global coherence;
  - Control global coherence;
  - Cummulative coherence.
  
Qualittative analysis with [PCA](https://github.com/flying-bear/thesis/blob/master/coherence/r/PCA.r) on coherence data was performed using [r](https://github.com/flying-bear/thesis/tree/master/coherence/r).

Qantitative analysis was performed [in python](https://github.com/flying-bear/thesis/blob/master/coherence/Apply_metrics.ipynb). The end of the file contains quantitative statistycal analysis of the coherence data and intra-experimental analysis.
