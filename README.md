# Polimi---Artificial-Neural-Networks-and-Deep-Learning-Competitions
This repo has the codes for the competitions I am participating in for the Neural Networks course at Politecnico Di Milano


For the first copetition we had a time-series classification problem. The dataset was composed of samples of temporal dynamics of body joints and pain prediciton, and the goal was to predict the subject's pain status.
  - The model impelemented is a Bi-GRU model.
  - And attention layer was added to give higher weights for the important data-points that would help get a better generalized model.
  - A CNN layer is added before the Bi-GRU model to act as an efficient automated feature extractor that cleans, abstracts, and condenses the input data before it reaches the recurrent layer.
  - A cosine scheduler was added to quicken the learning process and adjust the learning rate accordingly.
