
1. Token Embedding: Mapping discrete tokens to continuous vector space
For vocabulary size V and embedding dimension $d$:
$$E: \{1, 2, ..., V\} \rightarrow \mathbb{R}^d$$
$\text{where } E(i) = \text{embedding of token } i$

2. Self-Attention: The core geometric transformation
For a sequence of $n$ tokens with embeddings $X \in \mathbb{R}^{n \times d}:$

Project to query, key, and value spaces
$$Q = XW^Q, K = XW^K, V = XW^V$$

$\text{ where } W^Q, W^K, W^V \in \mathbb{R}^{d \times d_h}$

Compute attention weights (geometric interpretation: similarity in projected space)
$$A = \text{softmax}\left(\frac{QK^T}{\sqrt{d_h}}\right)  \in \mathbb{R}^{n \times n}$$

Compute weighted values (geometric interpretation: weighted recombination)
$$Z = AV  \in \mathbb{R}^{n \times d_h}$$

3. Multi-head attention: Parallel transformations in different subspaces
$$\text{MultiHead}(X) = \text{Concat}(Z_1, Z_2, ..., Z_h)W^O$$
$\text{ where } Z_i \text{ is from head } i \text{ and } W^O \in \mathbb{R}^{hd_h \times d}$

Geometric interpretation: This creates multiple views of the semantic space,
capturing different types of relationships simultaneously

4. Feed-forward network: Non-linear transformation of each position
$$\text{FFN}(x) = \max(0, xW_1 + b_1)W_2 + b_2$$
$\text{ where } W_1 \in \mathbb{R}^{d \times d_{ff}}, W_2 \in \mathbb{R}^{d_{ff} \times d}$

Geometric interpretation: This applies a point-wise non-linear transformation,
reshaping the manifold locally without considering relationships between positions

5. Layer normalization: Normalizing vectors to improve training stability
$$\text{LayerNorm}(x) = \gamma \odot \frac{x - \mu}{\sqrt{\sigma^2 + \epsilon}} + \beta$$
$\text{ where } \mu \text{ and } \sigma \text{ are mean and std dev of } x$

Geometric interpretation: This projects vectors onto a hypersphere, normalizing their length while preserving direction

6. Residual connections: Preserving information across transformations
$$x' = \text{LayerNorm}(x + \text{MultiHead}(x))$$
$$x'' = \text{LayerNorm}(x' + \text{FFN}(x'))$$

Geometric interpretation: This creates pathways for information to bypass transformations, maintaining access to earlier representations

7. Final layer: Projecting to token probabilities
$$P(x_{t+1}|x_{\leq t}) = \text{softmax}(x''_t W_E^T + b)$$
