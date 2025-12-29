
Token prediction formula
$P(x_t | x_{<t})$ = $\text{softmax}(W_e h_t + b)$

Where:
- $x_t$ = Token at position t
- $x_{<t}$ = All previous tokens
- $h_t$ = Hidden state at position $t$
- $W_e$ = Embedding weight matrix
- $b$ = Bias vector

The hidden state $h_t$ is computed through multiple transformer layers:

$$h_t = \text{TransformerLayer}_L(...\text{TransformerLayer}_1(E[x_{<t}]))$$

Where: 
- $E[x_{<t}]$ represents the embedded tokens and each transformer layer performs multi-head attention and feed-forward operations