
```LaTeX
% Self-attention mechanism formula
\text{Attention}(Q, K, V) = \text{softmax}\left(\frac{QK^T}{\sqrt{d_k}}\right)V

% Where:
% Q = Query matrices
% K = Key matrices
% V = Value matrices
% d_k = Dimension of the key vectors

% This creates contextual representations through weighted aggregation
% The result is a vector that contains information from across the context window
```