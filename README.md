# The spatially embedded recurrent neural network
This repository describes the implementation of spatially embedded recurrent neural networks (seRNNs). The main results are reported in our preprint "Spatially embedded recurrent neural networks reveal widespread links between structural and functional neuroscience findings" (https://www.nature.com/articles/s42256-023-00748-9). We currently provide two example implementations:
- seRNN_demo.ipynb: Baseline implementation of seRNNs using rate-based networks in Tensorflow with a simple cognitive task. This implementation was used in the paper above.
- seRSNN_demo.ipynb: Additional implementation using spiking networks in PyTorch and the DVS128 Gesture Dataset to replicate seRNN findings under new training regime. Analyses of the spiking version are described in a preprint (https://arxiv.org/abs/2409.17693).

If you have a new version of a spatially embedded neural network, please feel free to create a Jupyter Notebook outlining your version and start a pull request. We are more than happy for new networks that expand the seRNN concept to be added to this repository.

Note that if you are interested in a more detailed description of analyses done in the paper above, we provide a CodeOcean Capsule which gives more details on exact training parameters used and also provides the data shown in our figures (https://codeocean.com/capsule/2879348/tree/v2).

See https://www.jachterberg.com/seRNN for more information.
