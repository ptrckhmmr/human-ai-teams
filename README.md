# Forming Effective Human-AI Teams: Building Machine Learning Models that Complement the Capabilities of Multiple Experts

This repository contains the code and experiments for our IJCAI 2022 paper "Forming Effective Human-AI Teams: Building Machine Learning Models that Complement the Capabilities of Multiple Experts" by Patrick Hemmer, Sebastian Schellhammer, Michael Vössing, Johannes Jakubik, Gerhard Satzger.

## Abstract
Machine learning (ML) models are increasingly being used in application domains that often involve working together with human experts. In this context, it can be advantageous to defer certain instances to a single human expert when they are difficult to predict for the ML model. While previous work has focused on scenarios with one distinct human expert, in many real-world situations several human experts with varying capabilities may be available. In this work, we propose an approach that trains a classification model to complement the capabilities of multiple human experts. By jointly training the classifier together with an allocation system, the classifier learns to accurately predict those instances that are difficult for the human experts, while the allocation system learns to pass each instance to the most suitable team member—either the classifier or one of the human experts. We evaluate our proposed approach in multiple experiments on public datasets with "synthetic" experts and a real-world medical dataset annotated by multiple radiologists. Our approach outperforms prior work and is more accurate than the best human expert or a classifier. Furthermore, it is flexibly adaptable to teams of varying sizes and different levels of expert diversity.

## Citation

```
@inproceedings{ijcai2022-344,
  title     = {Forming Effective Human-AI Teams: Building Machine Learning Models that Complement the Capabilities of Multiple Experts},
  author    = {Hemmer, Patrick and Schellhammer, Sebastian and Vössing, Michael and Jakubik, Johannes and Satzger, Gerhard},
  booktitle = {Proceedings of the Thirty-First International Joint Conference on
               Artificial Intelligence, {IJCAI-22}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},
  editor    = {Lud De Raedt},
  pages     = {2478--2484},
  year      = {2022},
  month     = {7},
  note      = {Main Track}
  doi       = {10.24963/ijcai.2022/344},
  url       = {https://doi.org/10.24963/ijcai.2022/344},
}
```