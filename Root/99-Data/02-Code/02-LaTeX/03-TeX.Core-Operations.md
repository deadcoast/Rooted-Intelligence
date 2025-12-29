
```LaTeX
% The core mathematical operations in LLMs can be expressed as:

% 1. Embedding Layer (Token to Vector mapping)
E: \mathbb{Z}^n \rightarrow \mathbb{R}^{n \times d}
\text{where } E(x) = [e_{x_1}, e_{x_2}, ..., e_{x_n}]

% 2. Self-Attention Operation
\text{For each head } h \in \{1, 2, ..., H\}:
Q_h = E(x)W_h^Q, K_h = E(x)W_h^K, V_h = E(x)W_h^V

A_h = \text{softmax}\left(\frac{Q_h K_h^T}{\sqrt{d_k}}\right)V_h

\text{MultiHead}(E(x)) = \text{Concat}(A_1, A_2, ..., A_H)W^O

% 3. Feed-Forward Network
\text{FFN}(x) = \max(0, xW_1 + b_1)W_2 + b_2

% 4. Layer Normalization
\text{LayerNorm}(x) = \gamma \frac{x - \mu}{\sqrt{\sigma^2 + \epsilon}} + \beta

% 5. Residual Connections
x' = \text{LayerNorm}(x + \text{MultiHead}(x))
x'' = \text{LayerNorm}(x' + \text{FFN}(x'))

% 6. Final Output Projection
P(x_{t+1}|x_{\leq t}) = \text{softmax}(x''_t W_E^T + b)

% Where:
% x = Input token sequence
% e_x = Embedding vector for token x
% W_h^Q, W_h^K, W_h^V = Weight matrices for query, key, value projections
% W^O = Output projection matrix for attention
% W_1, W_2 = Feed-forward network weights
% \gamma, \beta = Learnable parameters for layer normalization
% W_E = Embedding matrix (shared with the input embedding)
```