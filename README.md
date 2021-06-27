Repository for the course project of Bayesian Statistics and Probabilistic Programming. The purpose is to solve the particle physics classification problem proposed in https://www.kaggle.com/c/cernsignal/overview.

Authors: Adrián Fernández Cid, Aitor Lucas Castellano, Marcos Moreno Blanco & Noel Rabella Gras

In this folder you will find:

**main.pdf**, where we summarise our work, focusing on novel aspects such as the undersampling and the Spike and Slab implementation.

**CERN-RandomSamples-Logistic-JAGS.ipynb**, a notebook with the vanilla and Horseshoe implementations of a logistic regression with random undersampling in JAGS.

**CERN-MinTargSamples-Logistic-JAGS.ipynb**, where we replace the above random undersampling by a one-step targetted removal (OSS or NCR) followed by random undersampling to reach an affordable dataset size.

**CERN-OssSamples-Logistic-JAGS.ipynb**, where we do the same but with our RTR method, implemented with OSS.

**CERN-NcrSamples-Logistic-JAGS.ipynb**, where we implement the RTR with the NCR instead.

**CERN-RandomSamples-Logistic-STAN.ipynb** Marcos

**CERN-OssSamples-Logistic-STAN.ipynb** Marcos

**CERN-RandomSamples-Logistic-SpikeSlab.ipynb** Marcos

**literature/**, a folder with the references we could find and consult.

**data/**, containing the necessary data for running the notebooks.

We have tried for the notebooks to be self-suficient while avoiding too much repetition, so some are more verbose than others: we therefore recommend going through the documents in the above order. 

