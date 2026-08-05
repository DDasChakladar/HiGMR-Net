# HiGMR-Net : Hierarchical Graph Memory Refinement Network for Multi-View EEG Connectivity Sequence Learning.

HiGMR-Net (Hierarchical Graph Memory Refinement Network) is a graph sequence-learning framework for classifying Frontotemporal Dementia (FTD) and Healthy Controls (HC) from EEG connectivity data. It models Event-Related Potential peak-wise connectivity graphs as an ordered sequence and jointly learns complementary channel-level and region-level brain-network representations.

The framework combines adaptive soft thresholding, region-level graph memory, channel-level edge refinement, a shared graph neural network, and attention-based temporal pooling. Its hierarchical coarse-to-fine design uses persistent region-level connectivity patterns to guide fine-grained channel-edge updates across EEG graph sequences.
