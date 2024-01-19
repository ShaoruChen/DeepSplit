# DeepSplit: Scalable Verification of Deep Neural Networks via Operator Splitting
`DeepSplit` is a library for solving neural network verification problems through the Alternative Direction Method of Multipliers (ADMM). Details of this method can be found in this paper:
- [DeepSplit: Scalable Verification of Deep Neural Networks via Operator Splitting](https://arxiv.org/abs/2106.09117)  
  Shaoru Chen*, Eric Wong*, J. Zico Kolter, Mahyar Fazlyab (* Equal contribution)  
  Under review of IEEE Open Journal of Control Systems

## Installation 

```
conda create -n deepsplit python=3.10
conda activate deepsplit

# Example: install pytorch on macOS. 
conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 -c pytorch

pip install auto-lirpa
conda install -c conda-forge cvxpy

pip install convex_adversarial
pip install -r requirements.txt
```
