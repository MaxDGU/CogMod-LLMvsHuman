# CogMod-LLMvsHuman
Cognitive modeling of humans vs. LLM participants on the decision-making experiment (https://kyblab.tuebingen.mpg.de/experiment_ccs2022/experiment_ccs2023/banditexperiment/) by Eric Schulz and Marcel Binz, testing human vs. LLM ability to infer weights from input/output pairs in a linear system of equations. 
Our team observed data (ccs2023_data.csv) of 15 human vs. 15 LLM participants on the above experiment and ran Gaussian similarity vs. linear regression models to fit the data. We observed that humans learn linear equations in a non-linear (Gaussian) fashion, whilst LLM's exhbibit more linear learning patterns. 
Next, we asked: what kind of models are appropriate for human few-shot learning of linear systems of equations? 
Our team built and trained 4 models of human function learning: a tuned gradient-descent model, a self-organizing map, and a rule-based model. Results are in cognitivemodeling_IICCSSS(0) and cognitivemodling_IICCSSS(1) notebooks. Summary in the powerpoint. 
All work was done as part of the 2023 Interdisciplinary Computational Cognitive Science Summer School (iiccsss.org) hackathon on 9/14. 
