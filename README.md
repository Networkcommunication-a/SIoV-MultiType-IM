# SIoV-MultiType-IM

**Code Repository for:**

*Influence Maximization for Multi-Type Information Dissemination in Social Internet of Vehicles*

## 1. Overview

This repository is associated with our research on influence maximization for multi-type information dissemination in Social Internet of Vehicles (SIoV).

The proposed framework integrates spatio-temporal multi-layer graph modeling, GraphSAGE, BiLSTM, and deep reinforcement learning (DQN) to achieve efficient online seed selection in dynamic vehicular networks.

## 2. Dataset

The experiments in this work are conducted using the TAPASCologne vehicular mobility dataset.

The dataset can be accessed through the following link:

**TAPASCologne Dataset:**

https://sumo.dlr.de/docs/Data/Scenarios/TAPASCologne.html

The continuous vehicle mobility traces are discretized into dynamic graph snapshots with a time interval of 20 seconds.

## 3. Experimental Environment

The simulation framework is developed using Python and SUMO (Simulation of Urban MObility).

The experimental study incorporates the following components:

- Multi-layer dynamic graph modeling.
- GraphSAGE-based spatial feature extraction.
- BiLSTM-based temporal feature learning.
- Dynamic candidate pool construction.
- DQN-based seed selection.
- Online incremental seed updating.

## 4. Code Availability

The complete source code of the proposed framework is currently being prepared for public release.

To facilitate reproducibility, the source code will be made publicly available on this GitHub repository upon acceptance of the manuscript.

In the meantime, this repository provides the dataset access information and a description of the experimental setup.

## 5. Citation

If you find this work useful, please cite our paper:

```bibtex
@article{cui_siov_multitype_im,
  title={Influence Maximization for Multi-Type Information Dissemination in Social Internet of Vehicles},
  author={Cui, Yaping and Zhang, Feng and Wu, Dapeng and He, Peng and Wang, Ruyan},
  journal={IEEE Transactions on Mobile Computing},
  year={2026}
}
```

## 6. Contact

For questions regarding this work, please contact the authors.
