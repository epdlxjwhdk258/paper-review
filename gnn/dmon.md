## DMoN (Deep Modularity Networks)

**Paper**  
https://arxiv.org/abs/2006.16904

### One-line Summary
A GCN-based differentiable graph clustering method.

### Problem
Traditional community detection methods are **non-differentiable**, making them difficult to integrate with deep learning frameworks.

### Method
Designs **modularity maximization as a differentiable objective**, enabling end-to-end training with neural networks.

### Key Ideas
- 🔥 **Modularity Loss**: Optimizes clustering by maximizing graph modularity.
- **Soft Cluster Assignment**: Assigns nodes to clusters probabilistically instead of hard assignments.

### Result
Improves performance in graph clustering tasks while enabling integration with deep learning models.

### My Insight
Can be applied to **keyword graph clustering** to extract topic communities from keyword networks.