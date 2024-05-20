# Argument Mining with LLMs: A Comparison between In-Context Learning and Fine-Tuning

Paper submitted to SIGDIAL 2024

## Abstract
Argument Mining (AM) is a challenging task in NLP and Argument Type Classification (ATC) is an essential sub-task of AM. Recent developments in NLP have emphasized the ability of LLMs to exhibit impressive emergent capabilities via in-context learning (ICL), which obviates the need for fine-tuning (FT). Our work addresses the ATC task with LLMs from both ICL and FT perspectives. We introduce a two-step ICL approach combining $k$NN-based examples selection and majority vote ensembling. We also present two prompting strategies: single prediction and all-in-one predictions, where argument components are classified either one by one or all at once, respectively. We further introduce a FT approach where additional contextual and structural features are injected into the prompts in various configurations. Our results show that the training-free ICL approach achieves competitive results on the ATC task, but remains below the FT one. Using the FT approach and the all-in-one strategy, we outperform the best results reported for the ATC task.


## In-context learning

The notebooks for the experiments related to the **in-context learning (ICL) approach** are in the folder `InContextLearning/`.


## Fine-tuning

The notebooks for the experiments related to the **fine-tuning (FT) approach** are in the folder `FineTuning/`.
